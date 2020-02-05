<template>
  <div class="container">
    <h1>{{ msg }}</h1>     
    <div>
      <h4 class="subHeading"> Please fill in the details</h4>
    </div>
     <div class="containerForm">
       <h2 class="formHeading"
       >Login details</h2>
       <div class="responsiveForm">
       <div class="responsiveA">
         <label><b>Username</b></label>
          <input type="text" placeholder="Enter Username" required>
       </div>
       <div class="responsiveB">
          <label><b>Password</b></label>
          <input type="password" placeholder="Enter Password" required>
       </div>
       </div>
        <div class="responsiveC">
          <button type="submit">Login</button>
        </div>
     </div>
  </div>
</template>

<script>
export default {
  name: 'LoginForm',
  data () {
    return {
      msg: 'Lets get started!'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped src="../assets/css/main.css">
@import '../assets/css/main.css';
</style>
