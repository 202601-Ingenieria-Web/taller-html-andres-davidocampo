# 🔍 PokéApp Pro - Explorador Avanzado de Pokémon

¡Bienvenido a la **PokéApp Pro**! Este proyecto es una aplicación web interactiva diseñada para explorar el vasto mundo de Pokémon utilizando la [PokéAPI](https://pokeapi.co/). El objetivo principal es ofrecer una experiencia de usuario fluida, visualmente atractiva y con funcionalidades de búsqueda inteligente.

---

## 🚀 Características Principales (Innovación y Creatividad)

Este proyecto va más allá de un listado simple, integrando características avanzadas:

- **Búsqueda por Coincidencia Parcial:** A diferencia de las búsquedas estándar, nuestra app permite encontrar Pokémon escribiendo solo una parte del nombre (ej: "char" devuelve a Charmander, Charmeleon y Charizard).
- **Interfaz Temática Dinámica:** El fondo de la aplicación simula una Pokébola gigante, y las tarjetas de cada Pokémon cambian su color de fondo automáticamente según su **Tipo Principal** (Fuego, Agua, Planta, etc.).
- **Ficha de Detalles (Modal Robusto):** Al hacer clic en un Pokémon, se despliega una Pokédex detallada que incluye:
  - **Galería de Formas:** Imágenes frontales, de espalda y versiones **Shiny** (variocolor) con efectos visuales.
  - **Estadísticas:** Gráficos de barras animados que muestran PS, Ataque, Defensa, etc.
  - **Datos Biométricos:** Peso, altura, experiencia base y habilidades.
- **Diseño Responsivo:** Optimizado para funcionar perfectamente en computadoras, tablets y dispositivos móviles.

---

## 🛠️ Tecnologías Utilizadas

Para el desarrollo de este taller se utilizaron tecnologías estándar de la web sin librerías externas para demostrar el dominio de los fundamentos:

1.  **HTML5:** Estructura semántica de la aplicación.
2.  **CSS3:** \* Uso de **Flexbox** y **Grid Layout** para la responsividad.
    - **Animaciones Avanzadas** (`@keyframes`) para la entrada de tarjetas y llenado de barras.
    - Variables CSS para la gestión de estados dinámicos.
3.  **JavaScript (ES6+):**
    - **Fetch API:** Para el consumo asíncrono de datos.
    - **Promesas (Async/Await):** Para manejar múltiples peticiones de forma eficiente.
    - **Métodos de Arreglos (`filter`, `map`):** Para la lógica de búsqueda y transformación de datos.

---

## 📖 Instrucciones de Uso

1.  **Carga Inicial:** Al abrir la página, se cargarán automáticamente los primeros 12 Pokémon de la región.
2.  **Búsqueda:** Escribe en el buscador el nombre o los caracteres del Pokémon que deseas encontrar y presiona "Enter" o el botón "Buscar".
3.  **Explorar Detalles:** Haz clic sobre cualquier tarjeta para abrir la ficha técnica.
4.  **Cerrar Detalles:** Puedes cerrar la ficha haciendo clic en la "X", presionando la tecla `ESC` o haciendo clic fuera del recuadro blanco.
5.  **Reiniciar:** El botón "Reiniciar" permite volver a la lista inicial de 12 Pokémon rápidamente.

---

## 📝 Estructura del Proyecto

```text
/
├── PokeApi.html      # Archivo único que contiene HTML, CSS y JS.
└── README.md       # Documentación del proyecto (este archivo).
```
