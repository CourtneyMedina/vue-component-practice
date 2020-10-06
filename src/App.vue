<template>
  <div class="container">
    <h2>Practice Components</h2>
    <NavBar/>
    <Input placeholder="Search"/>
    <Logo/>
    <Button className="button purple" text="Donate!"></Button>
  </div>
</template>

<script>
import Logo from "./components/Logo.vue"
import NavBar from "./components/NavBar.vue"
import Input from "./components/Input.vue"
import Button from "./components/Button.vue"

export default {
  components: {
    Logo,
    Input,
    NavBar,
    Button,
  }
  
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}

.container{
  margin: 0 auto; /* centers everything */
  padding: 0px 15px;
}

</style>
