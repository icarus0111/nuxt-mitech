<template>
    <n-link :to="`/service/${service.id}`" class="ht-box-images style-03 wow move-up">
        <div class="image-box-wrap">
            <div class="box-image">
                <img class="img-fulid" :src="service.icon" alt="icon">
            </div>
            <div class="content">
                <h5 class="heading">{{ service.heading }}</h5>
                <div class="text">{{ service.desc }}</div>
            </div>
        </div>
    </n-link>
</template>

<script>
    export default {
        props: ['service']
    };
</script>