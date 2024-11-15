# Chat Estilo WhatsApp

Este proyecto es una simple aplicación de chat con un estilo inspirado en WhatsApp. Permite que los usuarios envíen mensajes, y el sistema responde de manera predeterminada según la longitud del mensaje. La página utiliza HTML, CSS y JavaScript para crear una experiencia interactiva en el navegador.

## Características

- **Interfaz de usuario similar a WhatsApp**: La interfaz tiene una barra superior, una caja de mensajes y un área de entrada de texto.
- **Respuestas del bot**: El sistema responde con diferentes mensajes según la longitud del mensaje enviado por el usuario.
  - Mensaje corto (menos de 10 caracteres): Responde con "¡Hola!"
  - Mensaje medio (entre 10 y 14 caracteres): Responde con "¡Adiós!"
  - Mensaje largo (entre 15 y 24 caracteres): Responde con "¡OK!"
  - Mensaje muy largo (más de 25 caracteres): Responde con "¡Buenas!"
- **Desvanecimiento progresivo**: Cada vez que el usuario envía un mensaje, la opacidad de la página disminuye lentamente, creando un efecto visual atractivo.
- **Desplazamiento automático**: La ventana de chat se desplaza automáticamente hacia abajo para mostrar el mensaje más reciente.

## Tecnologías utilizadas

- **HTML**: Estructura básica del chat.
- **CSS**: Estilos visuales para crear la apariencia del chat.
- **JavaScript**: Lógica para manejar la interacción con el usuario, la respuesta del bot y los efectos visuales.

## Instalación

1. Clona este repositorio o descarga el archivo `index.html`.
2. Abre el archivo `index.html` en tu navegador preferido.

## Uso

1. Escribe un mensaje en el área de texto.
2. Haz clic en el botón de enviar (▶).
3. El bot responderá según la longitud de tu mensaje.
4. La opacidad de la página disminuirá ligeramente con cada mensaje enviado.

## Personalización

Puedes modificar los siguientes aspectos para adaptar la experiencia a tus necesidades:

- **Respuestas del bot**: Modificar los mensajes predeterminados que el bot envía según la longitud del mensaje del usuario.
- **Estilo visual**: Cambiar los colores, fuentes y diseño en la sección de CSS.
- **Efectos de opacidad**: Ajustar el valor de la opacidad y el comportamiento visual de la página.

## Contribuciones

Las contribuciones son bienvenidas. Si tienes mejoras o correcciones para este proyecto, siéntete libre de hacer un *pull request*.

## Licencia

Este proyecto está bajo la Licencia MIT. Consulta el archivo [LICENSE](LICENSE) para más detalles.
