<template>
  <Layout>
    <section class="sx-component sx-static-info">
      <div class="sx-head">
        <h1 class="sx-head--page-title">
          <span>team (portfolio) requirements</span>
        </h1>
      </div>
      <div class="container">
        <div class="sx-body">
          <div class="table-responsive sx-table">
            <table class="table table-hover table-striped">
              <thead>
                <tr>
                  <th scope="col">Player</th>
                  <th scope="col">Minimum</th>
                  <th scope="col">Maximum</th>
                </tr>
              </thead>
              <tbody>
                <tr>
                  <td scope="row">Wicketkeeper</td>
                  <td>1</td>
                  <td>2</td>
                </tr>
                <tr>
                  <td scope="row">Batsmen</td>
                  <td>3</td>
                  <td>5</td>
                </tr>
                <tr>
                  <td scope="row">All-rounder</td>
                  <td>1</td>
                  <td>3</td>
                </tr>
                <tr>
                  <td scope="row">Bowler</td>
                  <td>3</td>
                  <td>5</td>
                </tr>
                <tr>
                  <td scope="row">Total Player</td>
                  <td>11</td>
                  <td>11</td>
                </tr>
                <tr>
                  <td scope="row">Player from each team</td>
                  <td>4</td>
                  <td>7</td>
                </tr>
                <tr>
                  <td scope="row">Captain &amp; Vice Captain</td>
                  <td>1 each</td>
                  <td>1 each</td>
                </tr>
                <tr>
                  <td scope="row" rowspan="3">Player Units per player</td>
                  <td colspan="2">
                    <div class="table-responsive">
                      <table class="table">
                        <thead>
                          <tr>
                            <th scope="col" colspan="2">team</th>
                          </tr>
                        </thead>
                        <tbody>
                          <tr>
                            <td>1</td>
                            <td>1</td>
                          </tr>
                        </tbody>
                      </table>
                    </div>
                    <div class="table-responsive">
                      <table class="table">
                        <thead>
                          <tr>
                            <th scope="col" colspan="2">team portfolio</th>
                          </tr>
                        </thead>
                        <tbody>
                          <tr>
                            <td>1</td>
                            <td>3</td>
                          </tr>
                        </tbody>
                      </table>
                    </div>
                    <div class="table-responsive">
                      <table class="table">
                        <thead>
                          <tr>
                            <th scope="col" colspan="2">player xchange</th>
                          </tr>
                        </thead>
                        <tbody>
                          <tr>
                            <td>1</td>
                            <td>3</td>
                          </tr>
                        </tbody>
                      </table>
                    </div>
                  </td>
                </tr>
              </tbody>
            </table>
          </div>
          <a href="index.html" class="sx-btn--home">
            <button type="button" class="sx-btn">back</button>
          </a>
        </div>
      </div>
    </section>
  </Layout>
</template>

<script>
export default {
  metaInfo: {
    title: "Portfolio Requirements",
  },
};
</script>

<style>
</style>