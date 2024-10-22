<template>
    <div class="background">
        <div class="content-head">  
            <h1>...</h1>
            <p>Let's</p>
            <h1 class="create">Create <br> Your <br> Account</h1>
        </div>
        <div class="form">
            <form action="form">
                <i class="fa fa-facebook"></i>
                <input type="text" placeholder="Full Name"><br>
                <input type="text" placeholder="Email Adress"><br>
                <input type="text" placeholder="Password"><br>
                <input type="text" placeholder="Retype Password">
            </form>
        </div>
        <div class="sighin">
            <input type="checkbox">&nbsp;I agree to the <span>Terms & Privacy</span></input> <br>
            <button class=""><nuxt-link to="">Sigh UP</nuxt-link></button> <br>
            <p>Have an account? <nuxt-link to="/pagelogin">Sign in</nuxt-link></p>
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
    .content-head {
        text-align: left;
        padding: 0 40px 0;
        background-color: #1d1f86;
        margin: 0 0 20px;
        border-bottom-right-radius: 70px;
        border-bottom-left-radius: 70px;
        height: 270px;
    }

    .content-head h1 {
        color: #fff;
    }

    .content-head p {
        color: #fff;
        font-size: 35px;
    }

    .sighin input{
        margin: 0 0 20px;
    }

    .sighin span{
        font-weight: 600;
    }

    .sighin button {
        background-color: #1d1f86;
        width: 400px;
        border-radius: 15px;
        padding: 15px;
        margin: 0 0 20px;
        transition: 0.3s;
    }

    .sighin button:hover {
        background-color: #5c6bc0;
    }

    Button a {
    text-decoration: none;
    color: #fff;
    }

    p a {
        color: #000;
        text-decoration: none;
        font-weight: 600;
    }
</style>