<template>
    <div class="row image">
        <div class="col-6 p-0">

            <img src="../assets/Banner.svg" alt="" />

        </div>

        <div class="col-6">
            <h1 class="heading fs-32px ">Sign UP</h1>

            <div class="row mt-5 mb-5">
                <div class="col-6">
                    <div class="social">
                        <img src="../assets/Google.svg" alt="">
                        <div class="font fs-16 fw-700">Sign Up With Google</div>
                    </div>
                </div>
                <div class="col-6">
                    <div class="social">
                        <img src="../assets/path18.svg" alt="">
                        <div class="font fs-16 fw-700">Sign Up With LinkedIn</div>
                    </div>
                </div>
            </div>

            <div class="Or mt-5 mb-5">
                <p class="or-color">OR</p>
            </div>

            <div class="row">
                <div class="col-6">
                    <div class="form-floating mb-3">
                        <input type="text" class="form-control" id="floatingInput" placeholder="name@example.com">
                        <label for="floatingInput">First Name</label>
                    </div>

                </div>
                <div class="col-6">
                    <div class="form-floating mb-3">
                        <input type="text" class="form-control" id="floatingInput" placeholder="name@example.com">
                        <label for="floatingInput">Last Name</label>
                    </div>

                </div>
            </div>

            <div class="form-floating mb-3">
                <input type="text" class="form-control" id="floatingInput" placeholder="name@example.com">
                <label for="floatingInput">Email</label>
            </div>

            <div class="form-floating mb-3">
                <input type="text" class="form-control" id="floatingInput" placeholder="name@example.com">
                <label for="floatingInput">Password</label>
            </div>
            <div class="form-floating mb-3">
                <input type="text" class="form-control" id="floatingInput" placeholder="name@example.com">
                <label for="floatingInput">Confirm Password</label>
            </div>

            <div class="form-check">
                <input class="form-check-input" type="checkbox" value="" id="flexCheckDefault">
                <label class="form-check-label" for="flexCheckDefault">
                    By accepting your agree to Yantraka.AI's
                    <a href="#">Terms of Use</a> & <a href="#">Privacy Policy</a>
                </label>

            </div>

            <div class="d-grid gap-2">
                <button class="btn mt-5" type="submit"
                    style="background-color: #6B38FD; font-size: 16px;color:#fff;border-radius:0px;">Sign Up</button>

            </div>

            <div class="row mt-5">
                <div class="col-12">

                    <div class="text-center fs-14px fw-400px">Already a user? &nbsp; <a href="#">SignIn</a></div>
                </div>
            </div>
        </div>
    </div>


</template>
<script>
export default {
    name: 'signup-Page',
}
</script>
<style scopped>
.image {
    height: 100vh;
}

.social {
    display: flex;
    padding: 16px 32px 16px 24px;
    border: 1px solid #E3E7ED;
    flex-direction: row;
    justify-content: center;
    align-items: center;
    padding: 16px 32px 16px 24px;
    gap: 8px;

}

.terms {
    text-decoration: none;
    color: #000;

}


.form-control:hover {
    border: 1px solid #6b38fd;

}

input:focus {
    outline: none;
}

.btn {
    width: 480px;
    height: 56px;
    margin: 0 auto;

}

p {
    display: flex;
    flex-direction: row;

}

.or-color {
    color: #A7AFBA;
    font-weight: 400;
    font-size: 14px;
}

p:before,
p:after {
    content: "";
    flex: 1 1;
    border-bottom: 1px solid #E3E7ED;
    margin: auto;
    width: 480px;
    color: #a7afba !important;
    ;
}

a:link,
a:visited {
    text-decoration: none;
    color: #6b38fd;
}
</style>