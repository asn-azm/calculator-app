<template>
<h1>{{message}}</h1>
</template>

<script>
export default {
  data(){
    return {
      message: "Created By Ahsan Azam"
    }
  }
}
</script>

<style scoped>
h1 {
  font-size: 33px;
  font-family: Arial, Helvetica, sans-serif;
  width: 480px;
  margin-left: 673px;
  background-color: cyan;
  animation-name: Heading;
  color: lime;
  animation-duration: 5s;
  
}

@keyframes Heading {
  0%   {color: lightgreen;}
  10%  {color: yellow;}
  20%  {color: blue;}
  30% {color: green;}
  40%   {color: pink;}
  50%  {color: lightgreen;}
  60%  {color:purple;}
  70% {color:lightseagreen;}
  80%  {color:lightskyblue;}
  90% {color: lightcoral;}
  100% {color: lightskyblue;}
   
}
</style>