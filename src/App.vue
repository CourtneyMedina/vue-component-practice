<template>
  <div class="container">
    <h2>Vue Search Engine</h2>
    <Logo/>
    <NavBar/>
    <Input placeholder="Search"/>
    <br/>
    <Button className="button red" text="Feeling Lucky?"></Button>
    <Button className="button purple" text="Search"></Button>
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
