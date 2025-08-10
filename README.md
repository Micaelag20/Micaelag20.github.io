<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <title>Portafolio Web</title>
    <style> body {
  background-color: rgb(41, 172, 212);
  font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
  margin: 0;
  padding: 0;
}
.contenido {
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 20px;
  gap: 20px;
}
.imagen-izquierda img {
  width: 260px;
  height: auto;
  border-radius: 10px;
}
.contenido-central {
  text-align: center;
  flex-grow: 1;
}
.imagen-central {
  width: 200px;
  height: 200px;
  object-fit: cover;
  border-radius: 60%;
  margin-bottom: 10px;
}
h1, p {
  background-color: rgb(82, 221, 221);
  color: black;
  padding: 10px;
  margin: 10px auto;
  max-width: 500px;
}
.imagen-derecha img {
  width: 260px;
  height: auto;
  border-radius: 10px;
}
#información { 
    background-color: rgb(160, 227, 231);
    padding: 15px;
}</style>
</head>
<body>
    <div class="contenido">
        <div class="imagen-izquierda" id="imagen-izquierda">
            <img src="imagenlat1.jpg.png" alt="Imagen izquierda">
        </div>
        <div class="contenido-central" id="información">
            <img src="Mica.jpg.jpg" alt="Foto de Mica" class="imagen-central">
            <h1>Hola! Mi nombre es Micaela Gómez y tengo 26 años. 😁</h1>
            <p>
                Soy profesora de Educación Física con orientación en Deporte. Actualmente dicto clases en primaria. </p>
                <p>
Durante la realización de la tesina en la universidad, tuve un primer acercamiento al lenguaje Python, lo que despertó en mí un gran interés por el mundo de la programación, motivándome a comenzar a formarme en esta área.
            </p>
        </div>
        <div class="imagen-derecha">
            <img src="imagenlat2.jpg" alt="Imagen derecha">
        </div>
    </div>

</body>
</html>
