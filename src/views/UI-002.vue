<template>
  <div class="flex-center">
    <div class="login-card">
      <h1>Do you need help?</h1>
      <button
        type="button"
        value="Refresh Page"
        onClick="location.href=location.href"
      >
        Don't Click Here
      </button>
    </div>
  </div>
</template>





<style lang="scss" scoped>
button {
  background: pink;
  padding: 10px;
  border-radius: 10px;
  color: white;
  outline: none;
  margin-left: auto;
  margin-right: auto;
  display: flex;
  position: relative;
  bottom: -160px;
}
.button:hover {
  background-color: #3e8e41;
}

.button:active {
  background-color: #3e8e41;
  box-shadow: 10 10px #666;
  transform: translateY(10px);
}

.login {
  &-card {
    text-align: left;
    background: white;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
    padding: 10rem 6rem;
    //background:blue;
    background-image: url(https://www.elegantthemes.com/blog/wp-content/uploads/2020/02/000-404.png);
    background-size: 500px 500px;
    background-repeat: no-repeat;
    h1 {
      margin-top: 0;
      color: white;
      height: 100px;
      display: flex;
      color: chartreuse;
    }
  }
}
</style>
