<template>
  <Blog> </Blog>
</template>
<script>
  var playbutton = document.querySelector('.play-icon');
  playbutton.addEventListener("click",function (e){
    e.preventDefault();
    document.querySelector('.landig-video-col .show-hide-image').style.display = "none";
  })

  export default {
    name: "BlogPage",
    head(){
      return{
        title:"Blog Page",
        meta:[
          {
            title: "Blog Page",
            name: "Blog page test data",
            content: "Blog page content"
          }
        ]
      }
    }
  }
</script>
