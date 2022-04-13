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

39. Despues los agregamos al stage de git con el comando:
    ```
    git add .
    ```
38. Creamos el repositorio remoto en GitHub y seguimos las instrucciones para subir nuestro repositorio local, digitando el siguiente código en nuestra terminal:
    ```
    git remote add origin https://github.com/KGISELLE/yardSalePlatzi.git
    git branch -M main
    git push -u origin main
    ```
