<template>
  <div class="register">
    <form action="">
      <h1>Sign Up</h1>
      <span>Please fill in this form to create an account</span><br>
      Email
      <input type="email" name="email" id="" placeholder="Enter Email">
      Username
      <input type="text" name="uname" id="" placeholder="Username"><br>
      First name
      <input type="text" name="fname" id="" placeholder="First Name"><br>
      Last name
      <input type="text" name="lname" id="" placeholder="Last Name"><br>
      Password
      <input type="password" name="password" id="" placeholder="Create your Password"><br>
      <span>By creating an account you agree to our <a href="#">Terms $ Privacy</a>.</span>
      <button type="submit">Sign Up</button>
    </form>
  </div>
</template>
<style>
  .register {
    display: flex;
    justify-content: center;
    background-color: aquamarine;
  }
</style>
