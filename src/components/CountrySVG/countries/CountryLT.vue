<script setup lang="ts">
import { useCountryGuessed } from '@/composables/useCountryGuessed.ts'
import { computed } from 'vue'

const { guessed } = useCountryGuessed('LT')
const classes = computed(() => ({ 'fill-stone-400 stroke-black': guessed.value }))
</script>

<template>
  <path
    id="lt"
    class="landxx eu lt"
    d="m 1446.8,217.493 c 1.02,0.164 1.26,-0.896 1.94,-1.367 0.75,-0.514 2.07,-0.683 2.93,-0.884 2.24,-0.522 4.86,-0.543 7.15,-0.413 1.35,0.592 3.01,0.08 4.24,0.44 1.49,0.127 4.66,0.811 6.09,-0.114 1.95,-1.264 2.03,0.11 3.24,1.07 0.73,0.583 1.69,0.474 2.58,0.608 1.2,0.179 2.27,0.687 3.04,1.564 0.49,0.548 3.55,2.568 4.24,2.195 -0.49,2.157 -0.32,2.717 1.63,3.237 -1.2,0.588 -0.32,1.577 -1.99,1.248 -1.28,-0.253 -1.43,0.964 -2.36,1.505 -2.29,1.32 -0.94,2.912 -2.85,4.952 0.48,0.196 1.45,0.275 1.58,0.935 0.15,0.796 -0.91,0.964 -1.44,0.792 0.55,-1.475 -1.72,-1.035 -1.84,-0.738 -0.57,1.378 -2.31,0.401 -2.98,1.794 -0.23,0.486 -1.44,0.493 -1.95,0.775 -0.87,0.476 -2.48,-0.05 -3.45,0.04 -0.48,0.04 -2.62,0.332 -2.78,-0.48 -0.2,-0.965 -1.18,-2.284 -2.12,-2.71 -1.3,-3.425 -0.36,-3.152 0.15,-4.497 0.1,-0.282 -1.82,-1.81 -2.14,-1.818 -0.77,-0.02 -4.77,0.215 -6.05,-0.811 -1.41,-1.118 -3.39,-1.503 -3.64,-0.404 0,-1.067 -1.71,-2.458 -2.25,-3.364 -0.67,-1.107 -0.57,-2.366 -0.97,-3.555"
    :class="classes"
  >
    <metadata id="title131">Lithuania</metadata>
  </path>
</template>
