<template>
  <Tutorial />
</template>

<script>
export default {
  name: 'IndexPage',
  head(){
    return{
      title:"Home Page",
      meta:[
        {
          title: "Home Page",
          name: "Home page test data",
          content: "Home page content"
        }
      ]
    }
  },
  mounted() {
    console.log(process.env.BASE_URL)
  }
}
</script>
