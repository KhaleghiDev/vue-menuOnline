<template>
  <div class="contact">
    <h1>تماس با ما</h1>
    <hr />
    <ul class="contact-list">
      <li class="contact-item"><a href="tel:05138426248">ارتباط با دفتر مشهد</a></li>
      <li class="contact-item"><a href="tel:09002488881">ارتباط با پشتیبان</a></li>
      <li class="contact-item"><a href="https://wa.me/989002488881">واتساپ</a></li>
      <li class="contact-item"><a href="https://t.me/edutsn_admin">تلگرام</a></li>
      <li class="contact-item"><a href="https://www.facebook.com/edutsn">فیسبوک</a></li>
      <li class="contact-item"><a href="https://www.instagram.com/edu.tsn/">اینستاگرام</a></li>
    </ul>

  </div>
</template>

<style>
@media (min-width: 1024px) {
  .contact {
    min-height: 100vh;
    display: flex;
    align-items: center;
    flex-direction: column;
    flex-wrap: nowrap;
    align-content: center;
    justify-content: center;
    text-align: center;
}
  .contact   h1 {
    border-bottom: 2px solid #ccc;
    line-height: 2.3em;
  }
  .contact ul li:first-child {
    margin-top: 25px;
  }
  .contact ul li{
    line-height: 2rem;
  }
  .contact ul li a {
    margin-bottom: 10px;
    padding: 5px 7px;
  }
  
}
</style>
