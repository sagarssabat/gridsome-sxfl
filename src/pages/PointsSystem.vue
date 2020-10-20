<template>
  <Layout>
    <div class="sx-component sx-points-system sx-static-info">
      <div class="sx-head">
        <h1 class="sx-head--page-title">
          <span>fantasy cricket Points system</span>
        </h1>
      </div>
      <div class="container">
        <div class="sx-body">
          <div class="sx-tabs">
            <nav>
              <div
                class="nav nav-tabs nav-justified"
                id="nav-tab"
                role="tablist"
              >
                <a
                  class="nav-item nav-link active"
                  id="nav-t20-tab"
                  data-toggle="tab"
                  href="#nav-t20"
                  role="tab"
                  aria-controls="nav-t20"
                  aria-selected="true"
                  >t20</a
                >
                <a
                  class="nav-item nav-link"
                  id="nav-odi-tab"
                  data-toggle="tab"
                  href="#nav-odi"
                  role="tab"
                  aria-controls="nav-odi"
                  aria-selected="false"
                  >odi</a
                >
                <a
                  class="nav-item nav-link"
                  id="nav-test-tab"
                  data-toggle="tab"
                  href="#nav-test"
                  role="tab"
                  aria-controls="nav-test"
                  aria-selected="false"
                  >test</a
                >
              </div>
            </nav>
            <div class="tab-content" id="nav-tabContent">
              <div
                class="tab-pane fade show active"
                id="nav-t20"
                role="tabpanel"
                aria-labelledby="nav-home-tab"
              >
                <!-- Batting Points System -->
                <div class="table-responsive sx-table">
                  <table class="table table-hover table-striped">
                    <thead>
                      <tr>
                        <!-- <th scope="col">#</th> -->
                        <th scope="col" colspan="2">
                          <div class="icon-svg batting">
                            <img src="../assets/images/svg/batting.svg" alt="" />
                            <span>batting</span>
                          </div>
                        </th>
                      </tr>
                    </thead>
                    <tbody>
                      <tr>
                        <th scope="row">runs</th>
                        <td>1</td>
                      </tr>
                      <tr>
                        <th scope="row">four runs</th>
                        <td>1</td>
                      </tr>
                      <tr>
                        <th scope="row">six bonus</th>
                        <td>2</td>
                      </tr>
                      <tr>
                        <th scope="row">half-century bonus</th>
                        <td>8</td>
                      </tr>
                      <tr>
                        <th scope="row">century bonus</th>
                        <td>16</td>
                      </tr>
                      <tr>
                        <th scope="row">
                          Dismissal for duck (excluding bowlers)
                        </th>
                        <td>-3</td>
                      </tr>
                    </tbody>
                  </table>
                </div>
                <!-- Strike Rate -->
                <div class="table-responsive sx-table">
                  <table class="table table-hover table-striped">
                    <thead>
                      <tr>
                        <!-- <th scope="col">#</th> -->
                        <th scope="col" colspan="2">
                          <div class="icon-svg batting">
                            <img
                              src="../assets/images/svg/strike-rate.svg"
                              alt=""
                            />
                            <span>Strike Rate (Except Bowler)</span>
                          </div>
                        </th>
                      </tr>
                    </thead>
                    <tbody>
                      <tr>
                        <th scope="row">Less then 50 runs per 100 balls</th>
                        <td>-6</td>
                      </tr>
                      <tr>
                        <th scope="row">
                          Between 50 and 59.99 runs per 100 balls
                        </th>
                        <td>-4</td>
                      </tr>
                      <tr>
                        <th scope="row">
                          Between 60 and 70 runs per 100 balls
                        </th>
                        <td>-2</td>
                      </tr>
                    </tbody>
                  </table>
                </div>
                <!-- Bowling -->
                <div class="table-responsive sx-table">
                  <table class="table table-hover table-striped">
                    <thead>
                      <tr>
                        <!-- <th scope="col">#</th> -->
                        <th scope="col" colspan="2">
                          <div class="icon-svg batting">
                            <img src="../assets/images/svg/bowling.svg" alt="" />
                            <span>bowling</span>
                          </div>
                        </th>
                      </tr>
                    </thead>
                    <tbody>
                      <tr>
                        <th scope="row">Wicket (except run-out)</th>
                        <td>25</td>
                      </tr>
                      <tr>
                        <th scope="row">Maiden over Bonus</th>
                        <td>8</td>
                      </tr>
                      <tr>
                        <th scope="row">4-wicket haul Bonus</th>
                        <td>8</td>
                      </tr>
                      <tr>
                        <th scope="row">5-wicket haul Bonus</th>
                        <td>16</td>
                      </tr>
                    </tbody>
                  </table>
                </div>
                <!-- Economy Rate -->
                <div class="table-responsive sx-table">
                  <table class="table table-hover table-striped">
                    <thead>
                      <tr>
                        <!-- <th scope="col">#</th> -->
                        <th scope="col" colspan="2">
                          <div class="icon-svg batting">
                            <img
                              src="../assets/images/svg/strike-rate.svg"
                              alt=""
                            />
                            <span>Economy rate</span>
                          </div>
                        </th>
                      </tr>
                    </thead>
                    <tbody>
                      <tr>
                        <th scope="row">less than 4 runs per over</th>
                        <td>6</td>
                      </tr>
                      <tr>
                        <th scope="row">between 4 to 4.99 runs per over</th>
                        <td>4</td>
                      </tr>
                      <tr>
                        <th scope="row">Between 5 to 6 runs per over</th>
                        <td>2</td>
                      </tr>
                      <tr>
                        <th scope="row">Between 9 to 10 runs per over</th>
                        <td>-2</td>
                      </tr>
                      <tr>
                        <th scope="row">Between 10 to 11 runs per over</th>
                        <td>-4</td>
                      </tr>
                      <tr>
                        <th scope="row">above 11 runs per over</th>
                        <td>-6</td>
                      </tr>
                    </tbody>
                  </table>
                </div>
                <!-- Fielding -->
                <div class="table-responsive sx-table">
                  <table class="table table-hover table-striped">
                    <thead>
                      <tr>
                        <!-- <th scope="col">#</th> -->
                        <th scope="col" colspan="2">
                          <div class="icon-svg batting">
                            <img
                              src="../assets/images/svg/fielding.svg"
                              alt=""
                            />
                            <span>fielding</span>
                          </div>
                        </th>
                      </tr>
                    </thead>
                    <tbody>
                      <tr>
                        <th scope="row">catch</th>
                        <td>8</td>
                      </tr>
                      <tr>
                        <th scope="row">Stumping</th>
                        <td>12</td>
                      </tr>
                      <tr>
                        <th scope="row">Run-out(Direct)</th>
                        <td>12</td>
                      </tr>
                      <tr>
                        <th scope="row">Run-out(Thrower)</th>
                        <td>6</td>
                      </tr>
                      <tr>
                        <th scope="row">Run-out(Catcher)</th>
                        <td>6</td>
                      </tr>
                    </tbody>
                  </table>
                </div>
                <!-- Others -->
                <div class="table-responsive sx-table">
                  <table class="table table-hover table-striped">
                    <thead>
                      <tr>
                        <!-- <th scope="col">#</th> -->
                        <th scope="col" colspan="2">
                          <div class="icon-svg batting">
                            <img src="../assets/images/svg/others.svg" alt="" />
                            <span>others</span>
                          </div>
                        </th>
                      </tr>
                    </thead>
                    <tbody>
                      <tr>
                        <th scope="row">Making it to playing XI</th>
                        <td>4</td>
                      </tr>
                      <tr>
                        <th scope="row">Concussion Substitutes</th>
                        <td>4</td>
                      </tr>
                      <tr>
                        <th scope="row">Captain Bonus*</th>
                        <td>100% of Points scored by the Captain</td>
                      </tr>
                      <tr>
                        <th scope="row">Vice Captain Bonus**</th>
                        <td>50% of Points scored by the Vice-captain</td>
                      </tr>
                    </tbody>
                  </table>
                </div>
              </div>
              <div
                class="tab-pane fade"
                id="nav-odi"
                role="tabpanel"
                aria-labelledby="nav-odi-tab"
              >
                <!-- Batting Points System -->
                <div class="table-responsive sx-table">
                  <table class="table table-hover table-striped">
                    <thead>
                      <tr>
                        <!-- <th scope="col">#</th> -->
                        <th scope="col" colspan="2">
                          <div class="icon-svg batting">
                            <img src="../assets/images/svg/batting.svg" alt="" />
                            <span>batting</span>
                          </div>
                        </th>
                      </tr>
                    </thead>
                    <tbody>
                      <tr>
                        <th scope="row">runs</th>
                        <td>1</td>
                      </tr>
                      <tr>
                        <th scope="row">four runs</th>
                        <td>1</td>
                      </tr>
                      <tr>
                        <th scope="row">six bonus</th>
                        <td>2</td>
                      </tr>
                      <tr>
                        <th scope="row">half-century bonus</th>
                        <td>4</td>
                      </tr>
                      <tr>
                        <th scope="row">century bonus</th>
                        <td>8</td>
                      </tr>
                      <tr>
                        <th scope="row">
                          Dismissal for duck (excluding bowlers)
                        </th>
                        <td>-4</td>
                      </tr>
                    </tbody>
                  </table>
                </div>
                <!-- Strike Rate -->
                <div class="table-responsive sx-table">
                  <table class="table table-hover table-striped">
                    <thead>
                      <tr>
                        <!-- <th scope="col">#</th> -->
                        <th scope="col" colspan="2">
                          <div class="icon-svg batting">
                            <img
                              src="../assets/images/svg/strike-rate.svg"
                              alt=""
                            />
                            <span>Strike Rate (Except Bowler)</span>
                          </div>
                        </th>
                      </tr>
                    </thead>
                    <tbody>
                      <tr>
                        <th scope="row">Less then 40 runs per 100 balls</th>
                        <td>-6</td>
                      </tr>
                      <tr>
                        <th scope="row">
                          Between 40 and 49.99 runs per 100 balls
                        </th>
                        <td>-4</td>
                      </tr>
                      <tr>
                        <th scope="row">
                          Between 50 and 60 runs per 100 balls
                        </th>
                        <td>-2</td>
                      </tr>
                    </tbody>
                  </table>
                </div>
                <!-- Bowling -->
                <div class="table-responsive sx-table">
                  <table class="table table-hover table-striped">
                    <thead>
                      <tr>
                        <!-- <th scope="col">#</th> -->
                        <th scope="col" colspan="2">
                          <div class="icon-svg batting">
                            <img src="../assets/images/svg/bowling.svg" alt="" />
                            <span>bowling</span>
                          </div>
                        </th>
                      </tr>
                    </thead>
                    <tbody>
                      <tr>
                        <th scope="row">Wicket (except run-out)</th>
                        <td>25</td>
                      </tr>
                      <tr>
                        <th scope="row">Maiden over Bonus</th>
                        <td>4</td>
                      </tr>
                      <tr>
                        <th scope="row">4-wicket haul Bonus</th>
                        <td>4</td>
                      </tr>
                      <tr>
                        <th scope="row">5-wicket haul Bonus</th>
                        <td>8</td>
                      </tr>
                    </tbody>
                  </table>
                </div>
                <!-- Economy Rate -->
                <div class="table-responsive sx-table">
                  <table class="table table-hover table-striped">
                    <thead>
                      <tr>
                        <!-- <th scope="col">#</th> -->
                        <th scope="col" colspan="2">
                          <div class="icon-svg batting">
                            <img
                              src="../assets/images/svg/strike-rate.svg"
                              alt=""
                            />
                            <span>economy rate</span>
                          </div>
                        </th>
                      </tr>
                    </thead>
                    <tbody>
                      <tr>
                        <th scope="row">Less than 2.5 runs per over</th>
                        <td>6</td>
                      </tr>
                      <tr>
                        <th scope="row">Between 2.5 to 3.49 runs per over</th>
                        <td>4</td>
                      </tr>
                      <tr>
                        <th scope="row">Between 3.5 to 4.5 runs per over</th>
                        <td>2</td>
                      </tr>
                      <tr>
                        <th scope="row">Between 7 to 8 runs per over</th>
                        <td>-2</td>
                      </tr>
                      <tr>
                        <th scope="row">Between 8.1 to 9 runs per over</th>
                        <td>-4</td>
                      </tr>
                      <tr>
                        <th scope="row">above 9 runs per over</th>
                        <td>-6</td>
                      </tr>
                    </tbody>
                  </table>
                </div>
                <!-- Fielding -->
                <div class="table-responsive sx-table">
                  <table class="table table-hover table-striped">
                    <thead>
                      <tr>
                        <!-- <th scope="col">#</th> -->
                        <th scope="col" colspan="2">
                          <div class="icon-svg batting">
                            <img
                              src="../assets/images/svg/fielding.svg"
                              alt=""
                            />
                            <span>fielding</span>
                          </div>
                        </th>
                      </tr>
                    </thead>
                    <tbody>
                      <tr>
                        <th scope="row">catch</th>
                        <td>8</td>
                      </tr>
                      <tr>
                        <th scope="row">Stumping</th>
                        <td>12</td>
                      </tr>
                      <tr>
                        <th scope="row">Run-out(Direct)</th>
                        <td>12</td>
                      </tr>
                      <tr>
                        <th scope="row">Run-out(Thrower)</th>
                        <td>6</td>
                      </tr>
                      <tr>
                        <th scope="row">Run-out(Catcher)</th>
                        <td>6</td>
                      </tr>
                    </tbody>
                  </table>
                </div>
                <!-- Others -->
                <div class="table-responsive sx-table">
                  <table class="table table-hover table-striped">
                    <thead>
                      <tr>
                        <!-- <th scope="col">#</th> -->
                        <th scope="col" colspan="2">
                          <div class="icon-svg batting">
                            <img src="../assets/images/svg/others.svg" alt="" />
                            <span>others</span>
                          </div>
                        </th>
                      </tr>
                    </thead>
                    <tbody>
                      <tr>
                        <th scope="row">Making it to playing XI</th>
                        <td>4</td>
                      </tr>
                      <tr>
                        <th scope="row">Concussion Substitutes</th>
                        <td>4</td>
                      </tr>
                      <tr>
                        <th scope="row">Captain Bonus*</th>
                        <td>100% of Points scored by the Captain</td>
                      </tr>
                      <tr>
                        <th scope="row">Vice Captain Bonus**</th>
                        <td>50% of Points scored by the Vice-captain</td>
                      </tr>
                    </tbody>
                  </table>
                </div>
              </div>
              <div
                class="tab-pane fade"
                id="nav-test"
                role="tabpanel"
                aria-labelledby="nav-test-tab"
              >
                <!-- Batting Points System -->
                <div class="table-responsive sx-table">
                  <table class="table table-hover table-striped">
                    <thead>
                      <tr>
                        <!-- <th scope="col">#</th> -->
                        <th scope="col" colspan="2">
                          <div class="icon-svg batting">
                            <img src="../assets/images/svg/batting.svg" alt="" />
                            <span>batting</span>
                          </div>
                        </th>
                      </tr>
                    </thead>
                    <tbody>
                      <tr>
                        <th scope="row">runs</th>
                        <td>1</td>
                      </tr>
                      <tr>
                        <th scope="row">four runs</th>
                        <td>1</td>
                      </tr>
                      <tr>
                        <th scope="row">six bonus</th>
                        <td>2</td>
                      </tr>
                      <tr>
                        <th scope="row">half-century bonus</th>
                        <td>4</td>
                      </tr>
                      <tr>
                        <th scope="row">century bonus</th>
                        <td>8</td>
                      </tr>
                      <tr>
                        <th scope="row">
                          Dismissal for duck (excluding bowlers)
                        </th>
                        <td>-5</td>
                      </tr>
                    </tbody>
                  </table>
                </div>
                <!-- Strike Rate -->
                <div class="table-responsive sx-table">
                  <table class="table table-hover table-striped">
                    <thead>
                      <tr>
                        <!-- <th scope="col">#</th> -->
                        <th scope="col" colspan="2">
                          <div class="icon-svg batting">
                            <img
                              src="../assets/images/svg/strike-rate.svg"
                              alt=""
                            />
                            <span>Strike Rate (Except Bowler)</span>
                          </div>
                        </th>
                      </tr>
                    </thead>
                    <tbody>
                      <tr>
                        <th scope="row">Less then 50 runs per 100 balls</th>
                        <td>NA</td>
                      </tr>
                      <tr>
                        <th scope="row">
                          Between 50 and 59.99 runs per 100 balls
                        </th>
                        <td>NA</td>
                      </tr>
                      <tr>
                        <th scope="row">
                          Between 60 and 74.99 runs per 100 balls
                        </th>
                        <td>NA</td>
                      </tr>
                    </tbody>
                  </table>
                </div>
                <!-- Bowling -->
                <div class="table-responsive sx-table">
                  <table class="table table-hover table-striped">
                    <thead>
                      <tr>
                        <!-- <th scope="col">#</th> -->
                        <th scope="col" colspan="2">
                          <div class="icon-svg batting">
                            <img src="../assets/images/svg/bowling.svg" alt="" />
                            <span>bowling</span>
                          </div>
                        </th>
                      </tr>
                    </thead>
                    <tbody>
                      <tr>
                        <th scope="row">Wicket (except run-out)</th>
                        <td>16</td>
                      </tr>
                      <tr>
                        <th scope="row">Maiden over Bonus</th>
                        <td>NA</td>
                      </tr>
                      <tr>
                        <th scope="row">4-wicket haul Bonus</th>
                        <td>4</td>
                      </tr>
                      <tr>
                        <th scope="row">5-wicket haul Bonus</th>
                        <td>8</td>
                      </tr>
                    </tbody>
                  </table>
                </div>
                <!-- Economy Rate -->
                <div class="table-responsive sx-table">
                  <table class="table table-hover table-striped">
                    <thead>
                      <tr>
                        <!-- <th scope="col">#</th> -->
                        <th scope="col" colspan="2">
                          <div class="icon-svg batting">
                            <img
                              src="../assets/images/svg/strike-rate.svg"
                              alt=""
                            />
                            <span>Economy Rate</span>
                          </div>
                        </th>
                      </tr>
                    </thead>
                    <tbody>
                      <tr>
                        <th scope="row">Left than 4</th>
                        <td>NA</td>
                      </tr>
                      <tr>
                        <th scope="row">4 to 4.99</th>
                        <td>NA</td>
                      </tr>
                      <tr>
                        <th scope="row">Between 5 to 6</th>
                        <td>NA</td>
                      </tr>
                      <tr>
                        <th scope="row">Between 9 to 10</th>
                        <td>NA2</td>
                      </tr>
                      <tr>
                        <th scope="row">Between 10 to 11</th>
                        <td>NA</td>
                      </tr>
                      <tr>
                        <th scope="row">above 11</th>
                        <td>NA</td>
                      </tr>
                    </tbody>
                  </table>
                </div>
                <!-- Fielding -->
                <div class="table-responsive sx-table">
                  <table class="table table-hover table-striped">
                    <thead>
                      <tr>
                        <!-- <th scope="col">#</th> -->
                        <th scope="col" colspan="2">
                          <div class="icon-svg batting">
                            <img
                              src="../assets/images/svg/fielding.svg"
                              alt=""
                            />
                            <span>fielding</span>
                          </div>
                        </th>
                      </tr>
                    </thead>
                    <tbody>
                      <tr>
                        <th scope="row">catch</th>
                        <td>8</td>
                      </tr>
                      <tr>
                        <th scope="row">Stumping</th>
                        <td>12</td>
                      </tr>
                      <tr>
                        <th scope="row">Run-out(Direct)</th>
                        <td>12</td>
                      </tr>
                      <tr>
                        <th scope="row">Run-out(Thrower)</th>
                        <td>6</td>
                      </tr>
                      <tr>
                        <th scope="row">Run-out(Catcher)</th>
                        <td>6</td>
                      </tr>
                    </tbody>
                  </table>
                </div>
                <!-- Others -->
                <div class="table-responsive sx-table">
                  <table class="table table-hover table-striped">
                    <thead>
                      <tr>
                        <!-- <th scope="col">#</th> -->
                        <th scope="col" colspan="2">
                          <div class="icon-svg batting">
                            <img src="../assets/images/svg/others.svg" alt="" />
                            <span>others</span>
                          </div>
                        </th>
                      </tr>
                    </thead>
                    <tbody>
                      <tr>
                        <th scope="row">Making it to playing XI</th>
                        <td>4</td>
                      </tr>
                      <tr>
                        <th scope="row">Concussion Substitutes</th>
                        <td>4</td>
                      </tr>
                      <tr>
                        <th scope="row">Captain Bonus*</th>
                        <td>100% of Points scored by the Captain</td>
                      </tr>
                      <tr>
                        <th scope="row">Vice Captain Bonus**</th>
                        <td>50% of Points scored by the Vice-captain</td>
                      </tr>
                    </tbody>
                  </table>
                </div>
              </div>
            </div>
          </div>
          <!-- ** Note **  -->
          <div class="sx-notes">
            <p>Please note:</p>
            <ul>
              <li>
                1 point is equivalent to 1 credit for calculating Team Portfolio
                Value
              </li>
              <li>
                *100% of the points scored by the cricketer you choose to be
                your Team Portfolio Captain will be given as Captain Bonus
                Points
              </li>
              <li>
                **50% of the points scored by the cricketer you choose to be
                your Team Portfolio Vice-captain will be given as Vice-captain
                Bonus Points
              </li>
              <li>
                Starting points are assigned to any player on the basis of
                announcement of his/her inclusion in the team. However, in case
                the player is unable to start the match after being included in
                the team sheet, he/she will not score any points. Points shall
                however, be applicable (including starting points) to any player
                who plays as a replacement of such player to whom starting
                points were initially assigned.
              </li>
              <li>
                Substitutes on the field will not be awarded points for any
                contribution they make. However, 'Concussion Substitutes' and
                'Covid-19 replacements' will be awarded four (4) points for
                making an appearance in a match and will be awarded points for
                any contribution they make as per the Fantasy Points System.
              </li>
              <li>
                Super Over, if any, will be considered for Points to be
                assigned/applied to a player.
              </li>
              <li>
                In case of run-outs involving 3 or more players from the
                fielding side, points will be awarded only to the last 2 players
                involved in the run-out.
              </li>
              <li>
                Any player scoring a century will only get points for the
                century (no points will be awarded for half-century separately).
                Similarly, any score over and above century will be eligible for
                bonus points only for the century.
              </li>
            </ul>
          </div>
        </div>
      </div>
    </div>
  </Layout>
</template>

<script>
export default {
  metaInfo: {
    title: "Points System",
  },
};
</script>

<style>
</style>