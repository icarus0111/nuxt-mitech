<template>
    <div class="accordion-wrapper section-space--ptb_100">
        <div class="container-fluid">
            <div class="row align-items-center">
                <div class="col-lg-6">
                    <div class="faq-wrapper faq-custom-col">
                        <div class="section-title section-space--mb_40">
                            <h6 class="section-sub-title mb-20">Our company</h6>
                            <h3 class="heading">Share the joy of achieving <span> glorious moments</span> & climbed up the top.</h3>
                        </div>

                        <div id="accordion">
                            <b-card no-body>
                                <b-card-header header-tag="header">
                                    <b-button block v-b-toggle.accordion-1 class="faq-title">
                                        How can we help your business? 
                                        <span> 
                                            <i class="fas fa-chevron-down"></i>
                                            <i class="fas fa-chevron-up"></i> 
                                        </span>
                                    </b-button>
                                </b-card-header>
                                <b-collapse id="accordion-1" visible accordion="my-accordion">
                                    <b-card-body>
                                        <b-card-text>
                                            Through the collaboration with customers in discussing needs and demand, we're able to attain mutual understanding, gain customer trust to offer appropriate advice, and bring about suggestions on suitable technology to transform your business.
                                        </b-card-text>
                                    </b-card-body>
                                </b-collapse>
                            </b-card>

                            <b-card no-body>
                                <b-card-header header-tag="header">
                                    <b-button block v-b-toggle.accordion-2 class="faq-title">
                                        How working process is simplified? 
                                        <span> 
                                            <i class="fas fa-chevron-down"></i>
                                            <i class="fas fa-chevron-up"></i> 
                                        </span>
                                    </b-button>
                                </b-card-header>
                                <b-collapse id="accordion-2" visible accordion="my-accordion">
                                    <b-card-body>
                                        <b-card-text>
                                            Mitech takes into consideration every little detail to make sure the system run smoothly and responsively. Mitech employs a new technique called Minified Technology for securing customers' database & building up highly confidential firewalls.
                                        </b-card-text>
                                    </b-card-body>
                                </b-collapse>
                            </b-card>

                            <b-card no-body>
                                <b-card-header header-tag="header">
                                    <b-button block v-b-toggle.accordion-3 class="faq-title">
                                        How can we help your business? 
                                        <span> 
                                            <i class="fas fa-chevron-down"></i>
                                            <i class="fas fa-chevron-up"></i> 
                                        </span>
                                    </b-button>
                                </b-card-header>
                                <b-collapse id="accordion-3" visible accordion="my-accordion">
                                    <b-card-body>
                                        <b-card-text>
                                            Through the collaboration with customers in discussing needs and demand, we're able to attain mutual understanding, gain customer trust to offer appropriate advice, and bring about suggestions on suitable technology to transform your business.
                                        </b-card-text>
                                    </b-card-body>
                                </b-collapse>
                            </b-card>
                            
                        </div>

                    </div>
                </div>

                <div class="col-lg-6">
                    <div class="rv-video-section">

                        <div class="ht-banner-01 ">
                            <img class="img-fluid border-radus-5 animation_images one wow fadeInDown" src="images/banners/home-processing-video-intro-slider-slide-01-image-02.jpg" alt="image">
                        </div>

                        <div class="ht-banner-02">
                            <img class="img-fluid border-radus-5 animation_images two wow fadeInDown" src="images/banners/home-processing-video-intro-slider-slide-01-image-03.jpg" alt="image">
                        </div>

                        <div class="main-video-box video-popup">
                            <a href="https://www.youtube.com/watch?v=9No-FiEInLA" class="video-link mt-30">
                                <div class="single-popup-wrap">
                                    <img class="img-fluid border-radus-5" src="images/banners/home-processing-video-intro-slider-slide-01-image-01.jpg" alt="">
                                    <div class="ht-popup-video video-button">
                                        <div class="video-mark">
                                            <div class="wave-pulse wave-pulse-1"></div>
                                            <div class="wave-pulse wave-pulse-2"></div>
                                        </div>
                                        <div class="video-button__two">
                                            <div class="video-play">
                                                <span class="video-play-icon"></span>
                                            </div>
                                        </div>
                                    </div>
                                </div>
                            </a>
                        </div>

                        <div class="ht-banner-03">
                            <img class="img-fluid border-radus-5 animation_images three wow fadeInDown" src="images/banners/home-processing-video-intro-slider-slide-01-image-04.jpg" alt="image">
                        </div>

                        <div class="ht-banner-04">
                            <img class="img-fluid border-radus-5 animation_images four wow fadeInDown" src="images/banners/home-processing-video-intro-slider-slide-01-image-05.jpg" alt="image">
                        </div>
                    </div>
                </div>

            </div>
        </div>
    </div>
</template>