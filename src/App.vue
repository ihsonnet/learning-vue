<template>
  <div id="app">
    <header>
        <a href="">who we are?</a>
        <a href="">educourse stats</a>
    </header>
    <section class="white">
        <div class="container">
            <div class="single-box">
            <h2>who we are?</h2>
            <div class="box-left">
            <h2>about educourse template</h2>
            <p>Curabitur ut est a mi fermentum tristique. Aliquam et ante odio. Donec elementum odio eget ex porta, vel laoreet nisl fermentum. Nam risus purus, hendrerit id placerat sit amet, tempor a urna. Maecenas id quam et dolor facilisis pulvinar.</p>
    
            <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.</p>
            <br>
            <a href="">view more</a>
            </div>
            <div class="box-right">
            <img src="dist/students.jpeg" alt="image">
            </div>
            </div>
        </div>
    </section>
    <section class="gray">
        <div class="container">
            <div class="single-box">
                <h2>educourse stats</h2>
                <p class="sub">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Donec neque erat, ultrices cursus nisi at, hendrerit tristique.</p>
                <div class="box">
                    <img src="dist/tool.png">
                    <h2>500+ <span>professionals trained</span></h2>
                    
                </div>
                <div class="box">
                    <img src="dist/expert.png">
                    <h2>10+ <span>Years of Experience</span></h2>
                    
                </div>
                <div class="box">
                    <img src="dist/clients.png">
                    <h2>15+ <span>Companies Association</span></h2>
                    
                </div>
                <div class="box">
                    <img src="dist/success.png">
                    <h2>99% <span>Job Guarantee</span></h2>
                     
                </div>
            </div>
        </div>
    </section>
  </div>
</template>

<script>
export default {
  name: 'app',
  data () {
    return {
      msg: 'Welcome to Your Vue.js App'
    }
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}

h1, h2 {
  font-weight: normal;
}

ul {
  list-style-type: none;
  padding: 0;
}

li {
  display: inline-block;
  margin: 0 10px;
}

a {
  color: #42b983;
}
</style>
