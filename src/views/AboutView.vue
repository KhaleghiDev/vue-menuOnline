<script>
import { RouterLink, RouterView } from "vue-router";
</script>
<template>
  <div class="about">
    <h1>درباره ما</h1>
    <p class="text-about">
      مهاجرت، سفر و تحصیل به خارج از کشور، ویزا، موضوعاتی هستند که این روزها به
      شنیدن آنها عادت کرده ایم. تیم ما در کنار شماست تا تمامی مراحل این مسیر را
      در کوتاه ترین زمان برای شما انجام دهد؛ با کمترین هزینه و به بهترین شکل در
      شرکت طلوع سفیران نور در یک تیم 20 نفره همراه شما هستیم. خدمات ما در زمینه
      مهاجرت به تمامی کشورهای پرطرفدار دنیا در زمینه های مهاجرت تحصیلی است و در
      حال حاضر در بیش از 30 دانشگاه معتبر جهان ارائه خدمات و پذیرش دانشجو داریم.
    </p>
  </div>
  <RouterLink to="/branches">
      <span class="btn-cv">
        رزومه موسس
      </span>
    </RouterLink>
</template>

<style>
@media (max-width: 1023px) {
.btn-cv{
  background: hsla(160, 100%, 37%, 1);
    padding: 3px 11px;
    border-radius: 10px;
}
a:hover{
  background: hsla(160, 100%, 37%, 1);
  box-shadow: #ffa200 0px 4px 12px;
  padding: 5px 8px;
}
}
@media (min-width: 1024px) {
  .about {
    min-height: 100vh;
    display: flex;
    align-items: center;
    flex-direction: column;
    justify-content: center;
  }
  .about h1 {
    border-bottom: 2px solid #ccc;
    line-height: 2.3em;
  }
  .text-about {
    padding: 10px 5px;
    text-align: right;
    line-height: 1.7;
  }
}
</style>
