<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>¿Me perdonas?</title>
</head>
<body>
<h1>¿Me perdonas?</h1>
<input type="text" id="respuesta" placeholder="Escribe 'sí' para perdonar">
<button onclick="verificarRespuesta()">Enviar</button>
<p id="mensaje"></p>

<script>
function verificarRespuesta() {
    var respuesta = document.getElementById("respuesta").value.toLowerCase();
    var mensaje = document.getElementById("mensaje");
    
    if (respuesta === "sí") {
        mensaje.textContent = "¡Gracias! Sabía que lo harías, por eso te quiero mucho.";
    } else {
        mensaje.textContent = "Lo siento, solo puedo aceptar 'sí'.";
    }
}
</script>
</body>
</html>


<!---
Crisdaesye23/Crisdaesye23 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
