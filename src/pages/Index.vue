<template>
  <Layout>
    <section class="sx-component home-bg">
      <VueSlickCarousel :arrows="true" :dots="true" :adaptiveHeight="true">
        <div class="carousel1">
          <div class="content-wrap">
            <img
              src="../assets/images/banner/carousel1.jpg"
              alt=""
              class="d-none d-sm-block"
            />
            <img
              src="../assets/images/banner/carousel1-mob.jpg"
              alt=""
              class="d-block d-sm-none"
            />
          </div>
        </div>
        <div class="carousel2">
          <div class="content-wrap">
            <img
              src="../assets/images/banner/carousel2.jpg"
              alt=""
              class="d-none d-sm-block"
            />
            <img
              src="../assets/images/banner/carousel2-mob.jpg"
              alt=""
              class="d-block d-sm-none"
            />
          </div>
        </div>
        <div class="carousel3">
          <div class="content-wrap">
            <img
              src="../assets/images/banner/carousel3.jpg"
              alt=""
              class="d-none d-sm-block"
            />
            <img
              src="../assets/images/banner/carousel3-mob.jpg"
              alt=""
              class="d-block d-sm-none"
            />
          </div>
        </div>
        <div class="carousel4">
          <div class="content-wrap">
            <img
              src="../assets/images/banner/carousel4.jpg"
              alt=""
              class="d-none d-sm-block"
            />
            <img
              src="../assets/images/banner/carousel4-mob.jpg"
              alt=""
              class="d-block d-sm-none"
            />
          </div>
        </div>
      </VueSlickCarousel>
    </section>
    <section class="sx-component download-banner">
      <div class="container">
        <div class="sx-component--wrap">
          <h2 class="sx-head--page-title" data-aos="fade-right">
            <span>get the sportzXchange app </span>
          </h2>
          <div class="sx-body" data-aos="fade-left">
            <div class="sitenav__download">
              <a href="/android">
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
    <section class="sx-component campaign d-none">
      <div class="container">
        <div class="sx-component--wrap">
          <h2 class="sx-head--page-title"><span>user ratings</span></h2>
          <div class="sx-body">
            <div class="row">
              <div class="card-item text-center col-md-4 col">
                <div class="card-wrap">
                  <div
                    class="card-icon icon-thumbs-up icon-thumbs-up--bohot"
                  ></div>
                  <h4 class="card-title">bohot sahi hai</h4>
                  <span class="card-rating">75</span>
                </div>
              </div>
              <div class="card-item text-center col-md-4 col">
                <div class="card-wrap">
                  <div class="card-icon icon-thumbs-up"></div>
                  <h4 class="card-title">sahi hai</h4>
                  <span class="card-rating">15</span>
                </div>
              </div>
              <div class="card-item text-center col-md-4 col">
                <div class="card-wrap">
                  <div class="card-icon icon-thumbs-down"></div>
                  <h4 class="card-title">nahi hai</h4>
                  <span class="card-rating">10</span>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>
    <section class="sx-component section-why d-block">
      <div class="container">
        <h2 class="sx-head--page-title">
          <span>contests for every skill level</span>
        </h2>
        <div class="sx-body">
          <div class="sx-body--content">
            <p>
              SportzXchange understands that customers have different gaming
              requirements, different outlooks and carry different skills and
              therefore we don’t believe in a
              <strong>“one size fits all”</strong> system. We are a unique
              fantasy sport platform that offers three different types of
              contests which are designed to suit players of different skill
              levels and interest.
            </p>
          </div>
        </div>
      </div>
      <div class="card--bg py-2">
        <div class="container">
          <div class="row justify-content-center">
            <div class="col-md-4">
              <div
                class="card"
                id="teamContest-tab"
                data-aos="flip-up"
                data-aos-easing="linear"
                data-aos-duration="500"
              >
                <div class="card-body">
                  <h5 class="card-title">beginner</h5>
                  <img
                    class="card-img-contest"
                    src="../assets/images/team-contest-white.png"
                  />
                </div>
                <div class="py-2 space-bg">
                  <div class="contest-name">
                    <img
                      class="card-img-top"
                      src="../assets/images/team-contest-name.png"
                    />
                  </div>
                </div>
              </div>
            </div>
            <div class="col-md-4">
              <div
                class="card"
                id="teamPortfolio-tab"
                data-aos="flip-up"
                data-aos-easing="linear"
                data-aos-duration="500"
              >
                <div class="card-body">
                  <h5 class="card-title">intermediate</h5>
                  <img
                    class="card-img-contest"
                    src="../assets/images/team-portfolio-contest-white.png"
                  />
                </div>
                <div class="py-2 space-bg">
                  <div class="contest-name">
                    <img
                      class="card-img-top"
                      src="../assets/images/team-portfolio-name.png"
                    />
                  </div>
                </div>
              </div>
            </div>
            <div class="col-md-4">
              <div
                class="card"
                id="playerXchange-tab"
                data-aos="flip-up"
                data-aos-easing="linear"
                data-aos-duration="500"
              >
                <div class="card-body">
                  <h5 class="card-title">expert</h5>
                  <img
                    class="card-img-contest"
                    src="../assets/images/player-trading-white.png"
                  />
                </div>
                <div class="py-2 space-bg">
                  <div class="contest-name">
                    <img
                      class="card-img-top"
                      src="../assets/images/player-xchange-name.png"
                    />
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>
    <section class="sx-component section-how contest-details">
      <div class="container">
        <h2 class="sx-head--page-title"><span>how to play?</span></h2>
        <div class="sx-body">
          <div class="row">
            <div class="sx-body--content col-md-6 offset-md-3 d-none">
              <ul>
                <li>
                  <p>
                    <strong>Beginner:</strong> 11 players : one unit of each
                    player : 300 credit
                  </p>
                </li>
                <li>
                  <p>
                    <strong>Intermediate:</strong> 11 players : upto 3 units of
                    each player: 400 credit
                  </p>
                </li>
                <li>
                  <p>
                    <strong>Expert:</strong> 11 players : upto 3 units of each
                    player : 500 credits
                  </p>
                </li>
              </ul>
            </div>
          </div>
        </div>
      </div>
      <div class="sx-tabs">
        <div class="container">
          <ul class="nav nav-tabs nav-justified" id="myTab" role="tablist">
            <li class="nav-item">
              <a
                class="nav-link active"
                id="teamContest-tab"
                data-toggle="tab"
                href="#teamContest"
                role="tab"
                aria-controls="teamContest"
                aria-selected="true"
              >
                <div class="d-none d-sm-flex">
                  <img
                    src="../assets/images/tc-tab.png"
                    alt=""
                    class="img-default"
                  />
                  <img
                    src="../assets/images/tc-tab-white.png"
                    alt=""
                    class="img-white"
                  />
                </div>
                <div class="d-flex d-sm-none">
                  <img
                    src="../assets/images/tc-tab-mob.png"
                    alt=""
                    class="img-default"
                  />
                  <img
                    src="../assets/images/tc-tab-white-mob.png"
                    alt=""
                    class="img-white"
                  />
                </div>
              </a>
            </li>
            <li class="nav-item">
              <a
                class="nav-link"
                id="teamPortfolio-tab"
                data-toggle="tab"
                href="#teamPortfolio"
                role="tab"
                aria-controls="teamPortfolio"
                aria-selected="false"
              >
                <div class="d-none d-sm-flex">
                  <img
                    src="../assets/images/tp-tab.png"
                    alt=""
                    class="img-default"
                  />
                  <img
                    src="../assets/images/tp-tab-white.png"
                    alt=""
                    class="img-white"
                  />
                </div>
                <div class="d-flex d-sm-none">
                  <img
                    src="../assets/images/tp-tab-mob.png"
                    alt=""
                    class="img-default"
                  />
                  <img
                    src="../assets/images/tp-tab-white-mob.png"
                    alt=""
                    class="img-white"
                  />
                </div>
              </a>
            </li>
            <li class="nav-item">
              <a
                class="nav-link"
                id="playerXchange-tab"
                data-toggle="tab"
                href="#playerXchange"
                role="tab"
                aria-controls="playerXchange"
                aria-selected="false"
              >
                <div class="d-none d-sm-flex">
                  <img
                    src="../assets/images/px-tab.png"
                    alt=""
                    class="img-default"
                  />
                  <img
                    src="../assets/images/px-tab-white.png"
                    alt=""
                    class="img-white"
                  />
                </div>
                <div class="d-flex d-sm-none">
                  <img
                    src="../assets/images/px-tab-mob.png"
                    alt=""
                    class="img-default"
                  />
                  <img
                    src="../assets/images/px-tab-white-mob.png"
                    alt=""
                    class="img-white"
                  />
                </div>
              </a>
            </li>
          </ul>
          <div class="tab-content" id="myTabContent">
            <div
              class="tab-pane fade show active"
              id="teamContest"
              role="tabpanel"
              aria-labelledby="teamContest-tab"
            >
              <div class="row">
                <div class="col-12">
                  <div class="embed-responsive embed-responsive-16by9">
                    <iframe
                      class="embed-responsive-item"
                      src="https://www.youtube.com/embed/NIZd7gFHPBI?rel=0&showinfo=0"
                      frameborder="0"
                      allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
                      allowfullscreen
                    ></iframe>
                  </div>
                </div>
              </div>
              <div class="sx-steps sx-static-info">
                <div class="step-list">
                  <div class="step-item">
                    <span class="sx-icon icon-pick-match"></span>
                    <div class="label-wrap">
                      <h5 class="label-head">select a match</h5>
                      <div class="label-content">
                        <p>
                          Select a match from the home screen & then choose a
                          contest
                        </p>
                      </div>
                    </div>
                  </div>
                  <div class="step-item">
                    <span class="sx-icon icon-team-portfolio"></span>
                    <div class="label-wrap">
                      <h5 class="label-head">make a team and join contest</h5>
                      <div class="label-content">
                        <ul>
                          <li>Initial budget: 300 credits</li>
                          <li>Select 11 players</li>
                          <li>Select Captain &amp; Vice Captain</li>
                          <li>Join The Contest <i></i></li>
                          <li>
                            More on
                            <a href="portfolio-requirements.html"
                              >Team requirements</a
                            >
                          </li>
                        </ul>
                      </div>
                    </div>
                  </div>
                  <div class="step-item">
                    <span class="sx-icon icon-winner"></span>
                    <div class="label-wrap">
                      <h5 class="label-head">Follow the match</h5>
                      <div class="label-content">
                        <p>
                          Follow the match and keep track of your Team Value
                          using the
                          <a href="points-system.html"
                            >Fantasy Cricket Points System</a
                          >
                        </p>
                      </div>
                    </div>
                  </div>
                </div>
              </div>
            </div>
            <div
              class="tab-pane fade"
              id="teamPortfolio"
              role="tabpanel"
              aria-labelledby="teamPortfolio-tab"
            >
              <div class="row">
                <div class="col-12">
                  <div class="embed-responsive embed-responsive-16by9">
                    <iframe
                      class="embed-responsive-item"
                      src="https://www.youtube.com/embed/FfwFLdb_PVE?rel=0"
                      frameborder="0"
                      allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
                      allowfullscreen
                    ></iframe>
                  </div>
                </div>
              </div>
              <div class="sx-steps sx-static-info">
                <div class="step-list">
                  <div class="step-item">
                    <span class="sx-icon icon-pick-match"></span>
                    <div class="label-wrap">
                      <h5 class="label-head">select a match</h5>
                      <div class="label-content">
                        <p>
                          Select a match from the home screen & then choose a
                          contest
                        </p>
                      </div>
                    </div>
                  </div>
                  <div class="step-item">
                    <span class="sx-icon icon-team-portfolio"></span>
                    <div class="label-wrap">
                      <h5 class="label-head">
                        make a team portfolio and join the contest
                      </h5>
                      <div class="label-content">
                        <ul>
                          <li>Initial budget – 400 credits</li>
                          <li>Select 11 players</li>
                          <li>
                            Select one or more units of each player chosen by
                            you to make a Team Portfolio UNIQUE FEATURE
                          </li>
                          <li>Select Captain &amp; Vice Captain</li>
                          <li>Join the contest <i></i></li>
                          <li>
                            More on
                            <a href="portfolio-requirements.html"
                              >Team Portfolio requirements</a
                            >
                          </li>
                        </ul>
                      </div>
                    </div>
                  </div>
                  <div class="step-item">
                    <span class="sx-icon icon-winner"></span>
                    <div class="label-wrap">
                      <h5 class="label-head">Follow the match</h5>
                      <div class="label-content">
                        <p>
                          Follow the match and keep track of your Team Value
                          using the
                          <a href="points-system.html"
                            >Fantasy Cricket Points System</a
                          >
                        </p>
                      </div>
                    </div>
                  </div>
                </div>
              </div>
            </div>
            <div
              class="tab-pane fade"
              id="playerXchange"
              role="tabpanel"
              aria-labelledby="playerXchange-tab"
            >
              <div class="row">
                <div class="col-12">
                  <div class="embed-responsive embed-responsive-16by9">
                    <iframe
                      class="embed-responsive-item"
                      src="https://www.youtube.com/embed/hZoZjDGqKbY?rel=0"
                      frameborder="0"
                      allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
                      allowfullscreen
                    ></iframe>
                  </div>
                </div>
              </div>
              <div class="sx-steps sx-static-info">
                <div class="step-list">
                  <div class="step-item">
                    <span class="sx-icon icon-pick-match"></span>
                    <div class="label-wrap">
                      <h5 class="label-head">select a match</h5>
                      <div class="label-content">
                        <p>
                          Select a match from the home screen &amp; then choose
                          a contest
                        </p>
                      </div>
                    </div>
                  </div>
                  <div class="step-item">
                    <span class="sx-icon icon-team-portfolio"></span>
                    <div class="label-wrap">
                      <h5 class="label-head">
                        make a team portfolio and join the contest
                      </h5>
                      <div class="label-content">
                        <ul>
                          <li>Initial budget – 400 credits</li>
                          <li>Select 11 players</li>
                          <li>
                            Select one or more units of each player chosen by
                            you to make a Team Portfolio UNIQUE FEATURE
                          </li>
                          <li>Select Captain &amp; Vice Captain</li>
                          <li>
                            Join the contest
                            <i
                              >(typically until 1 hour before the official match
                              start time)</i
                            >
                          </li>
                          <li>
                            More on
                            <a href="portfolio-requirements.html"
                              >Team Portfolio requirements</a
                            >
                          </li>
                        </ul>
                      </div>
                    </div>
                  </div>
                  <div class="step-item">
                    <span class="sx-icon icon-trading"></span>
                    <div class="label-wrap">
                      <h5 class="label-head">Player Trading UNIQUE FEATURE</h5>
                      <div class="label-content">
                        <ul>
                          <li>
                            Additional 100 credits will be allotted to you which
                            can be used only for trading
                          </li>
                          <li>
                            Buy or Sell player units with other participants on
                            the platform to possibly increase your chances of
                            winning
                          </li>
                        </ul>
                      </div>
                    </div>
                  </div>
                  <div class="step-item">
                    <span class="sx-icon icon-winner"></span>
                    <div class="label-wrap">
                      <h5 class="label-head">Follow the match</h5>
                      <div class="label-content">
                        <p>
                          Follow the match and keep track of your Team Value
                          using the
                          <a href="portfolio-requirements.html"
                            >Fantasy Cricket Points System</a
                          >
                        </p>
                      </div>
                    </div>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>
    <section class="sx-component download-app">
      <div class="container">
        <h2 class="sx-head--page-title">
          <span>Get the SportzXchange App</span>
        </h2>
        <div class="sx-body">
          <div class="sitenav__download">
            <a href="android-user.html">
              <button class="sx-btn sx-btn--android icon-android" type="button">
                <span>download <em>android</em></span>
              </button>
            </a>
            <a href="ios-user.html">
              <button class="sx-btn sx-btn--ios icon-apple" type="button">
                <span>click here <em>IOS</em></span>
              </button>
            </a>
          </div>
        </div>
      </div>
    </section>
  </Layout>
</template>

<script>
import VueSlickCarousel from "vue-slick-carousel";
import "vue-slick-carousel/dist/vue-slick-carousel.css";
// optional style for arrows & dots
import "vue-slick-carousel/dist/vue-slick-carousel-theme.css";
export default {
  metaInfo: {
    title: "Hello, world!",
  },
  components: { VueSlickCarousel },
};
</script>

<style>
.home-links a {
  margin-right: 1rem;
}
</style>
