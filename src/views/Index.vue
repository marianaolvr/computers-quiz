<template>
  <div class="index">
    <QuizCard />
  </div>
</template>

<script lang="ts">
import Vue from 'vue'
import QuizCard from '@/components/QuizCard.vue'

export default Vue.extend({
  name: 'Index',
  components: {
    QuizCard
  }
})
</script>
