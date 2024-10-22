<template>
    <head>
        <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
    </head>
    <div class="background">
        <h1 class="barr">...</h1>
        <div class="fotgot-head">
            <img src="/public/assets/img/icons8-lock-150.png" class="icon" alt="Icon">
            <h1>Fotgot</h1>
            <span class="pass">Password?</span>
            <p>No worries, we'll send you <br> reset instructions</p>
        </div>
        <div class="formnew">
            <form action="">
                <span class="email">Email</span>
                <br>
                <input class="input" type="email" placeholder="Enter your Email">
                <button><nuxt-link to="">Reset Password</nuxt-link></button>    
                <p class="back"><nuxt-link to="/pagelogin">Back to Login</nuxt-link></p> 
            </form>
        </div>
    </div>
</template>

<script>
export default {
    setup () {
        

        return {}
    }
}
</script>

<style>
    .icon {
        width: 100px;    
    }

    .barr {
        text-align: left;
        padding: 0 40px;
    }

    .pass {
        font-size: 40px;
    }

    .fotgot-head {
        margin: 0 0 100px;
    }

    .formnew {
        background-color: #1d1f86;
        padding: 40px;
        height: 425px;
        border-top-right-radius: 70px;
        border-top-left-radius: 70px;
    }

    .email {
        position: absolute;
        left: 15px;
        top: -10px;
    }

    form{
        position: relative;
        top: 20%;
        color: #fff;
    }

    form .input {
        width: 400px;
        padding: 15px;
        border-radius: 20px;
        border: 1px solid #fff;
        color: #fff;
        margin: 0 0 20px;
    }

    form button {
        border: 1px solid #fff;
        width: 400px;
        padding: 15px;
        color: #fff;
        border-radius: 20px;
        transition: 0.3s ease;
        margin: 0 0 20px;
    }

    .back a{
        color: #fff;
        border-bottom: 2px solid;
    }

    form button:hover {
    background-color: #5c6bc0;
  }
</style>