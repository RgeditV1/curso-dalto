># <strong>Este Repositorio es para mostrar mi avance en HTML y CSS por ahora</strong>
----
### Contenido Multimedia en HTML
```html
<!DOCTYPE html>
<html>

  <head>

  </head>

  <body>
    <h1>Mi Pagina Web</h1>
    <img src="/imgs/dev.jpg"><br>
    <video src="/src/vid.mp4" controls></video>
    <audio src="/src/vid.mp4" controls></audio>
  </body>
<!--con el atributo controls, le asignamos al audio o video
  los controles como el boton de reproducir, el timeline etc..
-->

</html>
```



### Formularios en HTML
```html
<form>
    <input type="text" name=""> <!--tipo texto-->
    <input type="password" name="" required><!--tipo contraseña-->
    <input type="number" name=""><!--tipo opcion/numerico-->
    <input type="email" name="" required><!--tipo email-->
    <input type="color" name=""><!--tipo selector colores-->
    <input type="range" min="1" max="5"><!--tipo rango numerico-->
    <input type="date" name=""><!--tipo Fecha-->
    <input type="time"><!--tipo Hora-->
    <input type="button" value="ok"><!--tipo boton-->
    <input type="submit" value="SUBMIT"><!--tipo boton de envio de formulario-->
    <textarea readonly>Buenas</textarea> <!--tipo compo de texto-->
</form>
```

+ El atributo <strong>value</strong> le añade el valor a los botones
+ El atributo <strong>Required</strong> hace que sea requerido para el boton submit (OJO es mejor usarlo desde el backend o servidor)
+ Los atributo <strong>Required/Value</strong> son opocionales
+ El atributo <strong>Readonly</strong> hace que solo podamos ver y no escribir
+ El text area tambien funciona con el buttom submit
