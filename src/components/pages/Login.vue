<template>
  <div class="login">
    <div class="loginHeader">
      User login
    </div>
   <div class="loginContainer">
     <table>
       <tr>
         <td>Username</td>
         <td>:</td>
         <td><input type="text" placeholder="Username"> </td>
       </tr>
       <tr>
         <td>Password</td>
         <td>:</td>
         <td><input type="password" placeholder="Password"></td>
       </tr>
       <tr>
         <td></td>
         <td></td>
         <td><button class="addBtn">Login</button></td>
       </tr>
     </table>
   </div>
  </div>
</template>

<script>
export default {
  name: 'Login',
  data () {
    return {
      msg: 'Welcome to Your Vue.js App'
    }
  }
}
</script>
