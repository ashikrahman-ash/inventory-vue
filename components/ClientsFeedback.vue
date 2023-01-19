<script>


// Swiper slider import
import { Swiper, SwiperSlide } from "swiper/vue";
import "swiper/css";
import "swiper/css/pagination";
import "./loginslider.css";
import { Pagination, Autoplay } from "swiper";


// Image Import
import ratingIcon from "../assets/img/five-start-ratings-icon.svg"
import verifyBadge from "../assets/img/verify-badge-icon.svg"
import feedbackQuote from "../assets/img/clients-feedback-quote.svg"

export default {
	components: {
		Swiper,
		SwiperSlide,
	},
	setup() {
		return {
			
			modules: [Pagination, Autoplay],

			feedbackQuote,
			verifyBadge,

            clientFeedbacks: [
				{
					feedbackQuoteIcon: feedbackQuote,
					feedbackText: "This platform is one of the best companies I have dealt with in US. They’re always happy to help, and i wouldn’t hesitate to recommend them.This platform is one of the best companies I have dealt.",
					ratingIcon: ratingIcon,
					ratingNumber: "4.5/5",
					author: "Daniel Anderson",
					customerStatusIcon: verifyBadge,
					customerStatusText: "Verified Customer",
				},
				{
					feedbackQuoteIcon: feedbackQuote,
					feedbackText: "This platform is one of the best companies I have dealt with in US. They’re always happy to help, and i wouldn’t hesitate to recommend them.This platform is one of the best companies I have dealt.",
					ratingIcon: ratingIcon,
					ratingNumber: "4/5",
					author: "Leslie Alexander",
					customerStatusIcon: verifyBadge,
					customerStatusText: "Verified Customer",
				},
				{
					feedbackQuoteIcon: feedbackQuote,
					feedbackText: "This platform is one of the best companies I have dealt with in US. They’re always happy to help, and i wouldn’t hesitate to recommend them.This platform is one of the best companies I have dealt.",
					ratingIcon: ratingIcon,
					ratingNumber: "4.7/5",
					author: "Kristin Watson",
					customerStatusIcon: verifyBadge,
					customerStatusText: "Verified Customer",
				},
				{
					feedbackQuoteIcon: feedbackQuote,
					feedbackText: "This platform is one of the best companies I have dealt with in US. They’re always happy to help, and i wouldn’t hesitate to recommend them.This platform is one of the best companies I have dealt.",
					ratingIcon: ratingIcon,
					ratingNumber: "4.5/5",
					author: "Daniel Anderson",
					customerStatusIcon: verifyBadge,
					customerStatusText: "Verified Customer",
				},
				{
					feedbackQuoteIcon: feedbackQuote,
					feedbackText: "This platform is one of the best companies I have dealt with in US. They’re always happy to help, and i wouldn’t hesitate to recommend them.This platform is one of the best companies I have dealt.",
					ratingIcon: ratingIcon,
					ratingNumber: "4/5",
					author: "Leslie Alexander",
					customerStatusIcon: verifyBadge,
					customerStatusText: "Verified Customer",
				},
				{
					feedbackQuoteIcon: feedbackQuote,
					feedbackText: "This platform is one of the best companies I have dealt with in US. They’re always happy to help, and i wouldn’t hesitate to recommend them.This platform is one of the best companies I have dealt.",
					ratingIcon: ratingIcon,
					ratingNumber: "4.7/5",
					author: "Kristin Watson",
					customerStatusIcon: verifyBadge,
					customerStatusText: "Verified Customer",
				},
			],
		};
	},


};

</script>

<template>
	<section class="py-[100px] clients-feedback-bg">
		<div class="container mx-auto">
			<h2 class="text-5xl leading-[56px] font-bold text-dark1 pb-14 text-center">
				What clients say
			</h2>
			<div class="">
				<swiper 
				:slidesPerView="3"
				:spaceBetween="30"
				:speed="1200"
				:loop="true"
				:loopFillGroupWithBlank="true"
				:autoplay="{
					delay: 2000,
					disableOnInteraction: false,
				}"
				
				:pagination="{
					clickable: true,
				}"
				:modules="modules"
				class="clientsFeedback">

					<swiper-slide v-for="clientFeedback in clientFeedbacks" class="clients-feedback-item col-span-1 text-center pb-[60px]">
						<div
							class="bg-white border border-dark5 rounded-2xl p-[30px] shadow-[0_30px_60px_rgba(0,0,0,0.05)]">
							<div class="quote-icons mb-5 " >
								<img :src="clientFeedback.feedbackQuoteIcon" alt="Quote">
							</div>
							<p class=" text-base leading-[30px] font-normal text-dark2 pb-12 text-center">
								{{ clientFeedback.feedbackText }}
							</p>
							<div class="ratings-wrap">
								<div class="rating-icon flex gap-[6px] justify-center">
									<span>
										<img :src="clientFeedback.ratingIcon" alt="Ratings">
									</span>
									<span class=" text-xs leading-5 font-medium text-dark3">
										{{ clientFeedback.ratingNumber }}
									</span>
								</div>
								<h4 class="author-name text-[22px] leading-8 text-dark1 font-semibold mt-[3px] mb-[5px] text-center">
									{{ clientFeedback.author }}
								</h4>
								<div class="verify-status flex gap-[5px] justify-center items-center">
									<div class="verify-badge">
										<img :src="clientFeedback.customerStatusIcon" alt="Verify icon">
									</div>
									<p class="text-xs leading-5 font-normal text-dark4">
										{{ clientFeedback.customerStatusText }}
									</p>
								</div>
							</div>
						</div>
					</swiper-slide>
				</swiper>

			</div>
		</div>
	</section>
</template>


<style scoped>
.clients-feedback-bg {
    background: linear-gradient(180deg, #F9F8FC 0%, rgba(249, 248, 252, 0) 100%);
}

.swiper-pagination-bullet-active {
    background: #2E00FF !important;
    height: 10px !important;
    width: 10px !important;
}
</style>


