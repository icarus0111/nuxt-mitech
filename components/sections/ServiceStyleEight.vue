<template>
    <div class="feature-large-images-wrapper section-space--ptb_100">
        <div class="container">
            <div class="row">
                <div class="col-lg-12">
                    <div class="section-title-wrap text-center section-space--mb_60">
                        <h6 class="section-sub-title mb-20">{{ data.featureSectionSubTitle }}</h6>
                        <h3 class="heading" v-html="data.featureSectionTitle">{{ data.featureSectionTitle }}</h3>
                    </div>
                </div>
            </div>
            <div class="row">
                <div class="col-12">
                    <div class="row">
                        <div class="col-lg-4 col-md-6 wow move-up" v-for="service in data.services.slice(14, 17)" :key="service.id">
                            <n-link :to="`/service/${service.id}`" class="ht-large-box-images style-03">
                                <div class="large-image-box">
                                    <div class="box-image">
                                        <div class="default-image">
                                            <img class="img-fluid" :src="service.image" alt="image">
                                        </div>
                                    </div>
                                    <div class="content">
                                        <h5 class="heading">{{ service.heading }}</h5>
                                        <div class="text">{{ service.desc }}</div>
                                        <div class="box-images-arrow">
                                            <span class="button-text">Discover now</span>
                                            <i class="far fa-long-arrow-right"></i>
                                        </div>
                                    </div>
                                </div>
                            </n-link>
                        </div>
                    </div>
                    <div class="section-under-heading text-center section-space--mt_20">
                        <n-link to="/it-solutions">
                            Learn more about how we work span 
                            <i class="ml-1 button-icon far fa-long-arrow-right"></i>
                        </n-link>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
    import data from '../../data/service.json';
    export default {
        data () {
            return {
                data
            }
        }
    };
</script>