<template>
  <div class="container-fluid">


    <nav class="navbar navbar-expand-lg navbar-dark bg-white">

      <a class="navbar-brand" href="#">
        <img src="../assets/Logo.svg" alt="">
      </a>

      <ul class="nav justify-content-center">
        <li class="nav-item">
          <a class="nav-link" href="#">Home</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#">Features</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#">Pricing</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#">About</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#">FAQ</a>
        </li>
      </ul>



      <ul class="nav  ms-auto">
        <li class="nav-item fw-700px fs-16px">
          <a class="nav-link " href="#">SignUp</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" id="button" href="#">SignIn</a>
        </li>
      </ul>

    </nav>
    <hr />

    <div class="row">
      <div class="col-lg-6">
        <img class="mb-2 img-fluid" src="../assets/machine.svg" alt="">
        <p class="main">CryptoGenie is a yantra which predicts the directional trend of cryptocurrency pairs.</p>
        <p class="sub">It uses advanced financial machine learning concepts and techniques to create models that
          generate
          predictive trends for crypto assets. </p>
        <button class="pre-button mb-3" type="button"><a herf="" class="go-button">Go to predictions</a></button>
        <div class="row">
          <div class="col-md-4 col-5">
            <p class="fw-700 fs-16 black mb-1">30 minutes</p>
            <p class=" fs-16 fs-400">Trend prediction window </p>
          </div>
          <div class="col-md-1 col-sm-1 col-2">
            <div class="line-in-middle"></div>
            <div class="vr"></div>
          </div>

          <div class="col-md-4 col-5 ">
            <p class="fw-700 fs-16 black mb-1">High prediction metrics</p>
            <p class=" fs-16 fs-400">A new level of AI</p>
          </div>
        </div>
      </div>
      <div class="col-lg-6 mt-5">
        <img src="../assets/Illustartion.svg" class="img-fluid crypto-img" alt="" />
      </div>
    </div>
    <div class="arrow">
      <img src="../assets/Arrows.svg" alt="" class="arrow-img">

    </div>
    <h2 class="fs-32 fw-700  pt-5 mb-5">Features</h2>
    <div class="row">
      <div class="col-lg-6">
        <img src="../assets/Group5.svg" alt="">

        <div class="content pt-5 mb-5">
          <h3 class="fs-24 fw-700">Automated Trend Predictions</h3>
          <p class="main-content fs-16 fw-400">Standard machine learning techniques are
            overly simplistic when applied to ﬁnancial domains. We apply sophisticated
            mathematical and statistical techniques to avoid overﬁtting and false positives
            inherent in most ﬁnancial prediction applications. Our empirical approach focuses
            on real world analysis, which are in addition to purely theoretical methods.</p>
        </div>
        <img src="../assets/Group1.svg" alt="">
        <div class="content pt-5 mb-5">
          <h3 class="fs-24 fw-700">Statistical & Empirical Approach</h3>
          <p class="main-content fs-16 fw-400">We provide 24 x 7 trend predictions which are valid for 30 minute window.
            Traders can use this trend information to enter trades with confidence.
            Aside from the current prediction
            window, one can also view the past trend predictions and its metrics.</p>

        </div>
        <img src="../assets/Group3.svg" alt="">
        <div class="content pt-5 mb-5">
          <h3 class="fs-24 fw-700 ">eXplainable AI (XAI)</h3>
          <p class="main-content fs-16 fw-400">Most AI/ML predictions are black boxes. One cannot interpret or
            understand
            the predictions made by the models. Our models have been built using interpretable and inclusive features
            that
            produce more explainable models, while maintaining a high level of prediction performance. We achieve this
            by
            extracting features that explain the underlying model classiﬁcation across our asset universe.</p>

        </div>

      </div>

      <div class="col-lg-6">
        <img src="../assets/Group6.svg" alt="">
        <div class="content pt-5 mb-5">
          <h3 class="fs-24 fw-700">Advanced Financial Machine Learning</h3>
          <p class="main-content fs-16 fw-400">We use cutting edge financial machine learning techniques to overcome
            real-world investment problems. Our fully proven approaches to data preparation, use of primary and
            secondary
            models, feature importance and extraction, advanced backtesting statistics and rigorous out of sample
            veriﬁcation before graduating and commissioning our models ensures superior performance.</p>

        </div>
        <img src="../assets/Group2.svg" alt="">
        <div class="content pt-5 mb-5 ">
          <h3 class="fs-24 fw-700">Transparent Historical Charts</h3>
          <p class="main-content fs-16 fw-400">We provide historical charts of prediction metrics. For e.g. accuracy,
            f1-score, precision, recall etc among others. These historical metrics can then be used to evaluate the
            efficacy of the prediction algorithm over time.</p>

        </div>
        <img src="../assets/Group4.png" alt="">
        <div class="content  pt-5 mb-5">
          <h3 class="fs-24 fw-700">Applied AI</h3>
          <p class="main-content fs-16 fw-400">We have designed, developed and deployed a state of the art end-to-end
            architecture for delivering high quality predictions seamlessly and continuously. Our infrastructure takes
            care of data ingest, validation, transformation, feature extraction and prediction serving in an automated
            fashion. Our cloud based infrastructure is designed to be secure, scalable and resilient. We regularly
            monitor
            our models in production for ‘concept drift’, so that we can deploy newer and better models as soon as we
            hit
            performance decay thresholds and decommission the previous models.</p>
        </div>

      </div>
    </div>

    <div class="row">
      <img src="../assets/Howitworks.svg" alt="">

    </div>
    <div class="arrow">
      <img src="../assets/Arrows2.svg" alt="" class="arrow-img">

    </div>

    <div class="pricing p-0">
      <p class="text-center fs-32 fw-700 p-3">Pricing</p>
      <p class="text-center fs-16 fw-400">It uses advanced financial machine learning concepts and techniques <br />
        to create models that generate predictive
        trends for crypto assets.</p>

      <div class=" nav-buttons ">
        <ul id="pills-tab" role="tablist" class="nav nav-pills mb-3 bg-light p-2">
          <li role="presentation" class="nav-item">
            <button id="pills-monthly-tab" data-bs-toggle="pill" data-bs-target="#pills-monthly" type="button"
              role="tab" aria-controls="pills-monthly" aria-selected="false" class="nav-link">Monthly</button>
          </li>
          <li role="presentation" class="nav-item">
            <button id="pills-yearly-tab" data-bs-toggle="pill" data-bs-target="#pills-yearly" type="button" role="tab"
              aria-controls="pills-yearly" aria-selected="true" class="nav-link active">Annual</button>
          </li>
        </ul>
      </div>


      <div class="pricing-card pt-3 ">
        <div class="row">
          <div class="col-sm-3">
            <div class="card">
              <div class="card-body">
                <div class="border_line"></div>
                <p class="text-center fs-28 fw-700">Free</p>
                <p class="fs-14 fw-400">Lorem ipsum dolor sit amet,</p>
                <h1><img src="../assets/tag1.svg" class="parallel">
                </h1>
                <div class="d-flex gap-2">
                  <img src="../assets/Vector.svg" alt="" width="20px" height="20px">
                  <p class="fs-16 fw-400">BTCUSDT Charts & current predictions</p>
                </div>
                <div class="d-flex gap-2">
                  <img src="../assets/Vector.svg" alt="" width="20px" height="20px">
                  <p class="fs-16 fw-400">BTCUSDT Charts & current predictions</p>
                </div>
                <div class="d-grid gap-2 ">
                  <button class="btn btn-primary fs-16 fw-700" type="submit">Go to predictions</button>

                </div>
              </div>
            </div>
          </div>
          <div class="col-sm-3">
            <div class="card">
              <div class="card-body">
                <div class="border_line"></div>
                <p class="text-center fs-28 fw-700">$10<span class="fs-16 fw-400">/per month</span></p>
                <p class="fs-14 fw-400">Yearly : $108 (10% discount)</p>
                <h1><img src="../assets/tag2.svg" class="parallel">
                </h1>
                <div class="d-flex gap-3">
                  <img src="../assets/Vector.svg" alt="" width="20px" height="20px">
                  <p class="fs-16 fw-400">10 coins current predictions</p>
                </div>
                <div class="d-flex gap-3">
                  <img src="../assets/Vector.svg" alt="" width="20px" height="20px">
                  <p class="fs-16 fw-400">More detailed charts</p>
                </div>
                <div class="d-grid gap-2 ">
                  <button class="btn btn-primary fs-16 fw-700" type="button">Change Plane</button>

                </div>
              </div>
            </div>
          </div>
          <div class="col-sm-3">
            <div class="card">
              <div class="card-body">
                <div class="border_line"></div>
                <p class="text-center fs-28 fw-700">$60<span class="fs-16 fw-400">/per month</span></p>
                <p class="fs-14 fw-400">Lorem ipsum dolor sit amet,</p>
                <h1><img src="../assets/tag3.svg" class="parallel">
                </h1>
                <div class="d-flex gap-2">
                  <img src="../assets/Vector.svg" alt="" width="20px" height="20px">
                  <p class="fs-16 fw-400">2-5 user teams</p>
                </div>
                <div class="d-flex gap-2">
                  <img src="../assets/Vector.svg" alt="" width="20px" height="20px">
                  <p class="fs-16 fw-400">Limited API use</p>
                </div>
                <div class="d-flex gap-2">
                  <img src="../assets/Vector.svg" alt="" width="20px" height="20px">
                  <p class="fs-16 fw-400">Trading bots</p>
                </div>
                <div class="d-grid gap-2 ">
                  <button class="btn btn-primary fs-16 fw-700" type="button">Change Plane</button>

                </div>
              </div>
            </div>
          </div>
          <div class="col-sm-3">
            <div class="card">
              <div class="card-body">
                <div class="border_line"></div>
                <p class="text-center fs-28 fw-700">Contact Us</p>
                <p class="fs-14 fw-400">Lorem ipsum dolor sit amet,</p>
                <h1><img src="../assets/tag4.svg" class="parallel mt-2">
                </h1>
                <div class="d-flex gap-3">
                  <img src="../assets/Vector.svg" alt="" width="20px" height="20px">
                  <p class="fs-16 fw-400">Unlimited API use</p>
                </div>
                <div class="d-flex gap-3">
                  <img src="../assets/Vector.svg" alt="" width="20px" height="20px">
                  <p class="fs-16 fw-400">Custom trading bots</p>
                </div>
                <div class="d-grid gap-2">
                  <button class="btn btn-primary fs-16 fw-700" type="button">Contact Us</button>

                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
      <div class="row mt-5 mb-5">
        <img src="../assets/black-panner.svg" alt="">
      </div>
      <div class="row">
        <div class="col-6">
          <img src="../assets/Group48265.svg" alt="">

        </div>
        <div class="col-6">
          <p class="fs-32 fw-700">Get trend predictions for crypto currencies at 30 min periods.</p>
          <p class="fs-16 fw-400">This will help you discern the trends per each crypto asset.</p>
          <button class="pre-button mb-3" type="button"><a herf="" class="go-button">Go to predictions</a></button>


        </div>
      </div>

      <div class="row">
        <div class="col-6">
          <img src="../assets/Logo2.svg" alt="">

        </div>
        <div class="col-6">
          <ul class="nav  justify-content-end">
            <li class="nav-item fw-700px fs-16px">
              <a class="nav-link " href="#">Features</a>
            </li>
            <li class="nav-item fw-700px fs-16px">
              <a class="nav-link " href="#">Pricing</a>
            </li>
            <li class="nav-item">
              <a class="nav-link " href="#">Predictions</a>
            </li>
            <li class="nav-item">
              <a class="nav-link " href="#">Support</a>
            </li>
          </ul>
        </div>
      </div>
      <hr />
      <div class="row">
        <div class="col-6">
          <img src="../assets/@Yantraka.svg" alt="">

        </div>
        <div class="col-6">
          <ul class="nav  justify-content-end">
            <li class="nav-item fw-700px fs-16px">
              <a class="nav-link disabled" href="#">Terms of use</a>
            </li>
            <li class="nav-item fw-700px fs-16px">
              <a class="nav-link disabled" href="#">Privacy Policy</a>
            </li>

          </ul>
        </div>
      </div>





    </div>
  </div>













