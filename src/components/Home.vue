<template>
    <div>
      <hr class="rr" style="margin:0;"> 
       <div class="main">
           <div class="img-container"></div>
           <div class="sl">
           <h1 style="padding-top:150px!important;color:#17a2b8;font-style:bold;">Romulus  Whittaker</h1>
           <h3 style="color:black;">The Official Site</h3>
           <p style="color:black;">
            An Indian herpetologist, wildlife conservationist and founder of the Madras Snake Park
           </p></div>
         </div>
    </div>
   </template>
   
   <script>
   export default {
     name: 'HelloWorld',
     data () {
       return {
         msg: 'Welcome to Your Vue.js App'
       }
     }
   }
   </script>
   
   <!-- Add "scoped" attribute to limit CSS to this component only -->
   <style scoped>
   body,
   h2 {
     margin: 0;
   }
   .main {
     height: 100vh;
   }
   .img-container {
     width:60%;
     height: 100%;
     background-color: lightgray;
     float: right;
     background: url("../assets/rome.jpeg") no-repeat center center / cover;
     -webkit-shape-outside: polygon(25% 0, 100% 0, 100% 100%, 0 100%);
     shape-outside: polygon(25% 0, 100% 0, 100% 100%, 0 100%);
     -webkit-clip-path: polygon(25% 0, 100% 0, 100% 100%, 0 100%);
     clip-path: polygon(25% 0, 100% 0, 100% 100%, 0 100%);
   }
   
   .rr{
  border: 2px solid #dee2e6!important;;
  border-radius: 3px!important;
}
   </style>