<script setup>
import { RouterLink, RouterView } from "vue-router";
import WelcomeItem from "./WelcomeItem.vue";
</script>

<template>

    <footer>
        <div class="footer_list">
            <div class="icon-box">


                <RouterLink to="/">

                    <span> صفحه اصلی</span>

                </RouterLink>
            </div>
            <div class="icon-box">
                <RouterLink to="/about">
                    <span>درباره ما</span>
                </RouterLink>
            </div>
            <div class="icon-box">
                <RouterLink to="/contact">
                    <span>
                    تماس با ما 
                </span>
            </RouterLink>
            </div>
            <div class="icon-box">
               
                <RouterLink to="/lang"> <span>زبان</span></RouterLink>
            </div>
        </div>
    </footer>

</template>


<style scoped>
.footer_list {
    display: none;
}

@media (max-width: 1023px) {
    .footer_list {
        display: flex;
        height: 100%;
    }

    footer {
        background: unset;
        background-color: #fff;
        height: 8vh;
        position: fixed;
        bottom: 0;
    }

    .footer_list a {
        color: #025a82 !important;
    }

    .icon-box .item {
        margin-top: 0;
    }

    .icon-box .item i {
        color: #ffa200;
    }
}
</style>
