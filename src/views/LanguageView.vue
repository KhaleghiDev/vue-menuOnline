<template>
  <div class="lang">
    <ul class="lang">
      <li class="lang-item"><a href="/fa">فارسی</a></li>
      <li class="lang-item"><a href="/lang">English</a></li>
      <li class="lang-item"><a href="/lang">عربی</a></li>
      <li class="lang-item"><a href="/lang">اردو</a></li>
    </ul>
  </div>
</template>

<style>
@media (min-width: 1024px) {
  li.lang-item {
    border: 3px solid #000;
    text-align: center;
    margin-bottom: 8px;
  }
  .lang {
    min-height: 100vh;
    display: flex;
    align-items: center;
    flex-direction: column;
    align-content: center;
    justify-content: center;
}
}
</style>
