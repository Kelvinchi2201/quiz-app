🧠 Cuestionario de Cultura General (Astro + Vanilla JS)
🌟 Descripción del Proyecto
Este es un proyecto de aplicación web simple de cuestionario (Quiz App) desarrollado usando el framework Astro para la construcción de la interfaz y JavaScript puro (Vanilla JS) para toda la lógica interactiva del juego.

El objetivo es ofrecer una experiencia de usuario rápida y sin complicaciones, con un diseño moderno utilizando Tailwind CSS.

Características

Preguntas Dinámicas: Las preguntas se cargan desde un archivo questions.json  para facilitar su edición y expansión.


Lógica de Juego Sencilla: El cuestionario avanza inmediatamente después de seleccionar una respuesta, sin necesidad de temporizadores ni recargas de página.


Feedback Visual: Al seleccionar una opción, los botones cambian de color para mostrar la respuesta correcta (verde) o incorrecta (rojo).


Puntuación Final: Muestra un resumen claro de la puntuación al finalizar todas las preguntas.

🛠️ Tecnologías Utilizadas
Astro: Framework web para la construcción de la interfaz y la inyección de datos.


JavaScript (Vanilla JS): Lógica del cuestionario (in-browser).

Tailwind CSS: Para estilos y diseño responsivo.

🚀 Instalación y Uso
Sigue estos pasos para levantar el proyecto en tu máquina local.

1. Requisitos
Asegúrate de tener instalado Node.js (versión 16.0 o superior).

2. Clonar el Repositorio
Bash

git clone <URL_DE_TU_REPOSITORIO>
cd quizz-app
3. Instalar Dependencias
Desde la raíz del proyecto, instala todas las dependencias de Node.js:

Bash

npm install
# o
pnpm install
# o
yarn install
4. Ejecutar en Modo Desarrollo
Inicia el servidor de desarrollo. La aplicación estará disponible generalmente en http://localhost:4321/.

Bash

npm run dev
5. Compilar para Producción
Para generar la versión estática de tu sitio, usa el comando build:

Bash

npm run build
⚙️ Estructura del Código Clave
Archivo	Descripción
src/pages/index.astro 

Página principal que renderiza el componente Quiz con la directiva client:load para hidratar el JavaScript.

src/components/Quiz.astro	
Contiene toda la estructura HTML y el bloque <script is:inline> con la lógica de JavaScript para el juego.

src/data/questions.json	
El archivo de configuración que almacena todas las preguntas, opciones y la respuesta correcta.


https://roadmap.sh/projects/quiz-app

https://roadmap.sh/projects/quiz-app/solutions?u=68e47bf01d72874d10ba816b
