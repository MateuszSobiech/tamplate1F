<template>
  <footer class="footer">
    <p class="contact_text">Contact</p>
    <a class="contact_email" href="mailto:email@gmail.com">email@gmail.com</a>
    <div class="social_media">
      <a class="contact_btn" href="https://www.facebook.com/" target="_blank">
        <img src="../../img/fb.svg" alt="" />
      </a>
      <a class="contact_btn" href="https://www.instagram.com/" target="_blank">
        <img src="../../img/ig.svg" alt="" />
      </a>
      <a class="contact_btn" href="https://twitter.com/" target="_blank">
        <img src="../../img/tw.svg" alt="" />
      </a>
    </div>
  </footer>
</template>

<script>
export default {
  name: 'Contact'
}
</script>

<style>
.footer {
  display: flex;
  flex-direction: column;
  text-align: center;
  background-image: linear-gradient(120deg, #d4fc79 0%, #96e6a1 100%);
  padding: 20px 0;
}
.contact_text {
  margin: 0;
  font-size: 48px;
}
.contact_email {
  padding-top: 20px;
}
.social_media {
  display: flex;
  flex-direction: column;
}
.contact_btn {
  margin: 20px auto 0 auto;
  height: 60px;
  width: 60px;
}
.contact_btn img {
  height: 60px;
  width: 60px;
}

@media (min-width: 768px) {
  .footer {
    padding: 30px;
  }
  .contact_email {
    margin: 0 auto;
    width: 25%;
  }
  .social_media {
    margin-top: 20px;
    flex-direction: row;
  }
  a:hover {
    transition: all 0.3s ease;
    transform: scale(1.3);
  }
}
</style>