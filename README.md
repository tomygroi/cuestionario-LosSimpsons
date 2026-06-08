# 💛 Cuestionario Interactivo: Los Simpsons
## 🚀 [Visita la pagina](https://tomygroi.github.io/cuestionario-LosSimpsons/)

### 📝 Descripción del Proyecto
Desarrollé una aplicación web interactiva de trivia con temática de **Los Simpsons**. El proyecto consiste en un juego de preguntas de opción múltiple estructurado en etapas lógicas de navegación, diseñado para ofrecer una experiencia dinámica, fluida y entretenida para el usuario desde el navegador.

* **✨ Stack Tecnológico:** *HTML5*, *CSS3*, *JavaScript* (Vanilla JS).

---

### 🔎 Características Principales y Estructura

#### 🌐 Arquitectura de Páginas y Flujo de Navegación
El sistema está construido mediante una arquitectura modular de tres vistas principales enlazadas dinámicamente:

* **Módulo de Cuestionario (`index.html`):** * Evaluación interactiva compuesta por 10 preguntas con 4 opciones de respuesta cada una.
  * Sistema de selección única por pregunta mediante controles optimizados.
* **Pantalla de Resultados (`resultado.html`):** * Procesamiento y renderizado del puntaje final obtenido por el jugador.
  * Botón estratégico **Volver a jugar** que reestablece el estado del juego y redirige a la pantalla inicial.

#### ⚙️ Requisitos Técnicos e Implementación
* **Estructura Semántica Avanzada:** Organización limpia del contenido del cuestionario utilizando etiquetas nativas *HTML5* como `<fieldset>` y `<legend>` para agrupar y aislar de forma clara cada bloque de preguntas.
* **Lógica en Tiempo Real (`main.js`):** Motor de *JavaScript* nativo desarrollado para controlar el flujo de navegación, la validación de las respuestas correctas y el cálculo exacto del puntaje acumulado.
* **Diseño y Estilo Tematizado (`style.css`):** Maquetación adaptada con *CSS3* para recrear la identidad visual de la serie, garantizando una interfaz colorida, atractiva y con controles intuitivos para el usuario.
* **Tabla de scores local (`resultado.js`):** Realización del puntaje final y creación de tabla de resultados de los de más jugadores.
* **Controles Accesibles:** Vinculación exacta entre elementos `<input>` y sus respectivos `<label>` mediante identificadores únicos para optimizar la experiencia de clic.
