<template>
  <Layout>
    <section class="sx-component contest-details">
      <div class="sx-head">
        <h1 class="sx-head--page-title"><span>how to play?</span></h1>
      </div>
      <div class="container">
        <div class="sx-body">
          <!-- <h2 class="sx-head--page-title"><span>Detailed view</span></h2> -->
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
                        src="../assets//images/tc-tab.png"
                        alt=""
                        class="img-default"
                      />
                      <img
                        src="../assets//images/tc-tab-white.png"
                        alt=""
                        class="img-white"
                      />
                    </div>
                    <div class="d-flex d-sm-none">
                      <img
                        src="../assets//images/tc-tab-mob.png"
                        alt=""
                        class="img-default"
                      />
                      <img
                        src="../assets//images/tc-tab-white-mob.png"
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
                        src="../assets//images/tp-tab.png"
                        alt=""
                        class="img-default"
                      />
                      <img
                        src="../assets//images/tp-tab-white.png"
                        alt=""
                        class="img-white"
                      />
                    </div>
                    <div class="d-flex d-sm-none">
                      <img
                        src="../assets//images/tp-tab-mob.png"
                        alt=""
                        class="img-default"
                      />
                      <img
                        src="../assets//images/tp-tab-white-mob.png"
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
                        src="../assets//images/px-tab.png"
                        alt=""
                        class="img-default"
                      />
                      <img
                        src="../assets//images/px-tab-white.png"
                        alt=""
                        class="img-white"
                      />
                    </div>
                    <div class="d-flex d-sm-none">
                      <img
                        src="../assets//images/px-tab-mob.png"
                        alt=""
                        class="img-default"
                      />
                      <img
                        src="../assets//images/px-tab-white-mob.png"
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
                      <div
                        class="embed-responsive embed-responsive-16by9 d-none d-sm-block"
                      >
                        <iframe
                          class="embed-responsive-item"
                          src="https://www.youtube.com/embed/NIZd7gFHPBI"
                          frameborder="0"
                          allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
                          allowfullscreen
                        ></iframe>
                      </div>
                      <div
                        class="embed-responsive embed-responsive-16by9 d-block d-sm-none"
                      >
                        <iframe
                          class="embed-responsive-item"
                          src="https://www.youtube.com/embed/NIZd7gFHPBI"
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
                              Select a match from the home screen & then choose
                              a contest
                            </p>
                          </div>
                        </div>
                      </div>
                      <div class="step-item">
                        <span class="sx-icon icon-team-portfolio"></span>
                        <div class="label-wrap">
                          <h5 class="label-head">
                            make a team and join contest
                          </h5>
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
                      <div
                        class="embed-responsive embed-responsive-16by9 d-none d-sm-block"
                      >
                        <iframe
                          class="embed-responsive-item"
                          src="https://www.youtube.com/embed/FfwFLdb_PVE"
                          frameborder="0"
                          allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
                          allowfullscreen
                        ></iframe>
                      </div>
                      <div
                        class="embed-responsive embed-responsive-16by9 d-block d-sm-none"
                      >
                        <iframe
                          class="embed-responsive-item"
                          src="https://www.youtube.com/embed/FfwFLdb_PVE"
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
                              Select a match from the home screen & then choose
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
                                Select one or more units of each player chosen
                                by you to make a Team Portfolio UNIQUE FEATURE
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
                      <div
                        class="embed-responsive embed-responsive-16by9 d-none d-sm-block"
                      >
                        <iframe
                          class="embed-responsive-item"
                          src="https://www.youtube.com/embed/hZoZjDGqKbY"
                          frameborder="0"
                          allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
                          allowfullscreen
                        ></iframe>
                      </div>
                      <div
                        class="embed-responsive embed-responsive-16by9 d-block d-sm-none"
                      >
                        <iframe
                          class="embed-responsive-item"
                          src="https://www.youtube.com/embed/hZoZjDGqKbY"
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
                              Select a match from the home screen &amp; then
                              choose a contest
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
                                Select one or more units of each player chosen
                                by you to make a Team Portfolio UNIQUE FEATURE
                              </li>
                              <li>Select Captain &amp; Vice Captain</li>
                              <li>
                                Join the contest
                                <i
                                  >(typically until 1 hour before the official
                                  match start time)</i
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
                          <h5 class="label-head">
                            Player Trading UNIQUE FEATURE
                          </h5>
                          <div class="label-content">
                            <ul>
                              <li>
                                Additional 100 credits will be allotted to you
                                which can be used only for trading
                              </li>
                              <li>
                                Buy or Sell player units with other participants
                                on the platform to possibly increase your
                                chances of winning
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
        </div>
      </div>
    </section>
  </Layout>
</template>

<script>
export default {
  metaInfo: {
    title: "How To Play",
  },
};
</script>

<style>
</style>