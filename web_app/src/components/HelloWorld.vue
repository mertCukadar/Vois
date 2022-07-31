<template>
  <nav>
    <img class="logo" src="@/assets/Logo.png" />
    <nav class="SignInBar">
      <input type="text" placeholder="User Name" />
      <input type="password" name="Password" id="pass" placeholder="Password" />
      <button>Sign In</button>
    </nav>
  </nav>
  <hr />
</template>

<script>
export default {};
</script>

<style>
nav {
  height: 3.5rem;
}
.logo {
  width: 7rem;
  float: left;
  margin-top: 15px;
  margin-left: 15px;
}
.SignInBar {
  float: right;
  margin-top: 1rem;
  margin-right: 40px;
}

nav nav input {
  margin-left: 20px;
  border: 0;
  border-bottom: 1px solid #2155cd;
  outline: 0;
  font-size: 0.8rem;
  padding: 7px 0px;
  background: transparent;
  transition: border-color 0.2s;
}

nav nav button {
  margin-left: 20px;
  border-radius: 5px;
  padding: 10px;
  background-color: #2155cd;
  color: #fff;
  border: none;
}

hr {
  width: 100%;
  border: 0.4px solid #819bd8;
}
</style>
