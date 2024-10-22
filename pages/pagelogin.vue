<template>
  <body>
    <div class="background">
      <h1 class="bar">...</h1>
      <div class="bg-img">
        <img src="/public/assets/img/css-3.png" alt="">
      </div>
      <h1>Student</h1>
      <h3>CHECK APP</h3>
      <div class="form">
        <form action="">
          <input type="email" name="" id="email" placeholder="Email or Phone"> <br>
          <input type="password" name="" id="email" placeholder="Password">
        </form>
      </div>
      <div class="backgound-button">
        <div class="Button">
          <a href="" class="a"><nuxt-link class="link" to="/forgot">Forget Password?</nuxt-link></a><br>
          <button><a href="">Login</a></button>
          <p>or</p>
          <button><nuxt-link to="/create">Create an account</nuxt-link></button>
        </div>
      </div>
    </div>
  </body>
</template>

<script>
export default {
  setup () {
    

    return {}
  }
}
</script>

<style>
@import url('https://fonts.googleapis.com/css2?family=Montserrat:wght@300;400;500;600;700&display=swap');

*{
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: 'Montserrat', sans-serif;
}

  body {
    background-size: cover;
    box-sizing: border-box;
    background-color: #5c6bc0;
    position: relative;
    padding: 0;
    margin: 0;
    display: flex;
    justify-content: center;
    text-align: center;
  }

  .bar {
    position: absolute;
    left: 5%;
    font-size: 40px;
  }
  
  .background {
    position: relative;
    background-color: #f2f2f2;
    height: 800px;
    width: 500px;
  }

  .bg-img {
    padding: 40px 0 20px;
  }

  .bg-img img {
    width: 200px;
  }

  h3 {
    padding: 0 0 40px;
  }

  .form {
    padding: 0 0 20px;
  }

  .form input {
    border-radius: 20px;
    border: 1px solid black;
    padding: 15px;
    margin: 0 0 20px;
    width: 400px;
  }

  .backgound-button {
    position: relative;
    background-color: #1d1f86;
    height: 245px;
    border-top-right-radius: 70px;
    border-top-left-radius: 70px;
  }

  .Button {
    position: relative;
    top: 40px;
  }

  .Button a {
    text-decoration: none;
    color: #fff;

  }

  .Button p {
    text-decoration: none;
    color: #fff;
    margin: 5px;
  }

  .Button button {
    border: 1px solid #fff;
    width: 400px;
    padding: 15px;
    color: #fff;
    border-radius: 20px;
    transition: 0.3s ease;
  }

  .Button button:hover {
    background-color: #5c6bc0;
  }

  .a {
    position: relative;
    bottom: 5px;
    font-weight: 600;
  }
</style>