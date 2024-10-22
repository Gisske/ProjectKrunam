<template>
    <v-app>
        <v-container class="fill-height d-flex justify-center align-center" fluid>
            <v-row justify="center" align="center" class="full-sceen">
                <v-col cols="12" sm="12" md="12">
                    <v-row justify="center" align="center">
                        <v-img src="/public/assets/img/css-3.png" alt="img" style="height:200px;;"></v-img>
                    </v-row>
                    <v-row justify="center" align="center">
                        <span style="font-size: 40px; font-weight: 700; color: orange;">Student</span>
                    </v-row>
                    <v-row class="mb-4" justify="center" align="center">
                        <span style="font-size: 20px; color: black;">CHECK APP</span>
                    </v-row>
                    <v-form>
                        <v-text-field
                            prepend-inner-icon="mdi-account"
                            label="Email or Phone"
                            outlined
                            required
                            color=""
                            class="mb-7"
                        ></v-text-field>

                        <v-text-field
                            prepend-inner-icon="mdi-lock"
                            label="Password"
                            outlined
                            required
                            color=""
                            class="mb-16"
                        ></v-text-field>
                    </v-form>  
                    <v-row class="cardBG" justify="center" align="center">
                    <v-col cols="12" sm="8" md="4">
                        <v-row class="mb-4" justify="center">
                            <nuxt-link to="/forgot">Forgot password</nuxt-link>
                        </v-row>
                        <v-row class="button mb-4" justify="center">
                            <nuxt-link to="/forgot">Login</nuxt-link>
                        </v-row>
                        <div class="mb-4" style="text-align: center;">
                            <span>or</span>
                        </div>
                        <v-row class="button" justify="center">
                            <nuxt-link to="/forgot">Create</nuxt-link>
                        </v-row>
                    </v-col> 
                </v-row>  
                </v-col>
            </v-row>
        </v-container>
    </v-app>
</template>
  
<style scoped>
 .full-sceen {
    height: 100%;
    width: 100%;
    background-color: rgb(56, 112, 68);
 }

 .cardBG {
    background-color: rgb(255, 255, 255);
    height:40vh;
    border-top-left-radius: 100px;
    border-top-right-radius: 100px;
 }

 .forgot a{
    text-decoration: none;
    color: #000;
 }

 .Login {
    background-color: rgb(56, 112, 68);
    color: white;
    padding: 25px;
    border-radius: 20px;
 }

 .Create {
    background-color: rgb(56, 112, 68);
    color: white;
    padding: 25px;
    border-radius: 20px;
 }

 .button a {
    text-decoration: none;
    background-color: rgb(56, 112, 68);
    width: 700px;
    padding: 20px;
    text-align: center;
    color: #fff;
    border-radius: 20px;
 }
</style>
  