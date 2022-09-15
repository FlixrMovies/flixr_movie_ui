<template>
    <section class="movie__detail">
        <!-- Navbar -->
        <Navbar />
        <!-- End of Navbar -->

        <div class="movie__detail">
            <div class="container-fluid movie__container-fluid">
                <div class="row">
                    <div class="col-lg-8 col-md-8">
                        <div class="movie">
                            <div class="head">
                                <h3 class="movie-title">
                                    Black Adam - Episode 1018
                                </h3>

                                <img src="@/assets/img/movie-loading.png" alt="movie-loading"
                                    class="w-100 img-responsive">
                                <!-- <video src=""></video> -->
                            </div>

                            <div class="body">
                                <div class="cover-art">
                                    <img src="@/assets/img/2021-black-adam.jpg" alt="movie-cover-art"
                                        class="img-responsive">

                                    <ul class="cover-details">
                                        <li class="cover-detail">
                                            Type:
                                            <p class="cover-detail-muted">TV</p>
                                        </li>
                                        <li class="cover-detail">
                                            Status:
                                            <p class="cover-detail-muted">Ongoing</p>
                                        </li>
                                        <li class="cover-detail">
                                            Studios:
                                            <p class="cover-detail-muted">Toei Animation</p>
                                        </li>
                                        <li class="cover-detail">
                                            Duration:
                                            <p class="cover-detail-muted">32 Min.</p>
                                        </li>
                                        <li class="cover-detail">
                                            Genres:
                                            <p class="cover-detail-muted">Action, Adventure</p>
                                        </li>
                                    </ul>
                                </div>
                            </div>

                            <div class="meta-desc">
                                <h5 class="meta-desc-title">
                                    Sypnosis:
                                </h5>
                                <p class="meta-desc-muted">
                                    Lorem ipsum dolor sit amet consectetur adipisicing elit. Deserunt, temporibus. In
                                    iure aliquam odit recusandae sequi, officiis optio exercitationem laudantium
                                    voluptatum modi perferendis blanditiis saepe ullam nemo tempora facilis!

                                    <br />

                                    Architecto explicabo facilis consequuntur fuga voluptatibus atque quae hic molestias
                                    dolor enim
                                    ea illo, expedita perspiciatis et veritatis corporis aut aliquam quis sapiente
                                    numquam odit totam quibusdam maiores nulla? Quaerat, laboriosam.
                                </p>
                            </div>
                        </div>
                    </div>
                    <div class="col-lg-4 col-md-4">
                        <div class="popular">
                            <div class="head">
                                <h3 class="movie-title">
                                    Popular Movies
                                </h3>
                            </div>

                            <div class="body">
                                <div class="row">
                                    <div class="col-lg-6 col-md-6 col-12">
                                        <div class="movie-card">
                                            <img src="@/assets/img/2021-black-adam.jpg" alt="movie-conver-art"
                                                class="w-100 h-100 img-responsive">
                                        </div>
                                    </div>

                                    <div class="col-lg-6 col-md-6 col-12">
                                        <div class="movie-card">
                                            <img src="@/assets/img/2021-black-adam.jpg" alt="movie-conver-art"
                                                class="w-100 h-100 img-responsive">
                                        </div>
                                    </div>

                                    <div class="col-lg-6 col-md-6 col-12">
                                        <div class="movie-card">
                                            <img src="@/assets/img/2021-black-adam.jpg" alt="movie-conver-art"
                                                class="w-100 h-100 img-responsive">
                                        </div>
                                    </div>

                                    <div class="col-lg-6 col-md-6 col-12">
                                        <div class="movie-card">
                                            <img src="@/assets/img/2021-black-adam.jpg" alt="movie-conver-art"
                                                class="w-100 h-100 img-responsive">
                                        </div>
                                    </div>

                                    <div class="col-lg-6 col-md-6 col-12">
                                        <div class="movie-card">
                                            <img src="@/assets/img/2021-black-adam.jpg" alt="movie-conver-art"
                                                class="w-100 h-100 img-responsive">
                                        </div>
                                    </div>

                                    <div class="col-lg-6 col-md-6 col-12">
                                        <div class="movie-card">
                                            <img src="@/assets/img/2021-black-adam.jpg" alt="movie-conver-art"
                                                class="w-100 h-100 img-responsive">
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
</template>

<script>
import Navbar from "@/components/Navbar.vue";

export default {
    name: "MovieDetail",
    components: {
        Navbar
    }
}
</script>

<style scoped>
section.movie__detail {
    background-color: #192026;
    height: auto;
    padding-bottom: 30px;
}

div.movie__container-fluid {
    max-width: 90%;
}

div.movie__detail {
    margin-top: 30px;
}

div.movie>div.head>h3.movie-title {
    padding-bottom: 30px;
}

h3.movie-title {
    color: #fff;
}

div.movie>div.head,
div.popular>div.head {
    margin-bottom: 30px;
}

div.popular>div.body>div.row>div.col-12 {
    margin-bottom: 30px;
}

div.movie-card {
    border-radius: 12px;
    height: 350px;
    text-align: center;
}

div.movie-card>img {
    border-radius: 12px;
}

div.cover-art {
    display: flex;

}

div.cover-art>img {
    width: 320px;
    height: 450px;
    border-radius: 15px;
}

ul.cover-details {
    list-style: none;
    margin-left: 0%;
    padding-left: 20px;
}

li.cover-detail {
    font-weight: 600;
    font-size: 19px;
    letter-spacing: 0.07em;
    color: #FFFFFF;
    margin-bottom: 20px;
}

li.cover-detail>p.cover-detail-muted {
    font-weight: 400;
    font-size: 16px;
    letter-spacing: 0.07em;
    color: #868686;
}

div.movie>div.meta-desc {
    margin-top: 30px;
}

h5.meta-desc-title {
    font-weight: 600;
    font-size: 20px;
    line-height: 32px;
    letter-spacing: 0.07em;
    color: #FFFFFF;
}

p.meta-desc-muted {
    font-weight: 400;
    font-size: 16px;
    line-height: 23px;
    letter-spacing: 0.07em;
    color: #868686;
    max-width: 80%;
}

@media screen and (max-width: 489px) {
    div.cover-art {
        flex-direction: column;
    }

    ul.cover-details {
        padding-left: 0%;
        margin-top: 10px;
    }

    li.cover-detail {
        margin-top: 20px;
        display: flex;
        justify-content: space-between;
    }

    p.meta-desc-muted {
        max-width: 100%;
    }

    div.popular>div.head {
        margin-top: 30px;
    }

    div.cover-art>img,
    div.movie-card>img {
        width: 90% !important;
        height: 350px;
    }

    div.cover-art>img {
        height: 450px;
        margin: auto;
    }
}
</style>