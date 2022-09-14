<template>
    <section class="explore">
        <div class="container-fluid explore__container-fluid">

            <div class="explore">
                <div class="head">
                    <h3 class="explore-title">
                        Explore
                    </h3>
                    <h5 class="explore-subtitle">
                        What are you gonna watch today?
                    </h5>
                </div>

                <div class="body">
                    <div class="explore-card explore-card-overlay">

                        <div class="explore-card-content">
                            <h4 class="card-content-title">
                                Black Adam
                            </h4>
                            <h6 class="card-content-desc">
                                Lorem ipsum dolor sit amet consectetur adipisicing elit.
                                Nobis iure ut vero expedita quaerat commodi!
                                Corrupti quam nesciunt animi, incidunt saepe iusto
                                adipisci facere autem natus, quibusdam magni, sit illum
                                deserunt maiores facilis! Recusandae vitae vero aperiam
                                eaque, voluptas quaerat!
                            </h6>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>
</template>

<script>
export default {
    name: "Explore",
}
</script>

<style scoped>
section.explore {
    padding-top: 30px;
}

.explore__container-fluid {
    max-width: 90%;
}

div.head>h3.explore-title {
    font-weight: 600;
    font-size: 32px;
    color: #FFFFFF;
}

div.head>h5.explore-subtitle {
    font-weight: 400;
    font-size: 22px;
    color: #868686;
}

div.body {
    margin-top: 20px;
}

div.explore-card {
    background: url("../assets/img/black-adam.jpg") no-repeat;
    background-position: contain;
    object-fit: cover;
    border-radius: 12px;
    padding: 30px;
    height: 30vw;
    max-width: 100%;
    width: 100%;
}

div.explor-card::before {
    background: linear-gradient(269.96deg, rgba(29, 29, 29, 0) 0.04%, rgba(29, 29, 29, 0.8) 99.5%);
}

div.explore-card-content {
    padding-top: 15vw;
    z-index: 10;
}

h4.card-content-title {
    font-weight: 600;
    font-size: 36px;
    line-height: 64px;
    color: #FFFFFF;
    flex: none;
    order: 0;
    align-self: stretch;
    flex-grow: 0;
}

h6.card-content-desc {
    font-weight: 400;
    font-size: 18px;
    line-height: 27px;
    max-width: 50%;
    color: #FFFFFF;
    flex: none;
    order: 1;
    align-self: stretch;
    flex-grow: 0;
}
</style>