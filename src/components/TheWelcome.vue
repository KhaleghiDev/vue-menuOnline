<script setup>
import WelcomeItem from "./WelcomeItem.vue";
import DocumentationIcon from "./icons/IconDocumentation.vue";
import ToolingIcon from "./icons/IconTooling.vue";
import EcosystemIcon from "./icons/IconEcosystem.vue";
import CommunityIcon from "./icons/IconCommunity.vue";
import SupportIcon from "./icons/IconSupport.vue";
</script>

<template>
  <WelcomeItem>
    <template #icon>
      <DocumentationIcon />
    </template>
    <h3>بورسیه تحصیلی</h3>
    <p>ارائه دهنده خدمات بورسیه تحصیلی</p>
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <ToolingIcon />
    </template>
    <h3>بسته های جامع تحصیلی</h3>
    <p>ارائه دهنده بسته های جامع برای رفاه تحصیلی بیشتر دانشجویان</p>
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <EcosystemIcon />
    </template>
    <h3>  خدمات vip</h3>
    <p>ارائه دهنده خدمات بورسیه تحصیلی</p>
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <CommunityIcon />
    </template>
    <h3>ارتباط  با دانشجو  </h3>
    <p>از ابتدا درخواست تا بعد از فارغ التحصیلی</p>
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <SupportIcon />
    </template>
    <h3>بیشترین رضایت مشتری </h3>
    <p>ارائه دهنده خدمات بورسیه تحصیلی</p>
  </WelcomeItem>
</template>
<style>
i{
  color: #ffa200 !important;
}
</style>