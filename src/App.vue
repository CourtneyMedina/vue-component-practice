<template>
  <div class="container">
    <h2>Practice Components</h2>
    <br/>
    <Logo/>
    <br/><br/>
    <Button text="Home" type="button" className="button red"></Button>
    <Button text="Profile" type="button" className="button blue"></Button>
    <Button text="Subscriptions" type="button" className="button green"></Button>
    <Button text="Login" type="button" className="button yellow" disabled="true"></Button>
    <br/><br/>
    <Input placeholder="Search"/>
  </div>
</template>

<script>
import Logo from "./components/Logo.vue"
import Button from "./components/Button.vue"
import Input from "./components/Input.vue"

export default {
  components: {
    Button,
    Logo,
    Input,
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
