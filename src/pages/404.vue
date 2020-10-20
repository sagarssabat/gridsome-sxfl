<template>
  <Layout>
    <section class="sx-component error-page">
      <div class="container">
        <div class="error-wrap text-center">
          <div class="error-img mx-auto">
            <img src="../assets/images/404.png" alt="" />
          </div>
          <div class="error-content">
            <p class="error-text--highlight">oops!</p>
            <p class="error-text">
              We can't seem to find a page that you are looking for...
            </p>
          </div>
          <a href="/" class="sx-btn--home">
            <button type="button" class="sx-btn">back to home</button>
          </a>
        </div>
      </div>
    </section>
  </Layout>
</template>

<script>
export default {
  metaInfo: {
    title: "Page not found",
  },
};
</script>

<style>
</style>