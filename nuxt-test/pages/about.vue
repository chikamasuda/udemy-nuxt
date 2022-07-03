<template>
  <div>
    about<br>
    {{ now }}
    <img src="~/assets/images/nuxt-course.jpg" with="300" alt=""><br>
    <div class="red-b">assets/CSSのテスト</div>
  </div>
</template>

<script>
export default {
  data() {
    return {
      now: null
    }
  },
  mounted() {
    this.now = this.$dayjs().format('YYYY-MM-DD HH:mm:ss')
  }
}
</script>

<style>

</style>