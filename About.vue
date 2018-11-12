<template>
  <div >
      <h1>This is an about page</h1>
      <ul id="example-1">
          <li v-for="film in allFilms" :key="film.episode_id">
              {{ film.title }}

          </li>
</ul>
</div>
</template>

<script>

import { films } from '../assets/films'
import { starships } from '../assets/starships'

export default {
  data: function() {
      return {
          allFilms: films
      }
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
