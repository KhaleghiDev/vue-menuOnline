<script setup>
defineProps({
  msg: {
    type: String,
    required: true
  }
})
</script>

<template>
  <div class="greetings">
    <img alt="Vue logo" class="logo" src="@/assets/img/logo.png" width="125" height="125" />
    <h1 class="green">{{ msg }}</h1>
    <h3>
      شرکت طلوع سفیران نور ارائه دهنده خدمات ویزای تحصیلی در ایران
    </h3>
  </div>
</template>

<style scoped>
h1 {
  font-weight: 500;
  font-size: 2.6rem;
  position: relative;
  top: -10px;
}

h3 {
  font-size: 1.2rem;
}

.greetings h1,
.greetings h3 {
  text-align: center;
}

@media (min-width: 1024px) {
  .greetings h1,
  .greetings h3 {
    text-align: left;
  }
}
</style>
