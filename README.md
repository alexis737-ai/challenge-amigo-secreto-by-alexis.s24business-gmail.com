# challenge-amigo-secreto-by-alexis.s24business-gmail.com
amigo secreto by alexis.s24business@gmail.com

# Amigo Secreto - Página Web

## Descripción
Este proyecto es una página web diseñada para organizar un sorteo de "Amigo Secreto". Permite a los usuarios ingresar nombres de amigos, almacenarlos en una lista y realizar un sorteo aleatorio para determinar quién es el amigo secreto de cada participante.

## Estructura del proyecto
El proyecto se compone de tres archivos principales:
1. **index.html**: Contiene la estructura HTML de la página.
2. **style.css**: Define el diseño y los estilos visuales de los elementos de la página.
3. **app.js**: Incluye las funciones y lógica en JavaScript para añadir interactividad.

---

## Explicación de cada archivo

### 1. index.html
- **Propósito**: Define la estructura básica de la página web.
- **Componentes principales**:
  - Título de la página: `Amigo Secreto`.
  - Campo de entrada para que los usuarios ingresen nombres.
  - Listas dinámicas:
    - `#listaAmigos`: Muestra los nombres añadidos.
    - `#resultado`: Muestra el nombre del amigo secreto sorteado.
  - Botones interactivos:
    - `Añadir`: Llama a la función `agregarAmigo()` para añadir un nombre.
    - `Sortear amigo`: Llama a la función `sortearAmigo()` para realizar el sorteo.

---

### 2. style.css
- **Propósito**: Proporciona estilos para mejorar la apariencia de la página.
- **Incluye**:
  - Fuentes personalizadas de Google Fonts (`Inter` y `Merriweather`).
  - Estilo para botones, campos de entrada y listas.

---

### 3. app.js
- **Propósito**: Implementa la lógica para añadir nombres, almacenarlos en una lista y realizar el sorteo.
- **Funciones principales**:
  - `agregarAmigo()`: Añade un nombre ingresado al array de amigos, siempre que sea válido y no duplicado.
  - `actualizarListaAmigos()`: Actualiza la lista visible en la página con los nombres ingresados.
  - `sortearAmigo()`: Realiza un sorteo aleatorio y muestra el resultado en pantalla.

---

## Cómo usar la página
1. Abre el archivo `index.html` en un navegador web.
2. Ingresa los nombres de los participantes en el campo de texto y presiona el botón "Añadir".
3. Verifica que todos los nombres aparezcan en la lista.
4. Presiona el botón "Sortear amigo" para seleccionar aleatoriamente un nombre.
5. El resultado se mostrará en la lista de "resultado".

---

## Mejoras sugeridas
1. **Validación**: Agregar manejo de errores para evitar nombres vacíos o sortear con menos de dos participantes.
2. **Diseño**: Ajustar los estilos en `style.css` para una experiencia más atractiva.
3. **Persistencia de datos**: Implementar almacenamiento local (`localStorage`) para mantener los nombres si se recarga la página.

---

## Créditos
Desarrollado con HTML, CSS y JavaScript.

---

