<template>
  <main class="main">
    <img class="img_fluid" src="../../img/me.jpg" alt="personal photo" />
    <section>
      <h2>About me</h2>
      <p>
        <b> Your text:</b> <br />
        Lorem ipsum dolor sit amet, consectetur adipiscing elit. Quisque in
        tellus habitasse donec tellus fusce. Nunc arcu fermentum, sit sit orci
        donec quam. Commodo in scelerisque sit cursus facilisis pretium aliquet
        bibendum rhoncus. Aenean aliquam cras velit scelerisque venenatis.
      </p>
      <p>
        <b> Your text:</b> <br />
        Lorem ipsum dolor sit amet, consectetur adipiscing elit. Quisque in
        tellus habitasse donec tellus fusce. Nunc arcu fermentum, sit sit orci
        donec quam. Commodo in scelerisque sit cursus facilisis pretium aliquet
        bibendum rhoncus. Aenean aliquam cras velit scelerisque venenatis.
      </p>
    </section>
  </main>
</template>

<script>
export default {
  name: 'AboutMe'
}
</script>

<style scoped>
.main {
  padding: 20px;
}
.main h2 {
  margin: 0;
}
.img_fluid {
  width: 100%;
  height: auto;
}

@media (min-width: 768px) {
  .main {
    display: flex;
    flex-direction: row-reverse;
    justify-content: space-around;
    align-items: center;
  }
  .img_fluid {
    width: 30%;
    height: auto;
  }
  section {
    padding: 50px;
    max-width: 30%;
    background-color: rgb(228, 253, 223);
  }
}
</style>