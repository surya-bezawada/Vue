<template>
    <nav class="navbar navbar-expand-md fixed-top ">
        <div class="container-fluid p-0">
            <a class="navbar-brand" href="#">
                <img src="../assets/Logo3.svg" alt="">
            </a>
            <ul class="navbar-nav ms-auto">
                <li class="nav-item">
                    <a class="nav-link fs-16 fw-400 text-white" href="#">CryptoGenie</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link fs-16 fw-400 text-white" href="#">Contact Us</a>
                </li>
            </ul>
        </div>
    </nav>
    <div class="container-fluid p-0">
        <div class="frame">
            <img src="../assets/Frame48503.svg" alt="" width="100%" class="img-fluid ">
            <div class="content">
                <div class="row">
                    <div class="col-lg-6">
                        <p>Yantraka.ai designs and develops products in Fintech, Energy and Retail domains using
                            advanced
                            Artificial Intelligence & Machine Learning</p>
                    </div>
                </div>
                <button class="btn ">Go to predictions</button>
            </div>
        </div>



    </div>





    <div class="container">
        <div class="row">
            <div class="col-12">
                <img src="../assets/Title.svg" alt="" class="pt-5 ">
                <img src="../assets/Cover.svg" alt="" class="img-fluid" width="100%">
            </div>
        </div>
        <div class="main pt-5">
            <a class="navbar-brand " href="#">
                <img src="../assets/Logo.svg" alt="" class="pt-3 pb-3">
            </a>
            <div class="row">
                <div class="col-6">
                    <p class="main-content">An Automated Predictive Trading Platform for Cryptocurrencies, Using
                        advanced financial machine
                        learning concepts and techniques at the cutting edge of technology from state of the art
                        research
                        papers
                    </p>
                    <button class="btn-prime">Go to Cryptogenie</button>

                </div>
                <div class="col-6">
                    <p class="main-content">CryptoGenie can be licensed to capital management firms which can leverage
                        the technolgoy to superior
                        returns to their fund investors. It is an automated system end to end, right from data
                        ingestion, to
                        model training, validation and trading.</p>
                </div>
            </div>
        </div>
        <hr />
        <div class="row pt-3">
            <div class="col-6">
                <img src="../assets/patternt.svg" alt="">
                <p class="pt-3">An "Industrial IoT solution for Energy generation prediction for Solar and Wind" using
                    advanced AI/ML. This is achieved by building an Applied AI framework which when deployed enables
                    accurate energy generation prediction.</p>
                <button class="btn-prime">Coming Soon</button>
            </div>
            <div class="col-6">
                <div class="trade">
                    <img src="../assets/Bg.svg" alt="">
                    <div class="trade-main">
                        <p class="fs-27 fw-900">Trade con???dently using CryptoGenie trend predictions. Would you like to know more?</p>
                         <button class="btn-prime">Go to Cryptogenie</button>
                    </div>

                </div>
            </div>
        </div>

        <div class="row">
            <div class="col-6">
                <img src="../assets/Logo4.svg" alt="">

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

</template>
<script>
export default {
    name: 'main-page'

}
</script>
<style>
.fs-16 {
    font-size: 16px;
}

.fs-400 {
    font-weight: 400px;
}



.frame {
    position: relative;
}

.content {
    position: absolute;
    color: #FEFEFE;
    font-size: 38px;
    font-weight: 900px;
    display: flex;
    justify-content: flex-start;
    flex-direction: column;
    align-items: flex-start;
    top: 20%;
    left: 10%;

}

.container {
    width: 860px !important;

}

.btn {
    height: 56px;
    width: 192px;
    border-radius: 0 !important;
    background-color: #FEFEFE !important;
    color: #000;
    border: 1px solid #FEFEFE !important;

}

.btn:hover {
    background-color: #6237DE !important;
    color: #FEFEFE;
}

.btn-prime {
    height: 56px;
    width: 192px;
    border-radius: 0px !important;
    background-color: #6237DE !important;
    color: #FEFEFE;
    border: 1px solid #FEFEFE !important;

}
.navbar{
    background-color: #6B38FD;
}
.fs-27{
    font-size: 27px;
    font-weight: 700;
}

.trade{
    position: relative;

}
.trade-main{
  position: absolute;
    color: #FEFEFE;
    display: flex;
    justify-content: flex-start;
    flex-direction: column;
    align-items: flex-start;
    top: 24%;
    left: 10%;
}
</style>