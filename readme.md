# <span style="color:#98CA3F">Proyecto para Curso Práctico Frontend Developer Platzi</span>👩‍💻🐱‍🐉🐱‍🏍

## <span style="color:#98CA3F">Documentación y recursos entregados por Platzi</span>

- [Estilos del proyecto](https://scene.zeplin.io/project/60afeeed20af1378ed046538)

- [Vista Mobile en Figma](https://www.figma.com/proto/bcEVujIzJj5PNIWwF9pP2w/Platzi_YardSale?node-id=0%3A719&amp%3Bscaling=scale-down&amp%3Bpage-id=0%3A1&amp%3Bstarting-point-node-id=0%3A719)

- [Vista Desktop en Figma](https://www.figma.com/proto/bcEVujIzJj5PNIWwF9pP2w/Platzi_YardSale?node-id=3%3A2112&amp%3Bscaling=scale-down&amp%3Bpage-id=0%3A998&amp%3Bstarting-point-node-id=5%3A2808)


## <span style="color:#98CA3F">Paso a paso</span> 🏃‍♀️📝🏃‍♀️
1. Despues de ver las 3 primeras clases para saber cual será el proyecto y como lo llevaremos a cabo, en la clase 4, ya comenzamos a crear la carpeta del proyecto "Curso Practico Frontend Platzi".

2. Abrimos la carpeta con nuestro editor de código (Visual Studio Code) y creamos nuestro primer archivo "readme.md" para comenzar a documentar el proceso.

3. Creamos nuestro segundo archivo, según lo que seguimos en el video de la ***[clase 4(Sistema de diseño, assets y variables de CSS)](https://platzi.com/clases/2477-frontend-developer-practico/41503-sistema-de-diseno-assets-y-variables-de-css/)***, "index.html".

4. En el archivo "index.html", creamos nuestra estructura de código html:5.

5. Contrario a como se muestra en la clase 4, decidí crear un archivo css "styles.css", para poder dividir mejor el código, puesto que ya tengo un conocimiento más avanzado de desarrollo frontend (No se si funcionará igual que en el video puesto que nunca he trabajado variables en CSS puro.).

6. Vincular el archivo CSS a mi archivo HTML con:
    ```html
    <link rel="stylesheet" href="styles.css">
    ```
    Nota: Se colocó esta etiqueta dentro de la etiqueta `<head>` antes de la etiqueta `<title>`.

7. <span style="color:#98CA3F">***Variables:***</span> Siguiendo con la clase 4, dentro del archivo "styles.css", se crea el siguiente código para crear variables en CSS, en el video se realizó dentro del archivo HTML, en etiqueta `<style>`:
    ```css
    :root{
        --very-light-pink: #C7C7C7;
        --white: #FFFFFF;
        --text-input-field: #F7F7F7;
        --black: #000000;
        --hospital-green: #ACD9B2;
        --dark: #232830;
    }
    ```

8. Siguiendo el video 4, hay que buscar la fuente "Quicksand" que aparece en el archivo de estilos dado por diseño. Esta fuente la buscamos en [Google Fonts](https://fonts.google.com/).

9. Al encontrar la fuente en google fonts, seleccionamos ligth(300), medium(500) y bold(700), según lo visto en el diseño.

10. Copiamos los links que nos provee google fonts.
    ```html
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Quicksand:wght@300;500;700&display=swap" rel="stylesheet">
    ```
    Y los pegamos dentro de la etiqueta `<head>` de nuestro archivo "index.html" antes de la etiqueta `<link>` del vinculo del archivo CSS.

11. Tambien copiamos CSS rules de google fonts y los pegamos en el archivo "styles.css", dentro de la etiqueta body
    ```css
    body{
        font-family: 'Quicksand', sans-serif;
    }
    ```
12. <span style="color:#98CA3F">***Sistemas de Diseño:***</span> Revisar la [guia de diseño](https://polaris.shopify.com/design/design) aconsejada en el video 4, para conocer más sobre estos principios que nos pueden ayudar a maquetar.

13. <span style="color:#98CA3F">***Assets:***</span> Agregar las carpetas con los logos y los iconos que necesitaremos en nuestro proyecto, las descargue de un archivo drive suministrado por un compañero en los comentarios del video 4.

14. Siguiendo el video de la ***[clase 5(Crear nueva contraseña: HTML)](https://platzi.com/clases/2477-frontend-developer-practico/41504-crear-nueva-contrasena-html/)***, comenzamos la maquetación de la vista para Mobile de la creación de una nueva contraseña.

15. Creamos el archivos "passwordView.html".

16. Creamos la estructura html:5 dentro del archivo "passwordView.html".

17. Analizamos el diseño entregado (Mobile first) para comenzar la maquetación en el archivo html. Dentro de la equeta `<body>` comenzamos a maquetar nuestros elementos html así:
    ```html
    <div class="login">
        <div class="form-container">
            <img src="" alt="logo" class="logo">
            <h1 class="title">Create a new password</h1>
            <p class="subtitle">Enter a new password for your account</p>

            <form action="/" class="form">
                <label for="password">Password</label>
                <input type="password" name="" id="password" placeholder="************" class="input input-password">

                <label for="new-password">Re-enter password</label>
                <input type="password" name="" id="new-password" placeholder="************" class="input input-password">

                <input type="submit" value="confirm" class="primary-button login-button">
            </form>
        </div>
        ```
18. Siguiendo el video de la ***[clase 6(Crear nueva contraseña: CSS)](https://platzi.com/clases/2477-frontend-developer-practico/41505-crear-nueva-contrasena-css/)***, comenzamos a darle los estilos la maquetación hecha en html de la vista para Mobile de la creación de una nueva contraseña.

19. Para seguir con la modularización del código creó un archivo "password.css" para poder darle estilos a la vista password, y para darle más orden también creo una carpeta styles para agregar allí todos los archivos css.

20. Modificó la ruta del archivo "styles.css", vinculado en el archivo "index.html".

21. Vinculo el archivo "password.css" con el archivo "passwordView.html", colocando en este último archivo el siguente código dentro de la etiqueta `<head>`:
    ```html
    <link rel="stylesheet" href="styles/password.css">
    ```

22. En el archivo "password.css", agrego todas las clases en orden de los elementos maquetados en el archivo "passwordView.html". Comenzando a dar los respectivos estilos en el archivo css.
    

23. Para centrar nuestro contenido tanto horizontal como verticalmente, ***hacemos uso de grid y su propiedad place-items: center;***, para realizarlo de una forma sencilla.
    ```css
    body{
        margin: 0;
    }
    .login {
        width: 100%;
        height: 100vh;
        display: grid;
        place-items: center;
    }
    ```

24. Ahora seguimos con los estilos del elemento `<div>` con clase form-container, creando un sistema de ilas y columnas con display: grid:
    ```css
    .form-container {
        display: grid;
        grid-template-rows: auto 1fr auto;
        width: 300px;
    }
    ```

25. Ahora vamos a ingresar nuestro logo, primero vamos a colocar nuesta ruta, lo primero es cambiarle el nombre a la carpeta "Platzi_YardSale_Logos" y "Platzi_YardSale_Icons" por "Logos" y "Icons". 

26. despues vamos a nuestro archivo "passwordView.html" y dentro de la etiqueta `<img>` llamamos la ruta de la imagen que queremos así:
    ```html
    <img src="./logos/logo_yard_sale.svg" alt="logo" class="logo">
    ```

27. Ahora a ese logo le vamos a dar mejor tamaño en nuestro archivo "password.css", se le da display: none, para que no aparezca en desktop, para despues por medio de media queries se arregla para que aparezca solo en mobile.
    ```css
    .logo {
        width: 150px;
        margin-bottom: 50px;
        justify-self: center;
        display: none;
    }
    ```

28. Seguimos con los estilos del titulo. Lo primero es llevar a nuestro archivo "passwordView.html", los links de la fuente, traida de google fonts y en el archivo "paswword.css" copiar las variables que ya habiamos definido en el archivo "styles.css".

29. Crear las variables para las medidas de la letra.
    ```css
    :root {
        /* colores */
        --very-light-pink: #C7C7C7;
        --white: #FFFFFF;
        --text-input-field: #F7F7F7;
        --black: #000000;
        --hospital-green: #ACD9B2;
        --dark: #232830;
        /* tamaño de letras */
        --sm: 14px;
        --md: 16px;
        --lg: 18px;
    }
    ```

30. Vamos a utilizar las variables de tamaño de letra para nuestro titulo:
    ```css
    .title {
        font-size: var(--lg);
        margin-bottom: 12px;
        text-align: center;
    }
    ```

31. Seguimos con los estilos del subtitulo:
    ```css
    .subtitle {
        color: var(--very-light-pink);
        font-size: var(--md);
        font-weight: 300;
        margin-top: 0;
        margin-bottom: 30px;
        text-align: center;
    }
    ```

32. Ahora vamos a estilizar tantos los botones como los labels e inputs. Comenzamos con los labels:
    ```css
    .label {
        font-size: var(--sm);
        font-weight: bold;
        margin-bottom: 4px;
    }
    .input {
        background-color: var(--text-input-field);
        border: none;
        border-radius: 8px;
        height: 24px;
        font-size: var(--md);
        padding: 4px;
    }
    ```

33. Queremos que nuestro label quede encima de la caja del input para esto, en su contenedor escribimos el siguiente código para poder organizarlo en columnas:
    ```css
    .form {
        display: flex;
        flex-direction: column;
    }
    ```

34. Seguimos con los estilos de nuestro boton:
    ```css
    .primary-button {
        background-color: var(--hospital-green);
        border-radius: 8px;
        border: none;
        color: var(--white);
        width: 100%;
        cursor: pointer;
        font-size: var(--md);
        font-weight: bold;
        height: 50px;
    }
    ```

35. Ultimamos los estilos en cuanto a margenes
    ```css
    .login-button {
        margin-top: 14px; 
        margin-bottom: 30px;
    }
    ```
36. Por ultimo en los estilos de esta vista, vamos a hacer que en el mobile aparezca el logo, con ayuda de las media queries:
    ```css
    @media (max-width: 640px) {
        .logo{
            display: block;
        }
    }
    ```

37. Subir el trabajo realizado hasta el momento a mi repositorio remoto en GitHub. Comenzamos con la trazabilidad del proyecto en git digitando el siguiente comando, en la terminal de nuestro editor de código en la carpeta del proyecto:
    ```
    git init
    ```

38. Agregamos nuestros archivos que no han comenzado trazabiidad en git, primero verificamos los archivos con el comando:
    ```
    git status
    ```

39. Después los agregamos al stage de git con el comando:
    ```
    git add .
    ```

40. Después realizamos el commit de estos archivos:
    ```
    git commit -m "Avance primeras clases Platzi, vista cambio de password, mobile y desktop"
    ```
41. Creamos el repositorio remoto en GitHub y seguimos las instrucciones para subir nuestro repositorio local, digitando el siguiente código en nuestra terminal:
    ```
    git remote add origin https://github.com/KGISELLE/yardSalePlatzi.git
    git branch -M main
    git push -u origin main
    ```
    <br>

## Dia 2 (Vista Email enviado)

1. Para realizar la vista "emailSent" revisamos el diseño para desktop y para mobile dado.

2. Creamos un nuevo archivo "emailSent.html" para crear el maquetado de esta vista.

3. Según la [clase 7 (Email enviado)](https://platzi.com/clases/2477-frontend-developer-practico/41506-email-enviado/), podemos copiar el código que teniamos de la vista anterior "password", porque mucho de este código se puede reutilizar, lo único es depurar que elemento si coinciden y que no, y modificar algunos elementos, para así darle forma a la nueva vista.

4. Creamos el archivo "emailSent.css" para darle estilos al maquedato anterior y realizamos el mismo procedimiento copiamos los estilos de password y borramos lo que no necesitemos para la vista y modificamos lo necesario.

5. Asi solo nos falta agregar la imagen del icono del correo, el boton de Login y agregar el texto para reenviar el email, en caso de no haberlo recibido.
    ```html
    <body>
        <div class="login">
            <div class="form-container">
                <img src="./logos/logo_yard_sale.svg" alt="logo" class="logo">
                <h1 class="title">Email has been sent!</h1>
                <p class="subtitle">Please check your inbox for instructions on how to reset the password</p>

                <div class="email-image">
                    <img src="./icons/email.svg" alt="email">
                </div>

                <button class="primary-button login-button">Login</button>

                <p>
                    <span>Didn't receive the email?</span>
                    <a href="/">Resend</a>
                </p>
    
            </div>
        </div>
    </body>
    ```
    ```css
    /* estilos agregados para vista emailSent */
    .email-image {
        width: 132px;
        height: 132px;
        border-radius: 50%;
        background-color: var(--text-input-field);
        display: flex;
        justify-content: center;
        align-items: center;
        margin-bottom: 24px;
    }
    .email-image img{
        width: 80px;
    }
    .resend {
        font-size: var(--sm);
    }
    .resend span {
        color: var(--very-light-pink);
    }
    .resend a {
        color: var(--hospital-green);
        text-decoration: none;
    }
    /* Fin estilos agregados para vista emailSent */
    ```

## (Vista Login)

1. Para realizar la vista "login" revisamos el diseño para desktop y para mobile dado, y hacemos exactamente los mismos pasos de la vista anterior.

2. Creamos un nuevo archivo "login.html" para crear el maquetado de esta vista.

3. Según la [clase 8 (Login)](https://platzi.com/clases/2477-frontend-developer-practico/41507-login/), podemos copiar el código que teniamos de la vista anterior "password", porque mucho de este código se puede reutilizar, lo único es depurar que elemento si coinciden y que no, y modificar algunos elementos, para así darle forma a la nueva vista.

4. Creamos el archivo "login.css" para darle estilos al maquetado anterior y realizamos el mismo procedimiento copiamos los estilos de password y borramos lo que no necesitemos para la vista y modificamos lo necesario.

5. Asi queda nuestro código:
    ```html
    <body>
        <div class="login">
            <div class="form-container">
                <img src="./logos/logo_yard_sale.svg" alt="logo" class="logo">

                <form action="/" class="form">
                    <label for="email" class="label">Email address</label>
                    <input type="text" name="" id="email" placeholder="emaildeprueba@email.com" class="input input-password">

                    <label for="password" class="label"> Password</label>
                    <input type="password" name="" id="new-password" placeholder="************" class="input input-password">

                    <input type="submit" value="Login" class="primary-button login-button">

                    <a href="/">Forgot my password</a>
                </form>

                <button class="secondary-button signup-button">Sign up</button>
            </div>
        </div>
    </body>
    ```
    ```css
    /* agregado para vista login */
    .form a {
        color: var(--hospital-green);
        font-size: var(--sm);
        text-align: center;
        text-decoration: none;
        margin-bottom: 52px;
    }
    /* Fin agregado para vista login */
    /* agregado para vista login */
    .input-email {
        margin-bottom: 22px;    
    }
    /* Fin agregado para vista login */
    /* agregado para vista login */
    .secondary-button {
        background-color: var(--white);
        border-radius: 8px;
        border: 1px solid var(--hospital-green);
        color: var(--hospital-green);
        width: 100%;
        cursor: pointer;
        font-size: var(--md);
        font-weight: bold;
        height: 50px;
    }
    /* Fin agregado para vista login */
    @media (max-width: 640px) {
        .logo{
            display: block;
        }
        /* agregado para vista login */
        .secondary-button {
            position: absolute;
            top: 90%;
            width: inherit;
        }
        /* Fin agregado para vista login */
    }
    ```

## Dia 3 (Vista crear cuenta)

1. Para realizar la vista "crear cuenta" revisamos el diseño para desktop y para mobile dado, y hacemos exactamente los mismos pasos de la vista anterior.

2. Creamos un nuevo archivo "createAccount.html" para crear el maquetado de esta vista.

3. Según la [clase 9 (Crear y editar mi cuenta)](https://platzi.com/clases/2477-frontend-developer-practico/41508-crear-y-editar-mi-cuenta/), podemos copiar el código que teniamos de la vista  "password", porque mucho de este código se puede reutilizar, lo único es depurar que elemento si coinciden y que no, y modificar algunos elementos, para así darle forma a la nueva vista.

4. Creamos el archivo "createAccount.css" para darle estilos al maquetado anterior y realizamos el mismo procedimiento copiamos los estilos de password y borramos lo que no necesitemos para la vista y modificamos lo necesario.

5. Para separar el boton de Create del resto del form en la vista mobile en el video se muestra una forma de realizarlo, que es dividiendo el form en un div aparte del button para que queden en contenedores distintos y con la ayuda de display: flex, situamos el div en la parte superior y el button en la parte inferior, detalle del código a continuación:

    ```html
    <body>
        <div class="login">
            <div class="form-container">
                <h1 class="title">My account</h1>

                <form action="/" class="form">
                    <div>
                        <label for="name" class="label">Name</label>
                        <input type="text" name="" id="name" placeholder="Camila Yokoo" class="input input-name">
        
                        <label for="email" class="label">Email address</label>
                        <input type="email" name="" id="email" placeholder="camilayokoo@gmail.com" class="input input-email">
                        
                        <label for="password" class="label">Password</label>
                        <input type="password" name="" id="password" placeholder="************" class="input input-password">
                    </div>

                    <input type="submit" value="Create" class="primary-button login-button">
                </form>
            </div>
        </div>
    </body>
    ```

6. Y para el CSS, modificamos lo siguiente:
    ```css
    .title {
    font-size: var(--lg);
    /* Modificado para vista createAccount */
    margin-bottom: 40px;
    text-align:start;
    }
    /* agregado para vista createAccount */
    .form div {
        display: flex;
        flex-direction: column;
    }
    /* Fin agregado para vista createAccount */
    /* agregado para vista createAccount */
    .input-name, 
    .input-email,
    .input-password {
        margin-bottom: 22px;
    }
    /* Fin agregado para vista createAccount */
    /* agregado para vista createAccount */
    @media (max-width: 640px) {
        .form-container {
            height: 100%;
        }
        .form {
            height: 100%;
            justify-content: space-between;
        }
    }
    /* Fin agregado para vista createAccount */

## (Vista EditAccount)

1. Para realizar la vista "editar cuenta" revisamos el diseño para desktop y para mobile dado, y hacemos exactamente los mismos pasos de las vistas anteriores.

2. Creamos un nuevo archivo "editAccount.html" para crear el maquetado de esta vista.

3. Según la [clase 10 (editar - mi cuenta)](https://platzi.com/clases/2477-frontend-developer-practico/41509-mi-cuenta/), podemos copiar el código que teniamos de la vista  "createAccount", porque mucho de este código se puede reutilizar, lo único es depurar que elementos si coinciden y que no, y modificar algunos elementos, para así darle forma a la nueva vista.

4. Creamos el archivo "editAccount.css" para darle estilos al maquetado anterior y realizamos el mismo procedimiento copiamos los estilos de password y borramos lo que no necesitemos para la vista y modificamos lo necesario.

5. Hay que cambiar el boton de primary a secondary y los inputs cambian por textos, cambiando los inputs por párrafos, quedando el código así:
    ```html
    <body>
        <div class="login">
            <div class="form-container">
                <h1 class="title">My account</h1>

                <form action="/" class="form">
                    <div>
                        <label for="name" class="label">Name</label>
                        <p class="value">Camila Yokoo</p>
        
                        <label for="email" class="label">Email address</label>
                        <p class="value">camilayokoo@gmail.com</p>
                        
                        <label for="password" class="label">Password</label>
                        <p class="value">************</p>
                    </div>

                    <input type="submit" value="Edit" class="secondary-button login-button">
                </form>
            </div>
        </div>
    </body>
    ```

    ```css
    /* agregado para vista editAccount */
    .value {
        color: var(--very-light-pink);
        font-size: var(--md);
        margin: 8px 0px 32px 0px;
    }
    /* Fin agregado para vista editAccount */

    /* Modificado para vista editAccount */
    .secondary-button {
        background-color: var(--white);
        border-radius: 8px;
        border: 1px solid var(--hospital-green);
        color: var(--hospital-green);
        width: 100%;
        cursor: pointer;
        font-size: var(--md);
        font-weight: bold;
        height: 50px;
    }
    /* Fin Modificado para vista editAccount */
    ```
***NOTA: Hasta aquí se han creado las vistas de autenticación, ahora crearemos las vistas principales.***

<br>

## Vista Principal - Inicio

1. Lo primero para crear esta vista main, es comenzar por el crear el archivo "mainView.html" para crear el maquetado de esta vista.

2. Según la [clase 11 (Página de inicio: HTML)](https://platzi.com/clases/2477-frontend-developer-practico/41510-pagina-de-inicio-html/), pegamos los links de google font que ya habiamos utilizado en otras vistas, y tambien realizamos el enlace a una hoja de estilos para esta vista.

3. Creamos el archivo "mainView.css" para darle estilos al maquetado anterior y realizamos el mismo procedimiento pegando las variables de las vistas anteriores.

4. Para comenzar a crear las cards con las imagenes , creamos una etiqueta `<section>` dentro de `<body>`.
    ```html
    <body>
        <section class="main-container">
            <div class="card-container">

                <!-- esquema card -->
                <div class="product-card">
                    <img src="" alt="" class="product">
                    <div>
                        <p>$120,00</p>
                        <p>Bike</p>
                    </div>
                    <figure>
                        <img src="./icons/bt_add_to_cart.svg" alt="">
                    </figure>
                </div>
                <!-- esquema card -->
                
            </div>
        </section>
    </body>
    ```

5. Ya teniendo el esquema de una card copiamos este código y lo replicamos cuantas veces lo necesitemos.

6. Ahora vamos a buscar las imagenes para los productos, las podemos decargar de [www.pixels.com](https://www.pexels.com/es-es/), copiando la url de la imagen (click derecho > copiar dirección de imagen) y la pegamos en la src de la etiqueta `<img>`.

7. Ahora le daremos los estilos a nuestra "mainView" en el archivo "mainView.css", seguimos indicaciones de la [clase 12 (Página de inicio: CSS)](https://platzi.com/clases/2477-frontend-developer-practico/41511-pagina-de-inicio-css/).

8. Así queda nuestro código en html y css:
    ```html
    <body>
        <section class="main-container">
            <div class="cards-container">

                <div class="product-card">
                    <img src="https://images.pexels.com/photos/276517/pexels-photo-276517.jpeg?auto=compress&cs=tinysrgb&dpr=2&w=500" alt="" class="product">
                    <div class="product-info">
                        <div>
                            <p>$120,00</p>
                            <p>Bike</p>
                        </div>
                        <figure>
                            <img src="./icons/bt_add_to_cart.svg" alt="">
                        </figure>
                    </div>
                </div>

                <!-- Repeticiún de product-card cuantas veces se necesite -->
                <div class="product-card">...
                </div>
                
            </div>
        </section>
    </body>
    ```

    ```css
    :root {
    /* colores */
    --very-light-pink: #C7C7C7;
    --white: #FFFFFF;
    --text-input-field: #F7F7F7;
    --black: #000000;
    --hospital-green: #ACD9B2;
    --dark: #232830;
    /* tamaño de letras */
    --sm: 14px;
    --md: 16px;
    --lg: 18px;
    /* Tamaño de las cards*/
    --card-size: 210px;
    }
    body {
        font-family: 'Quicksand', sans-serif;
        margin: 0;
    }

    .cards-container {
        display: grid;
        grid-template-columns: repeat(auto-fill, var(--card-size));
        gap: 26px;
        place-content: center;
    }
    .product-card {
        width: var(--card-size);
    }
    .product-card img{
        width: var(--card-size);
        height: var(--card-size);
        border-radius: 20px;
        object-fit: cover;
    }
    .product-info {
        display: flex;
        justify-content: space-between;
        align-items: center;
        margin-top: 12px;
    }
    .product-info figure{
        margin: 0;
        display: flex;
    }
    .product-info figure img{
        width: 40px;
        height: 40px; 
    }
    .product-info div p:nth-child(1){
        font-weight: bold;
        font-size: var(--md);
        margin-top: 0;
        margin-bottom: 4px;
    }
    .product-info div p:nth-child(2){
        font-size: var(--sm);
        margin-top: 0;
        margin-bottom: 0;
        color: var(--very-light-pink);
    }

    @media(max-width: 640px) {
        .cards-container {
            grid-template-columns: repeat(auto-fill, 140px);
        }
        .product-card {
            width: 140px;
        }
        .product-card img{
            width: 140px;
            height: 140px;
        }
    }
    ```