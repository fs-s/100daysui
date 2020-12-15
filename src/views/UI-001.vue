<template>
  <div class="flex-center">
    <div class="login-card">
      <form class="login-form">
        <h1>Create a new account</h1>
        <div class="form-group">
          <label for="email">Your E-mail</label>
          <input type="email" id="email" />
        </div>
        <div class="form-group">
          <label for="password">Password</label>
          <input type="password" id="password" />
        </div>
      </form>
      <button type="button" value="Refresh Page" onClick="location.href=location.href">Sign up</button>
    </div>
  </div>
</template>





<style lang="scss" scoped>
.login {
  &-card {
    margin:50px;
    text-align: left;
    border-radius: 10px;
    width: 300px;
    background: white;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
    padding: 4rem 2rem;
    //background:blue;
    background-image: url(https://i.pinimg.com/originals/60/04/30/600430c1d22c731b94cf4e7dae6b398a.gif);
    
    h1 {
      margin-top: 0;
      color: white;
      margin-bottom: 100px;
    }
    .form-group {
      display: flex;
      flex-direction: column;
      margin-bottom: 1rem;
    }
    input{
      border:none;
      border-bottom: 2px solid currentColor;
      padding: 10px 5px;
      border-radius: 12px;
    }
    label{
      margin-bottom: 5px;
      color:white;
    }
    button{
      background: #004EFF;
      padding:10px;
      border-radius:10px;
      color: white;
      outline: none;
      margin-left:auto;
      margin-right:auto;
      display:flex;

    }
    .button:hover {background-color: #3e8e41}

  .button:active {
    background-color: #3e8e41;
    box-shadow: 10 10px #666;
    transform: translateY(10px);
}
  }
}
</style>
