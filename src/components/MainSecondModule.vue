<template>
    <div class="slidebar__main">
        <swiper :modules="modules" navigation :pagination="{ clickable: true }" :scrollbar="{ draggable: true }"
            :autoplay="{ delay: 3000 }" loop="{ true }" speed="700" @swiper="onSwiper" class="swiper">
            <swiper-slide class="swiper-slide">
                <div class="first-img__slidebar">
                    <div class="canvas">
                        <div class="trf-logo__slidebar">
                            <img src="../assets/images/man-from-tfr-slidebar.jpg" class="man-from-tfr">
                        </div>
                    </div>
                </div>
            </swiper-slide>
            <swiper-slide class="swiper-slide">
                <img src="../assets/images/second-slide.jpg" class="second-img__slidebar">
            </swiper-slide>
            <swiper-slide class="swiper-slide">
                <img src="../assets/images/child-look.jpg" class="third-img__slidebar">
            </swiper-slide>
        </swiper>
    </div>
</template>

<script>
import { Autoplay, Navigation, Pagination, Scrollbar, A11y } from 'swiper/modules';

import { Swiper, SwiperSlide } from 'swiper/vue';

import 'swiper/scss';
import 'swiper/scss/navigation';
import 'swiper/scss/pagination';

export default {
    components: {
        Swiper,
        SwiperSlide,
    },
    setup() {
        const onSwiper = (swiper) => {
            console.log(swiper);
        };
        return {
            onSwiper,
            modules: [Autoplay, Navigation, Pagination, Scrollbar, A11y],
        };
    },
};
</script>

<style type="scss" scoped>
.slidebar__main {
    .swiper {
        height: 98vh;

        .swiper-slide {
            .first-img__slidebar {
                width: 100%;
                height: 98vh;
                background-size: cover;
                /* filter: brightness(75%); */
                background-position: top center;

                background: url(../assets/images/child-first-slide.jpg);

                .canvas {
                    width: 100%;
                    height: 98vh;
                    display: grid;
                    align-items: center;
                    justify-content: center;
                    background-color: rgba(0, 0, 0, 0.3);

                    .trf-logo__slidebar {
                        background: url(../assets/images/trf.png);

                        display: grid;
                        width: 830px;
                        height: 100%;
                        align-items: center;
                        justify-content: center;
                        background-position: center center;
                        background-size: contain !important;
                        background-repeat: no-repeat !important;

                        .man-from-tfr {
                            width: 395px;
                            height: 580px;
                            object-fit: cover;
                            object-position: 32% 50%;
                            border: 16px solid #eed490;
                        }
                    }
                }

            }

            .second-img__slidebar {
                width: 100%;
                height: 98vh;
                object-fit: cover;
                filter: brightness(75%);
                object-position: center -90px;
            }

            .third-img__slidebar {
                width: 100%;
                height: 98vh;
                object-fit: cover;
                filter: brightness(75%);
                object-position: center center;
            }
        }
    }
}
</style>