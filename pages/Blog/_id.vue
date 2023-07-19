<template>
  <BlogDetails />
</template>
<script>
export default {
  name: "BlogDetailsPage",
  mounted() {
    console.log("route.params.id=====>"+this.$route.params.id)
  }
}
</script>
