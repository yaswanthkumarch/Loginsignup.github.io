# Loginsignup.github.io
<!DOCTYPE html>

<html>

    <head>

        <title>Login & Register Box</title>

        <meta name="viewport"

        content="width=device-width,

        initial-scale=1.0">

        <meta charset="UTF-8">
        <link rel="stylesheet" href="style.css"/>

        <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.2.0/css/all.min.css"/>

    </head>

    <body>

        <div class="container">

           <div class="form-btn">

               <span onclick="login()">Login</span>

               <span onclick="regist()">SignUp</span>

               <hr id="indicator">

           </div>

           <form id="loginform">

               <input type="text" placeholder="Username">

               <input type="password" placeholder="Password">

               <button class="btn" id="alert" onclick="alertmsg()">Login</button>

               <a href="#">Forgot Password?</a>

           </form>

           <form id="registerform">

               <input type="Email" placeholder="Email">

               <input type="text" placeholder="Username">

               <input type="password" placeholder="Password">

               <button  class="btn" id="alert" onclick="alertmsg()">Sign Up</button>

           </form>

        </div>

        <script>

              var loginform=document.getElementById('loginform')

            var signform=document.getElementById('registerform')

            var indicator=document.getElementById('indicator')

            function login(){

                signform.style.transform="translateX(-290px)"

                loginform.style.transform="translateX(-290px)"

               indicator.style.transform="translateX(5px)" 

            }

            function regist(){

                signform.style.transform="translateX(0px)"

                loginform.style.transform="translateX(0px)"

                indicator.style.transform="translateX(110px)"

            }

        </script>

    </body>

</html>