</template>

<script>
export default {
  name: 'Home-Page'

}
</script>

<style scoped>
.container-fluid{
  width:960px;
}
a {
  color: black
}

.border_line {
  border: 4px solid #000;
}

#button {

  font-weight: 700;
  font-size: 16px;
  color: #000000;
  border: 1px solid #E3E7ED;
  padding: 7px
}

.main {
  font-family: 'Satoshi';
  font-style: normal;
  font-weight: 700;
  font-size: 47.52px;
  line-height: 55px;
  color: #000000;
}

.sub {

  font-family: 'Satoshi';
  font-style: normal;
  font-weight: 400;
  font-size: 15.84px;
  line-height: 24px;
  display: flex;
  align-items: center;
  color: #000000;
}

.pre-button {

  width: 176.52px;
  height: 55.68px;
  background: #6237DE;
  border: none;
}

.go-button {

  font-weight: 700;
  font-size: 16px;
  line-height: 24px;
  color: #FFFFFF;
  flex: none;
  order: 0;
  flex-grow: 0;
  text-decoration: none;
}

.crypto-img {
  width: 100% !important;
}

.fs-16 {
  font-size: 16px;
}

.fw-700 {
  font-weight: 700;
}

.fs-400 {
  font-weight: 400;
}

.arrow-img {
  width: 100% !important;
}

