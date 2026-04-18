### Prompt para generar el prompt para el agente de cursor 

Genérame un prompt para que Cursor, a partir de dos imágenes, me genere una aplicación web de una ruleta de la suerte. Debe tener un indicador fijo en la parte superior.

Las imágenes son: una es el logo de mi empresa llamado logo.PNG, y la otra es una ruleta de color rojo que quiero usar únicamente como referencia llamada ruleta_ejemplo.png, ya que todo debe ser generado por código.

Quiero que el color predominante sea el azul rey #042c93. El resultado de la ruleta debe ser completamente aleatorio y, al finalizar, se debe mostrar un modal dinámico con el label y la descripción de lo que se ganó. El label es lo que se muestra dentro de la ruleta.

Además, la aplicación debe ser responsive y la ruleta debe verse lo más grande posible en todas las pantallas, pensada principalmente para verse muy bien en dispositivos móviles.

En la parte superior, solo quiero un banner con el nombre del restaurante 'Sinaloa Restaurant', que combine con el azul rey.

Y todo sera detonado por un boton inferior que diga Girar!

la ruleta debe tener el logotipo en el centro y este no debe moverse

usando html css y javascipt puro sin librerias agrupando todo en 1 solo archivo html


### Prompt para realizar la pagina web
Quiero que generes una aplicación web completa en un solo archivo HTML (incluyendo HTML, CSS y JavaScript en el mismo archivo, sin usar librerías externas).

### Objetivo
Crear una ruleta de la suerte interactiva, visualmente atractiva, completamente generada por código (NO usar imágenes para la ruleta en sí).

### Recursos disponibles
- Una imagen llamada "logo.png" → usarla centrada dentro de la ruleta (no debe girar).
- Una imagen llamada "ruleta_ejemplo.png" → usarla únicamente como referencia visual (NO debe ser utilizada directamente).

### Requerimientos funcionales

1. Ruleta
- La ruleta debe estar compuesta por múltiples segmentos (mínimo 8, idealmente 10–12).
- Cada segmento debe tener:
  - Un "label" (texto visible dentro de la ruleta).
  - Una "description" (texto adicional que se mostrará después).
- La ruleta debe girar al presionar un botón.
- El resultado debe ser completamente aleatorio.
- La ruleta es la única que gira, el puntero NO se mueve.

2. Indicador (puntero)
- Debe estar fijo en la parte superior de la ruleta.
- Visualmente claro para indicar el resultado final.

3. Centro de la ruleta
- Debe contener el logo ("logo.png").
- El logo NO debe rotar junto con la ruleta.

4. Resultado
- Al terminar el giro:
  - Mostrar un modal dinámico.
  - El modal debe mostrar:
    - El label (premio ganado).
    - La description correspondiente.
- El modal debe poder cerrarse fácilmente.

5. Botón
- Ubicado en la parte inferior.
- Texto: "¡Girar!"
- Debe detonar la animación de la ruleta.

### Requerimientos de diseño

- Color principal: azul rey #042c93.
- Estilo moderno, limpio y atractivo.
- El banner superior debe mostrar:
  - Texto: "Sinaloa Restaurant"
  - Debe combinar visualmente con el color principal.
- La ruleta debe ocupar el mayor espacio posible en pantalla.

### Responsive Design

- Debe estar optimizada principalmente para dispositivos móviles.
- Debe escalar correctamente en diferentes tamaños de pantalla.
- La ruleta debe mantenerse centrada y lo más grande posible sin romper layout.

### Detalles técnicos

- Usar solo:
  - HTML
  - CSS
  - JavaScript puro (vanilla JS)
- No usar frameworks ni librerías (no React, no Tailwind, no Bootstrap).
- Usar <canvas> o manipulación del DOM/CSS para generar la ruleta dinámicamente.
- La animación debe ser suave (usar easing si es posible).
- Evitar resultados predecibles (usar Math.random correctamente).
- Separar claramente:
  - Datos de segmentos
  - Lógica de giro
  - Renderizado

### Bonus (si puedes incluirlo)
- Animación de desaceleración progresiva.
- Efecto visual al caer en el resultado.
- Sombra o profundidad en la ruleta.
- Transición suave del modal.

### Output esperado
Devuélveme un único archivo HTML completamente funcional, listo para abrirse en el navegador sin dependencias externas.


En lugar de 12 segmentos solamente es necesario que sean 8 ademas necesito que corrigas el hecho de que el boton no esta justo abajo de la ruleta en conjunto con la visualizacion de los label ya que estan mal orientados, de manera horizontal y en algunos segmentos ni siquiera se ven 

Mejor pero se ven raros los textos como si estubieran escritos alreves como se se voltearan las letras de la ruleta y eliminaste el color azul de el banner que me gustaba, ademas pudieras cambiar el color de fondo por algo mas adoc ya que se ve bastante sin chiste

Pudieras hacer un poco mas hacia arriba la ruleta y un poco hacia abajo el boton, ademas al cargar la pagina se ve de manera correcta los textos pero cuando gira se desacomodan, noto que estas tratando de dejarlos legibles independientemente del segmento, no me molestaria que rotaran y que el de abajo estubiera normal pero de cabeza como en una ruleta fisica, pudieras corregir este comportamiento y asgurarte de que no se desconfigure la orientacion de los label en la ruleta