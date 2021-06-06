<template>
  <header class="hero">
    <div class="name_shadow">
      <h1>
        Name <br />
        Surname
      </h1>
    </div>
  </header>
</template>

<script>
export default {
  name: 'Hero'
}
</script>

<style>
.hero {
  color: whitesmoke;
  text-align: left;
  width: 100%;
  min-height: 100vh;
  top: 0;
  background-image: url("../../img/hero.jpg");
  background-repeat: no-repeat;
  background-size: cover;
  background-position: 20% 0;
  z-index: -1;
}
.name_shadow {
  background-color: rgba(0, 0, 0, 0.4);
  position: absolute;
  top: 60%;
  left: 10%;
}
.hero h1 {
  opacity: 1;
  padding: 20px;
  margin: 0;
}

@media (min-width: 768px) {
  .hero {
    background-position: 20% 60%;
  }
  .name_shadow {
    top: 55%;
    left: 18%;
  }
  .hero h1 {
    font-size: 56px;
  }
}
</style>