.fs-32 {
  font-size: 32px;
}

.fs-28 {
  font-size: 28px;
}


.fs-24 {
  font-size: 24px;
}

.img-work {
  width: 100% !important;
}

.content {
  padding: 10px
}

.fs-14 {
  font-size: 14px;
}

.card-body {
  box-sizing: border-box;
  border-radius: 0px;
  background: #FFFFFF;
  border: 1px solid #E3E7ED;

}

.card-body:hover {
  border: 1px solid #6b38fd;
}

.btn {
  background-color: #6237DE;
  color: #FFFFFF;
  border-radius: 0px;
  height: 56px;

}

.btn:hover {
  background-color: #6237DE;
  color: #FFFFFF;
}

h1 {
  display: flex;
  flex-direction: row;
}

h1:before,
h1:after {
  content: "";
  flex: 1 1;
  border-bottom: 1px solid #A7AFBA;
  margin: auto;
}



.pricing {
  background: #F0F0F0;
}

.vr {
  width: 0.99px;
  height: 53.46px;
  background: #000;
}

.nav-buttons {
  /* border: 1px solid #FFFFFF; */
  /* width:180px;
  height: 45px; */
  display: flex;
  justify-content: center;
  align-items: center;
}

.pills-yearly-tab {
  border-radius: 0px;

}
</style>
