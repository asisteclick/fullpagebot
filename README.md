# Fullpage Bot
Bot en página completa, institucional

Este script permite desplegar un chatbot en página completa dentro de una URL de la empresa. Por ejemplo, si tu dominio es `https://www.empresa.com` y quieres ejecutar el chatbot de Ventas en página completa pero dentro de la URL interna `https://www.empresa.com/ventasbot` lo que debes realizar es:

1) Crea la página `ventasbot` dentro de tu dominio web www.empresa.com
2) Copia en `ventasbot` el contenido del archivo `index.html`
3) Reemplaza el atributo `src` del iframe `chatbot` por la URL de tu bot de AsisteClick

    <iframe id="chatbot" src="https://app.asisteclick.com/V2/request.php?id=asisteclick-11&deptid=0&pagex=fullpagebot&hashbot=agents"></iframe>


