<template>
  <Layout>
    <section class="sx-component refer-friend">
      <div class="sx-head">
        <img
          src="../assets/images/banner/carousel4.png"
          alt=""
          class="d-none d-sm-block sx-head--page-title img"
        />
        <img
          src="../assets/images/banner/carousel4-tab.png"
          alt=""
          class="d-block d-sm-none sx-head--page-title img"
        />
      </div>
      <section class="sx-component download-banner">
        <div class="container">
          <div class="sx-component--wrap">
            <h1 class="sx-head--page-title">
              <span>get the sportzXchange app </span>
            </h1>
            <div class="sx-body">
              <div class="sitenav__download">
                <a href="/android" target="_blank" rel="noopener noreferrer">
                  <button
                    class="sx-btn sx-btn--android icon-android"
                    type="button"
                  >
                    <span>download <em>android</em></span>
                  </button>
                </a>
                <a href="/ios-user">
                  <button class="sx-btn sx-btn--ios icon-apple" type="button">
                    <span>click here <em>IOS</em></span>
                  </button>
                </a>
              </div>
            </div>
          </div>
        </div>
      </section>
      <div class="container">
        <div class="sx-body">
          <h2 class="sx-head--subtitle">how to install?</h2>
          <p class="sx-head--desc my-2">follow 3 easy steps</p>
          <div class="row my-5">
            <div class="col-md-4 card-item">
              <img
                src="../assets/images/step1.png"
                alt=""
                class="card-img img-responsive mx-auto"
              />
              <p class="text-center card-text mt-3">
                This type of file can harm your device. Do you wish to download
                sportzXchange.apk anyway?
              </p>
            </div>
            <div class="col-md-4 card-item">
              <img
                src="../assets/images/step2.png"
                alt=""
                class="card-img img-responsive mx-auto"
              />
              <p class="text-center card-text mt-3">
                Wait for download to finish
              </p>
            </div>
            <div class="col-md-4 card-item">
              <img
                src="../assets/images/step3.png"
                alt=""
                class="card-img img-responsive mx-auto"
              />
              <p class="text-center card-text mt-3">
                Open Settings and Turn on "Allow from this source" to install
                SportzXchange App
              </p>
            </div>
          </div>
        </div>
      </div>
    </section>
  </Layout>
</template>

<script>
export default {
  metaInfo: {
    title: "Android - Download Instructions",
  },
};
</script>

<style>
</style>