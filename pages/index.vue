<template>
  <div id="landing">
    <div class="hero">
      <div class="hero-text">
        <h1>Savransky Stan</h1>
	<h3>diary notes thoughts...</h3>
        <p>
          <nuxt-link class="btn" to="/posts/">my notes ...</nuxt-link>
        </p>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  components: {},
  data() {
    return {};
  },
  methods: {}
};
</script>

<style lang="scss">
#landing {
  .hero {
    height: 100vh;

    h1 {
      max-width: 80%;
      font-size: 5em;
      margin: auto;
    }

    p {
      font-size: 1em;
    }
  }
}
</style>
