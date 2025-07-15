\# Asistente Normativo SENA



Este proyecto es un chatbot interactivo diseñado para facilitar la consulta y comprensión del "Reglamento del Aprendiz SENA - Acuerdo 009 de 2024". Permite a los usuarios (aprendices, instructores, administrativos) obtener información relevante sobre derechos, deberes, sanciones y procedimientos, así como generar casos de estudio hipotéticos basados en la normativa.



\## Características



\* \*\*Consulta de Reglamento:\*\* Acceso rápido a información sobre el Reglamento del Aprendiz SENA.

\* \*\*Perfiles de Usuario:\*\* Respuestas adaptadas según el perfil del usuario (aprendiz, instructor, administrativo).

\* \*\*Generación de Casos de Estudio:\*\* Utiliza un modelo de lenguaje avanzado (Gemini) para crear escenarios hipotéticos y su análisis basado en el reglamento.

\* \*\*Soporte de Voz (Text-to-Speech):\*\* Habilidad para que el chatbot lea las respuestas en voz alta.

\* \*\*Interfaz de Usuario Intuitiva:\*\* Diseño responsivo y animado para una experiencia de usuario agradable.



\## Tecnologías Utilizadas



\* \*\*HTML5:\*\* Estructura de la aplicación.

\* \*\*CSS3 (Tailwind CSS):\*\* Estilos y diseño responsivo.

\* \*\*JavaScript:\*\* Lógica del chatbot y manejo de interacciones.

\* \*\*Google Gemini API:\*\* Para la generación de texto avanzado y casos de estudio.

\* \*\*LottieFiles:\*\* Para animaciones visuales (por ejemplo, el indicador de "pensando").

\* \*\*Google Fonts:\*\* Para la tipografía (Exo, Inter, Source Sans Pro).



\## Cómo Ejecutar el Proyecto Localmente



Para ejecutar este proyecto en tu máquina local, sigue los siguientes pasos:



1\.  \*\*Clonar el Repositorio:\*\*

&nbsp;   ```bash

&nbsp;   git clone <URL\_DEL\_REPOSITORIO>

&nbsp;   cd asistente-normativo-sena

&nbsp;   ```

&nbsp;   (Reemplaza `<URL\_DEL\_REPOSITORIO>` con la URL real de tu repositorio de GitHub).



2\.  \*\*Abrir `index.html`:\*\*

&nbsp;   Simplemente abre el archivo `index.html` en tu navegador web preferido. No se requiere un servidor local para esta aplicación, ya que todo el código es de cliente.



&nbsp;   \*\*Nota sobre la API Key:\*\*

&nbsp;   El campo `apiKey` en el código JavaScript (`const apiKey = "";`) está vacío. En un entorno de desarrollo o producción real, deberías gestionar tu clave de API de Gemini de forma segura. Para pruebas locales, puedes insertar tu clave de API directamente en el código JavaScript, pero \*\*NUNCA\*\* la subas a un repositorio público de GitHub. Para despliegues, considera usar variables de entorno o servicios de backend para proteger tu clave.



\## Estructura del Proyecto





.

├── index.html          # Archivo principal de la aplicación

├── README.md           # Este archivo

└── .gitignore          # Archivo para ignorar archivos y directorios en Git





\## Contribuciones



Las contribuciones son bienvenidas. Si deseas mejorar este proyecto, por favor sigue estos pasos:



1\.  Haz un "fork" del repositorio.

2\.  Crea una nueva rama (`git checkout -b feature/nueva-caracteristica`).

3\.  Realiza tus cambios y haz "commit" (`git commit -am 'Add new feature'`).

4\.  Sube tus cambios a tu "fork" (`git push origin feature/nueva-caracteristica`).

5\.  Abre un "Pull Request".



\## Licencia



Este proyecto está bajo la licencia MIT. Consulta el archivo `LICENSE` para más detalles.



