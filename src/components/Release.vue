<template>
    <section class="release">
        <div class="container-fluid release__container-fluid">

            <div class="release">
                <div class="head">
                    <h3 class="release-title">
                        New Release
                    </h3>
                </div>

                <div class="body">
                    <div class="row">
                        <div class="col-lg-4 col-md-4 col-12">
                            <div class="release-card">
                            </div>
                            <div class="release-card-overlay">
                                <h5 class="release-title">Black Adam</h5>
                                <h6 class="release-subtitle">
                                    Episode 1018
                                </h6>
                            </div>
                        </div>

                        <div class="col-lg-4 col-md-4 col-12">
                            <div class="release-card">
                            </div>
                            <div class="release-card-overlay">
                                <h5 class="release-title">Black Adam</h5>
                                <h6 class="release-subtitle">
                                    Episode 1018
                                </h6>
                            </div>
                        </div>

                        <div class="col-lg-4 col-md-4 col-12">
                            <div class="release-card">
                            </div>
                            <div class="release-card-overlay">
                                <h5 class="release-title">Black Adam</h5>
                                <h6 class="release-subtitle">
                                    Episode 1018
                                </h6>
                            </div>
                        </div>

                        <div class="col-lg-4 col-md-4 col-12">
                            <div class="release-card">
                            </div>
                            <div class="release-card-overlay">
                                <h5 class="release-title">Black Adam</h5>
                                <h6 class="release-subtitle">
                                    Episode 1018
                                </h6>
                            </div>
                        </div>

                        <div class="col-lg-4 col-md-4 col-12">
                            <div class="release-card">
                            </div>
                            <div class="release-card-overlay">
                                <h5 class="release-title">Black Adam</h5>
                                <h6 class="release-subtitle">
                                    Episode 1018
                                </h6>
                            </div>
                        </div>

                        <div class="col-lg-4 col-md-4 col-12">
                            <div class="release-card">
                            </div>
                            <div class="release-card-overlay">
                                <h5 class="release-title">Black Adam</h5>
                                <h6 class="release-subtitle">
                                    Episode 1018
                                </h6>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>
</template>

<script>
export default {
    name: "Release"
}
</script>

<style scoped>
.release__container-fluid {
    max-width: 90%;
}

section.release {
    padding-top: 40px;
    padding-bottom: 60px;
}

div.body>div.row>div.col-12 {
    padding-bottom: 30px;
}

div.body>div.row>div.col-12:last-child {
    padding-bottom: 0px;
}

h3.release-title {
    font-weight: 600;
    font-size: 32px;
    color: #FFFFFF;
}

h6.release-subtitle {
    text-align: center;
    color: #e9e5e5a2;
}

div.release-card {
    background: url("../assets/img/2021-black-adam.jpg") no-repeat center 0px;
    background-size: cover;
    border-radius: 12px;
    height: 380px;
    max-width: 100%;
    width: 100%;
    display: flex;
    flex-direction: column;
    justify-content: space-between;
}


div.release-card::after {
    content: "";
    z-index: 10;
    width: 100%;
    height: 100%;
    border-radius: 12px;
    background: rgb(17, 16, 16);
    opacity: 0.5;
}

div.release-card-overlay>h5.release-title {
    font-weight: 600;
    font-size: 18px;
    margin-top: 10px;
    line-height: 18px;
    text-align: center;
    color: #FFFFFF;
}

@media screen and (max-width: 890px) {

    div.body>div.row>div.col-12 {
        padding-bottom: 30px;
    }

    div.body>div.row>div.col-12:last-child {
        padding-bottom: 0px;
    }
}

@media screen and (max-width: 789px) {
    div.release-card {
        height: 400px;
        width: 90%;
        margin: auto;
    }

    div.body>div.row>div.col-12 {
        padding-bottom: 30px;
    }

    div.body>div.row>div.col-12:last-child {
        padding-bottom: 0px;
    }
}
</style>