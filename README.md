# trabajo-de-estudio-2
Modificacion
<!DOCTYPE html>
  <html>
    <head>
      <meta charset="utf-8">
      <meta name="viewport" content="width:device-width, user-scalable=no, initial-scale=1">
      <link rel="stylesheet" href="css/estilos.css">
      <title>Scarlet Foto Estudio</title>
    </head>
    <body>
      <div id=contenido>
        <header>
      <div id="title">
        <h2>Comenzando Con Los Paisajes</h2>
      </div>
      <nav>
        <ul>
          <li><a href="Inicio.html">Incio</a></li>
          <li><a href="Paisajes.html">Paisajes</a></li>
          <li><a href="Retratos.html">Retratos</a></li>
        </ul>
      </nav>
      </header>
        <section class="fila">
        <article id="Img_1">
         <figure>
          <img src="imagenes/img02.jpeg"width="300px" height="300px">
            <p>Imagen. No. 1</p>
         </figure>
        </article>
        <article id="Img_2">
          <figure>
            <img src="imagenes/img02.jpeg" width="300px" height="300px">
            <p>Imagen. No. 2</p>
          </figure>
        </article>
        <article id="Img_3">
          <figure>
          <img src="imagenes/img02.jpeg"width="300px" height="300px">
            <p>Imagen. No. 3</p>
          </figure>
        </article>
        </section>
        <section class="fila_2">
        <article id="Img_4">
          <figure>
          <img src="imagenes/img02.jpeg"width="300px" height="300px">
             <p>Imagen. No. 4</p>
          </figure>
        </article>
        <article id="Img_5">
          <figure>
            <img src="imagenes/img02.jpeg"width="300px" height="300px">
              <p>Imagen. No. 5</p>
          </figure>
        </article>
        <article id="Img_6">
            <figure>
            <img src="imagenes/img02.jpeg"width="300px" height="300px">
              <p>Imagen. No. 6</p>
            </figure>
        </article>
        </section>
      <footer>
        <section id="information">
        <article>
              <h2>Contacto</h2>
                <p>el_leon64@live.com</p>
                <p>Calle/ Pedro Felix Contreras #268.</p>
                <p>Tel:809-587-7206</p>
        </article>
        <article>
              <h2>Terminos</h2>
                <p>Conoce nuestros terminos y condiciones.</p>
        </article>
        <article>
              <h2>Redes Sociales</h2>
                <p>Comparte en nuestras redes</p>
            <p><img src="imagenes/facebook.png" width="20px" height="20px">Luis Rosario</p>
        </article>
        <article>
              <h2>Derechos</h2>
                <p>&copy; 2017 Luis J Rosario.</p>
        </article>
        </section>
          </footer>
      </div>
    </body>
<html>
codigo para la pagina de retratos
<!DOCTYPE html>
  <html>
    <head>
      <meta charset="utf-8">
      <meta name="viewport" content="width:device-width, user-scalable=no, initial-scale=1">
      <link rel="stylesheet" href="css/estilos.css">
      <title>Retratos</title>
    </head>
    <body>
      <div id=contenido>
        <header>
      <div id="title">
        <h2>Comenzando Con Los Retratos</h2>
      </div>
      <nav>
        <ul>
          <li><a href="Inicio.html">Incio</a></li>
          <li><a href="Paisajes.html">Paisajes</a></li>
          <li><a href="Retratos.html">Retratos</a></li>
        </ul>
      </nav>
      </header>
      <section class="fila">
      <article id="Img_1">
       <figure>
        <img src="imagenes/img02.jpeg"width="300px" height="300px">
          <p>Imagen. No. 1</p>
       </figure>
      </article>
      <article id="Img_2">
        <figure>
          <img src="imagenes/img02.jpeg" width="300px" height="300px">
          <p>Imagen. No. 2</p>
        </figure>
      </article>
      <article id="Img_3">
        <figure>
        <img src="imagenes/img02.jpeg"width="300px" height="300px">
          <p>Imagen. No. 3</p>
        </figure>
      </article>
      </section>
      <section class="fila_2">
      <article id="Img_4">
        <figure>
        <img src="imagenes/img02.jpeg"width="300px" height="300px">
           <p>Imagen. No. 4</p>
        </figure>
      </article>
      <article id="Img_5">
        <figure>
          <img src="imagenes/img02.jpeg"width="300px" height="300px">
            <p>Imagen. No. 5</p>
        </figure>
      </article>
      <article id="Img_6">
          <figure>
          <img src="imagenes/img02.jpeg"width="300px" height="300px">
            <p>Imagen. No. 6</p>
          </figure>
      </article>
      </section>
          <footer>
        <section id="information">
        <article>
              <h2>Contacto</h2>
                <p>el_leon64@live.com</p>
                <p>Calle/ Pedro Felix Contreras #268.</p>
                <p>Tel:809-587-7206</p>
        </article>
        <article>
              <h2>Terminos</h2>
                <p>Conoce nuestros terminos y condiciones.</p>
        </article>
        <article>
              <h2>Redes Sociales</h2>
                <p>Comparte en nuestras redes</p>
                <p><img src="imagenes/facebook.png" width="20px" height="20px">Luis Rosario</p>
        </article>
        <article>
              <h2>Derechos</h2>
                <p>&copy; 2017 Luis J Rosario.</p>
        </article>
        </section>
          </footer>
      </div>
    </body>
