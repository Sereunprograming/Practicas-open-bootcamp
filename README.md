# Practicas-open-bootcamp
formularios


<!DOCTYPE html>
<html lang="en es">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Formularios</title>
    <link rel="stylesheet" href="stylo-formulario.css">
</head>
<body>
    <div class="container"> 
            <h2>Sign up to Form</h2>   
            <div class="botones">
                <button class="google-boton">
                    <picture >
                    <img src="https://static.vecteezy.com/system/resources/previews/010/353/285/original/colourful-google-logo-on-white-background-free-vector.jpg" alt="logo de google"/>
                    </picture>
                    <span>Registrase con Google</span>
                </button>
                <button class="twitter-boton" >
                    <picture>
                        <img src="https://cdn-icons-png.flaticon.com/512/107/107195.png" alt="logo-twitter">                      
                    </picture>
                </button>
            </div>
            <div class="separator">
                <hr>
                <span>or</span>
                <hr>
            </div>
            <form action="" method="">
                <div class="section-inputs">
                    <label for="name">
                        <span>Name</span>
                        <input id="name" name="name" />
                    </label>
                    <label for="username">
                        <span>Username</span>
                        <input id="username" name="username" />
                    </label>
                </div>
                <label for="email">
                    <span>Email</span>
                    <input id="email" name="email" />
                </label>
                <label for="password">
                    <span>Password</span>
                    <input id="password" name="password" placeholder="6+ caracteres" />
                </label>
                <label for="checkbox" class="checkbox-label">
                    <input type="checkbox" id="checkbox">
                    <span>Acepto las condiciones y el aviso legal</span>
                </label>
                <button type="submit" class="submit-btn">Crear Cuenta</button>
            </form>
        </div>
    </body>
    </html>
