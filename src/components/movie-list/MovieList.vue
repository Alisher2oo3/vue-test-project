<script>
import MovieListItem from '@/components/movie-list-item/MovieListItem.vue'

export default {
  components: {
    MovieListItem
  }
}
</script>

<template>
  <ul class="movie-list list-group">
    <MovieListItem />
    <MovieListItem />
    <MovieListItem />
  </ul>
</template>

<style scoped>
.movie-list {
  margin-top: 2rem;
  padding: 1.5rem;
  background-color: #fcfaf5;
  border-radius: 5px;
  box-shadow: 15px 15px 15px rgba(0, 0, 0, 0.15);
}
</style>