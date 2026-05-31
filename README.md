# 🎱 Interactive JS Bingo Game (Juego del Bingo)

Un motor algorítmico y visual para el juego interactivo del Bingo en la web, desarrollado en **JavaScript puro (ES6+)**. Implementa una lógica matemática sólida para el sorteo de esferas aleatorias sin repetición, la gestión de cartones de jugadores y la validación en tiempo real de líneas y Bingo.

[![JavaScript](https://img.shields.io/badge/JavaScript-ES6+-yellow?style=flat-square&logo=javascript)](https://developer.mozilla.org/es/docs/Web/JavaScript)
[![HTML5](https://img.shields.io/badge/HTML5-Semantic-orange?style=flat-square&logo=html5)](https://developer.mozilla.org/es/docs/Web/HTML5)
[![CSS3](https://img.shields.io/badge/CSS3-Design-blue?style=flat-square&logo=css3)](https://www.w3.org/Style/CSS/)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg?style=flat-square)](LICENSE)

---

## 🌟 Características Clave

*   **Sorteo Aleatorio Controlado:** Generador de números aleatorios sin repetición (esferas de 1 a 75 / 90) que mantiene el historial de números cantados.
*   **Generador Dinámico de Cartones:** Creación algorítmica de cartones basados en las reglas estándar del Bingo, asegurando que no haya números duplicados en el mismo cartón y respetando la distribución por columnas (B-I-N-G-O).
*   **Detección Automática de Jugadas:**
    *   **Línea:** Escaneo en tiempo real de filas completadas.
    *   **Bingo:** Validación instantánea del cartón lleno para proclamar la victoria.
*   **Interfaz Dinámica en Navegador:** Renderizado ágil del panel de control del sorteo y de los cartones de juego mediante la manipulación nativa del DOM.

---

## 🛠️ Tecnologías y Algoritmos

*   **Lenguaje:** JavaScript ES6+
*   **Interfaz:** HTML5 y hojas de estilo CSS3.
*   **Algoritmo de Mezcla (Shuffle):** Implementa derivaciones eficientes para el mezclado aleatorio de los bolilleros virtuales garantizando imparcialidad del juego.
*   **Manipulación del DOM:** Actualización interactiva de nodos sin necesidad de frameworks de terceros, garantizando rapidez y ligereza.

---

## 🚀 Despliegue Local

No requiere de servidores ni entornos pesados. Sigue estos pasos para jugarlo:

### 1. Clonar el Repositorio
```bash
git clone https://github.com/bryanruiz1028/bingo-js.git
cd bingo-js
```

### 2. Ejecutar la Aplicación
Dado que es una aplicación del lado del cliente en JS nativo, simplemente haz doble clic sobre el archivo principal:
*   `index.html`

O si lo prefieres en Visual Studio Code, ábrelo y ejecútalo con la extensión **Live Server**.

---

## 📄 Licencia

Este proyecto está bajo la Licencia MIT - consulta el archivo [LICENSE](LICENSE) para más detalles.
