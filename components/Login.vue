<template>
  <div class="Login__Wrapper">
    <div class="Login__Container">
      <div class="Login__Icon">
        <img
          class="Login__Icon__Img"
          src="/kidsloop_min_logo.svg"
          alt="KidsLoop Logo"
        />
      </div>
      <h2 class="Sign_In__Header">Sign In</h2>
      <form class="Sign_In__Form">
        <input
          class="Login__Email"
          type="text"
          placeholder="Email or Phone *"
        />
        <input
          class="Login__Password"
          type="password"
          placeholder="Password *"
        />
        <div class="Form__Button__Container">
          <a href="#" class="Forgot__Password">Forgot Password?</a>
          <button class="Sign_In__Button">Sign In</button>
        </div>
      </form>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
/*  Start Submit button + forgot password container */
.Form__Button__Container {
  display: flex;
  justify-content: space-between;
  align-items: center;
}
.Forgot__Password {
  text-decoration: none;
  color: navy;
  font-weight: 600;
}
.Sign_In__Button {
  color: whitesmoke;
  background: dodgerblue;
  border-radius: 12px;
  height: 30px;
  width: 72px;
  border: none;
}
/* End forgot pw + signin button */

.Sign_In__Header {
  font-weight: 500;
}
.Sign_In__Form {
  display: flex;
  justify-content: flex-start;
  width: 100%;
  flex-direction: column;
  margin-top: 15px;
}
.Login__Email,
.Login__Password {
  padding: 5px;
  border: 1px solid lightgrey;
  border-radius: 12px;
  height: 40px;
  width: 100%;
}
.Login__Password {
  margin: 10px 0;
}

.Login__Wrapper {
  display: flex;
  justify-content: center;
  align-items: center;
  width: 100vw;
  height: 100vh;
}

.Login__Container {
  padding: 15px;
  display: flex;
  flex-direction: column;
  justify-content: flex-start;
  align-items: flex-start;
  width: 50vw;
  height: auto;
  max-width: 400px;
  max-height: 500px;
  border-radius: 14px;
  -webkit-box-shadow: 0px 0px 20px 5px rgba(0, 0, 0, 0.4);
  box-shadow: 0px 0px 20px 5px rgba(0, 0, 0, 0.1);
}
.Login__Icon__Img {
  width: 50px;
  height: 50px;
}
</style>