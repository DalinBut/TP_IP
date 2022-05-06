<template>
  <form action="" method="post">
    <div class="container">
      <div class="rContainer">
        <img src="../assets/ava.png" alt="avatar" class="avatar"><br>
        <label for="uname"><b>Username</b></label><br>
        <input type="text" name="uname" required><br>
        <label for="password"><b>Password</b></label><br>
        <input type="password" name="password" required><br>
        <button type="submit"><b>Login</b></button><br>
        <p>Forgot <a href="#">password</a>?</p>
      </div>
    </div>
    <!-- <HelloWorld msg="Welcome to Your Vue.js App"/> -->
  </form>
</template>

<style>
.container {
  display: flex;
  justify-content: center;
  /* width: 100%; */
  text-align: center;
  float: left;
}
  .rContainer {
    background-color: aquamarine;
    width: 500px;
    height: 430px;
    text-align: center;
    float: left;
    /* margin-left: 200px; */
  }
  .avatar {
    width: 200px;
  }
  label {
    float: left;
    margin-left: 5%;
  }
  input {
    width: 90%;
    margin: 10px;
  }
  button {
    background-color: greenyellow;
    border-radius: 20px;
    margin: 10px;
    width: 100px;
    height: 30px;
    border: none;
    color: rgb(78, 65, 65);
  }
  button:hover {
    background-color: rgb(33, 151, 23);
    border: solid rgba(105, 230, 74, 0.681);
  }
  p {
    float: right;
    padding-right: 10px;
  }
</style>
