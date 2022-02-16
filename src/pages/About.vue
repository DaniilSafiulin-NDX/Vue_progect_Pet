<template>
  <div class="git-btn">
    <my-button>
      Оставьте ваш отзыв о моей работе
    </my-button>
    <my-select
        v-model="selectedSort"
        :options="sortOptions"
      />
  </div>
</template>

<script>
import MyButton from '../components/UI/MyButton.vue'
export default {
  components: { MyButton },

}
</script>

<style scoped>

</style>
