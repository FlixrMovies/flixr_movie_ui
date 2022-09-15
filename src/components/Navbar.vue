<template>
    <nav class="navbar container-fluid nav__container-fluid">
        <router-link to="/" class="navbar-brand">Flixr Movies</router-link>

        <input type="text" class="form-control" placeholder="Search movie">
        <a class="mobile_only" @click="toggleMobileSearch()">
            <i class="fa fa-search" aria-hidden="true"></i>
        </a>
    </nav>

    <!-- Mobile Search -->
    <div class="mobile__search">
        <div class="search__container">
            <h4 class="search-title">Search...</h4>
            <input type="text" v-model="search" class="form-control" placeholder="Search movie">
        </div>

        <a class="mobile_only mobile_times" @click="closeMobileSearch()">
            <i class="fa fa-times" aria-hidden="true"></i></a>
    </div>
    <!-- End of Mobile Search -->
</template>

<script>
export default {
    name: "Navbar",
    data() {
        return {
            "search": ""
        }
    },
    methods: {
        toggleMobileSearch() {
            console.log("Mobile search for mobile...")
        },
        closeMobileSearch() {
            console.log("Close mobile search modal..")
        }
    }
}
</script>

<style scoped>
.nav__container-fluid {
    max-width: 95%;
}

.mobile_only,
.mobile__search {
    display: none;
}

.mobile__search {
    background: #192026;
    height: 100vh;
    position: absolute;
    top: 0%;
    left: 0%;
    bottom: 0%;
    right: 0%;
}

.mobile_times {
    color: #192026;
    background-color: #374151;
    width: 10%;
    height: 45px;
    padding: 10px;
    text-align: center;
    border-radius: 50%;
    position: absolute;
    top: 20px;
    right: 20px;
}

.search__container {
    width: 100%;
    margin: auto;
    padding: 15rem 0rem 10rem 0rem;
    text-align: center;
    justify-content: center;
}

h4.search-title {
    color: #FFFFFF;
    font-weight: 600;
    font-size: 32px;
}

nav {
    padding: 25px;
    box-shadow: 0px 0px 0px 0px;
    display: flex;
    justify-content: space-between;
    align-items: center;
}

nav a {
    font-weight: bold;
    text-decoration: none;

    font-weight: 700;
    font-size: 30px;
    letter-spacing: 0.07em;
    color: #FFFFFF;
}

.mobile__search input,
nav input {
    background: #374151;
    border-radius: 37px;
    align-items: center;
    padding: 8px 100px 8px 18px;
    gap: 10px;
    border-color: transparent;
    width: 40%;
    height: 50px;
}

.mobile__search input:focus,
nav input:focus {
    background: #374151;
    border-color: transparent;
}

@media screen and (max-width: 489px) {

    /* .mobile_only,
    .mobile__search {
        display: block;
    } */

    .mobile__search input {
        width: 90%;
        margin: auto;
    }

    nav {
        padding: 20px;
    }

    nav a {
        font-size: 22px;
    }

    nav input {
        display: none;
    }
}
</style>