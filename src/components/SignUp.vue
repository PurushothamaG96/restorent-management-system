<template>
    <div class="main-container">
        <img class="logo-sign" src="../assets/resto-logo.webp" alt="">
        <div class="input">
            <input type="text" placeholder="Enter Name">
        </div>
        <div class="input">
            <input type="email" placeholder="Enter Email">
        </div>
        <div class="input">
            <input type="password" placeholder="Enter password">
        </div>
        <div class="input">
            <button>Sign Up</button>
        </div>
    </div>
</template>

<script>
    export default {
        name: "signUp",
    }
</script>

<style scoped>
    .logo-sign{
        width: 7rem;
    }
    .main-container{
        width: 90%;
        margin: auto;
    }
    .input{
        width: 50%;
        margin: 2rem auto;
    }
    .input>input{
        width: 100%;
        height: 2rem;
        font-size: large;
        padding:0px 1rem;
        border: 1px solid orangered;
        border-radius: 1rem;
    }
    .input>input:focus{
        border: 2px solid orangered;
    }
    .input>button{
        width: 50%;
        height: 2rem;
        color:aliceblue;
        background: orangered;
        font-size: large;
        border-radius: 1rem;
        border:1px solid orangered;
        
    }
    @media screen and (max-width: 768px) {
        .main-container{
            width: 100%;
        }
        .input{
            width: 100%;
        }
    }
</style>