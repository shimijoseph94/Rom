<template>
 <div>
    <div class="main">
        <div class="img-container"></div>
        <div class="sl">
        <h2>Title</h2>
        <p>
          Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla pellentesque orci id elit mollis luctus. Integer tincidunt euismod lectus sodales convallis. Pellentesque bibendum libero turpis, ac hendrerit ante maximus et. Cras interdum tortor id metus
          hendrerit volutpat.
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
  width: 70%;
  height: 100%;
  background-color: lightgray;
  float: right;
  background: url(http://fillmurray.com/1000/1000) no-repeat center center / cover;
  -webkit-shape-outside: polygon(25% 0, 100% 0, 100% 100%, 0 100%);
  shape-outside: polygon(25% 0, 100% 0, 100% 100%, 0 100%);
  -webkit-clip-path: polygon(25% 0, 100% 0, 100% 100%, 0 100%);
  clip-path: polygon(25% 0, 100% 0, 100% 100%, 0 100%);
}
</style>
<template>
 <div class="container-fluid">
    <section >
        <div class="content">
            <h1>Why do we use it?</h1>
<p>It is a long established fact that a reader will be distracted by the readable content of a page when looking at its layout. The point of using Lorem Ipsum is that it has a more-or-less normal distribution of letters, as opposed to using 'Content here, content here', making it look like readable English. Many desktop publishing packages and web page editors now use Lorem Ipsum as their default model text,</p>
        </div>
        <div class="image-box"></div>
    </section>
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
section{
    position: absolute;
    top: 50%;
    left: 50%;
    transform: translate(-50%,-50%);
    height: 400px;
    width: 1200px;
    background: #f00;
    box-shadow:0px 25px 30px rgba(0,0,0,.5);
    display: flex;
}
.content{
    width: calc(50% - 50px);
    height: 100%;
    background: #000;
    box-sizing: border-box;
    padding: 30px 50px;
    color: #fff;
    font-family: sans-serif;
    line-height: 25px;
    
}
.image-box{
       width: calc(50% + 50px);
    height: 100%;
    background: #f00;
    box-sizing: border-box;
    border-left: 100px solid #000;
    border-bottom: 400px solid transparent;
    background: url(http://www.divscode.com/bootimg/pexel.jpeg);
    background-position: -350px -59px;
    background-repeat: no-repeat;
    
    
}
</style>
