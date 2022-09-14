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
                        <div class="col-lg-2 col-md-2 col-12">
                            <div class="release-card">

                                <h6 class="overlay-text">
                                    Episode 1018
                                </h6>
                            </div>
                            <div class="release-card-overlay">
                                <h5 class="release-title">Black Adam</h5>
                            </div>
                        </div>

                        <div class="col-lg-2 col-md-2 col-12">
                            <div class="release-card">
                        
                                <h6 class="overlay-text">
                                    Episode 1018
                                </h6>
                            </div>
                            <div class="release-card-overlay">
                                <h5 class="release-title">Black Adam</h5>
                            </div>
                        </div>

                        <div class="col-lg-2 col-md-2 col-12">
                            <div class="release-card">
                        
                                <h6 class="overlay-text">
                                    Episode 1018
                                </h6>
                            </div>
                            <div class="release-card-overlay">
                                <h5 class="release-title">Black Adam</h5>
                            </div>
                        </div>

                        <div class="col-lg-2 col-md-2 col-12">
                            <div class="release-card">
                        
                                <h6 class="overlay-text">
                                    Episode 1018
                                </h6>
                            </div>
                            <div class="release-card-overlay">
                                <h5 class="release-title">Black Adam</h5>
                            </div>
                        </div>

                        <div class="col-lg-2 col-md-2 col-12">
                            <div class="release-card">
                        
                                <h6 class="overlay-text">
                                    Episode 1018
                                </h6>
                            </div>
                            <div class="release-card-overlay">
                                <h5 class="release-title">Black Adam</h5>
                            </div>
                        </div>

                        <div class="col-lg-2 col-md-2 col-12">
                            <div class="release-card">
                        
                                <h6 class="overlay-text">
                                    Episode 1018
                                </h6>
                            </div>
                            <div class="release-card-overlay">
                                <h5 class="release-title">Black Adam</h5>
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

h3.release-title {
    font-weight: 600;
    font-size: 32px;
    color: #FFFFFF;
}

div.release-card {
    background: url("../assets/img/2021-black-adam.jpg") no-repeat center;
    background-size: cover;
    border-radius: 12px;
    padding: 30px;
    height: 20vw;
    max-width: 100%;
    width: 100%;
}

h6.overlay-text {
    text-align: center;
    padding-top: 17vw;
    color: #192026;
}

/* div.release-card-overlay::before {
    content: "";
    position: absolute;
    z-index: 10;
    background: linear-gradient(180deg, rgba(29, 29, 29, 0) 0%, #0F1E29 100%);
    opacity: 0.5;
} */

div.release-card-overlay>h5.release-title {
    font-weight: 600;
    font-size: 18px;
    margin-top: 10px;
    line-height: 18px;
    text-align: center;
    color: #FFFFFF;
}
</style>