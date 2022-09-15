<template>
    <div class="movie-card">
        <img :src=source :alt=text class="w-100 h-100 img-responsive">
    </div>
</template>

<script>
export default {
    name: "MovieCard",
    props: {
        source: String,
        text: String
    }
}
</script>