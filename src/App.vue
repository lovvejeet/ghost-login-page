<template>
  <body>
    
 
<main class="main">
  <!-- <img src="..\src\assets\ghost_PNG69.png" alt=""> -->
  <form class="form" action="">
<div class="logo">
  <label>GHOST TOWN</label>
<!-- <img src="..\src\assets\2136665.png" alt="">  -->
</div>

<div class="userdiv">
  <div>
<label id="user-label">Username</label>
</div>
<input type="text" name="user" id="user-input">
</div>
<div class="password-div">
<div class="passdiv">
<label id="pass-label" >Password</label>
</div>
<input type="password" name="password" id="pass-input">
</div>

<div class="sign-div">
  <button class="sign-btn">Login</button>
</div>

</form>
</main>
</body>
</template>

<style>

body{
  cursor: url("..\\src\\assets\\2136665.png");
font-family: -apple-system,BlinkMacSystemFont,"Segoe UI","Noto Sans",Helvetica,Arial,sans-serif,"Apple Color Emoji","Segoe UI Emoji";

}
.main{
  display: grid;
  justify-content: center;
    margin-top: 110px;
    

    
}
.form{
    background-image: url("..\\src\\assets\\giphy.gif");
    font-family: -apple-system,BlinkMacSystemFont,"Segoe UI","Noto Sans",Helvetica,Arial,sans-serif,"Apple Color Emoji","Segoe UI Emoji";
    height: 490px;
    width: 310px;
    display: grid;
    justify-content: center;
    border-radius: 12px;
    box-shadow: 29px 30px 63px;
    
    
;
}

.logo{
    display: flex;
    margin-left: 18px;
    color: white;
    margin-top: 46px;
    font-size: 30px;
    font-weight: 700;
    text-shadow: -4px 1px 14px;
    font-family: -apple-system,BlinkMacSystemFont,"Segoe UI","Noto Sans",Helvetica,Arial,sans-serif,"Apple Color Emoji","Segoe UI Emoji";
}
#user-label,#pass-label{
  color: aliceblue;
}
#user-input,#pass-input{
    display: block;
    padding: 5px 12px;
    font-size: 14px;
    margin-top: 10px;
    margin-bottom: 16px;
    width: 100%;
    border: 1px solid #d0d7de;
    border-radius: 6px;
    transition: 0.50s;
    font-family: -apple-system,BlinkMacSystemFont,"Segoe UI","Noto Sans",Helvetica,Arial,sans-serif,"Apple Color Emoji","Segoe UI Emoji";
    
}

.sign-btn{
    padding: 5px 16px;
    width: 100%;
    text-align: center;
    border-radius: 6px;
    margin-left: 10px;
    /* background-color: #d0d7de; */
    border: none;
    font-family: -apple-system,BlinkMacSystemFont,"Segoe UI","Noto Sans",Helvetica,Arial,sans-serif,"Apple Color Emoji","Segoe UI Emoji";
    /* white-space: nowrap;
    vertical-align: middle; */
    transition: 0.50s;
}
.password-div{
   margin-top: -58px;
}

/* hover effects */
#user-input:hover,#pass-input:hover{
  background-color:#d0d7de ;
}
.sign-btn:hover{
  background-color:#d0d7de ;
}
</style>