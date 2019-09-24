<template>

  <img src="https://vueschool.io/img/favicons/apple-touch-icon.png" alt="the logo">

</template>
<script>
	export default {
  components: {

  },
  computed: {
    posts () {
      return this.$store.state.posts.all
    }
  }
}
</script>