<html>
estilos css
body {
font-family: 'Dancing Script', cursive;
background-color: #02010a;
}

#contenido {
width: 100%;
flex-flow: row wrap;
background-color: #82c3a6;
alignment-adjust: central;
margin: 0 auto;
border-radius: 10px;
}

@media all and (min-width:900px) {
#contenido {
width: 900px
}
}
/*inicio header*/

img {
box-shadow: 2px 2px #02010a
}

header {
animation-duration: 1s;
animation-name: slidein;
}

@keyframes slidein {
0% {
margin-top: 150%;
}

60% {
margin-top: -5%;
}

100% {
margin-top: 0%;
}

}

header {
background-color: #5b7989;
border-radius: 10px 10px 0 0;
width: 100%;
text-align: center;
}

header #title {
width: 45%;
float: left;
padding-left: 10%;
text-align: left
}

header #title h1 {
text-shadow: 2px 2px #02010a;
color: white;
display: block;
}

header ul {
list-style-type:none;
display: inline-block;
}

li {
list-style-type: none;
padding: 10px 10px;
display: inline-block;
}

a {
text-decoration:underline;
color: white;
font-size: 20px;
}


#img_central {
background-color: #82c3a6;
width: 100%;

}

#img_central article {
text-align: center;
}

#img_central img {
width: 80%;
margin: 10px 20px;

}

#submenu {
background-color: #d5c75f;
border: 1px;
width: 100%;
display: flex;
flex-direction: row;
text-align: center;
}

#submenu p {
font-size: 20px;
text-decoration: underline;
}

#submenu img {
margin: 10px 25px;
height: 70%;
width: 70%;
}

#submenu .paisajes img {
transition-property: all;
transition-duration: 1s;
}

#submenu .paisajes img:hover {
transform: rotate(10deg);
box-shadow: 2px 2px #82c3a6;
}

#submenu .retratos img {
transition-property: all;
transition-duration: 1s
}

#submenu .retratos img:hover {
transform: translate(20px, -5px);
box-shadow: 2px 2px #82c3a6;
}

.fila {
background-color: #d5c75f;
border: 1px;
width: 100%;
display: flex;
text-align: center;
}

.fila p {
font-size: 20px;
text-decoration: underline;
}

.fila img {
margin: 10px 25px;
height: 70%;
width: 70%;
}

#Img_1 {
filter: blur(6px);
}

#Img_2 {
-webkit-filter: grayscale(100%);
}

#Img_3 {
-webkit-filter: sepia(90%);
}

#Img_4 {
-webkit-filter: grayscale(100%);
}

#Img_6 {
-webkit-filter: grayscale(100%);
}

.fila_2 {
background-color: #d5c75f;
border: 1px;
width: 100%;
display: flex;
flex-direction: row;
text-align: center;
}

.fila_2 p {
font-size: 20px;
text-decoration: underline;
}

.fila_2 img {
margin: 10px 25px;
height: 70%;
width: 70%;
}


footer {
background-color: #C6d5c5;
border-bottom-left-radius: 10px;
border-bottom-right-radius: 10px
}

#information{
display: inline-block;
display: flex;
font-size: 18px;
}

#information article{
padding:0 0 0 20px;
}

#information img{
width: 20px;
box-shadow: 0 0;
}

}
