# Fase 2: Planificación y Diseño

## 1. Esquema del Perfil

Para la construcción del portafolio definí el siguiente orden de secciones en el `README.md` principal, buscando que la información se lea rápido y con una jerarquía clara:

1. **Presentación:** Saludo inicial, nombre, carrera y mi rol actual.
2. **Sobre mí y Áreas de interés:** Breve resumen académico de mi paso por la universidad y los temas de desarrollo que más me llaman la atención.
3. **Habilidades y Tecnologías:** Organización de lenguajes, frameworks y herramientas clasificadas mediante insignias visuales (badges).
4. **Proyectos Destacados:** Sección principal con las fichas detalladas de mis 3 proyectos seleccionados.
5. **Contacto:** Enlaces directos a mi correo y redes profesionales.

---

## 2. Estrategia de Commits

Para mantener un historial limpio y estructurado en Git, aplicaré la convención de **Commits Convencionales**. Registraré cada avance de forma independiente para evitar acumular muchos cambios en un solo commit.

### Prefijos que utilizaré:
* `docs:` Para actualizar archivos de documentación dentro de la carpeta `/docs` o editar el `README.md`.
* `feat:` Para agregar nuevas secciones, fichas de proyectos o bloques de contenido HTML/Markdown.
* `style:` Para ajustar la presentación visual, orden de elementos, diseño responsivo o corregir estilos.
* `fix:` Para corregir errores de sintaxis, enlaces rotos o fallas de ortografía.

### Plan de commits a realizar durante el desarrollo:
* `docs: agregar planificacion y diseno de la Fase 2`
* `feat: agregar encabezado y seccion de presentacion en README`
* `feat: incorporar seccion de habilidades y insignias de tecnologias`
* `feat: agregar tarjetas de proyectos destacados`
* `style: mejorar jerarquia visual y accesibilidad movil`
* `fix: corregir enlaces a repositorios`

---

## 3. Diseño del Contenido por Sección

### Sección 1: Presentación
* **Información a incluir:** Mi nombre completo, carrera universitaria (Ingeniería en Ciencias de la Computación / Desarrollo de Software en ESPOL) y una frase corta sobre mi enfoque.
* **Información a evitar:** Datos personales sensibles como número telefónico, dirección de casa o cédula.
* **Elementos visuales:** Texto claro, encabezado (`#`), resaltado en negrita e insignias de estado (ej. estudiante activo).
* **Enlaces necesarios:** Ninguno en este apartado.
* **Lectura rápida:** Oraciones cortas e idas al grano para enganchar en los primeros 10 segundos.

### Sección 2: Sobre mí y Áreas de Interés
* **Información a incluir:** Lo que me motiva a programar, mi progreso académico y las áreas tecnológicas donde me quiero especializar (desarrollo web, bases de datos, lógica de bajo nivel).
* **Información a evitar:** Historias personales ajenas al ámbito técnico o académico.
* **Elementos visuales:** Párrafos de máximo 3 líneas y una lista con viñetas para mis temas de interés.
* **Enlaces necesarios:** Ninguno.
* **Lectura rápida:** Puntos clave listados verticalmente para evitar bloques densos de texto.

### Sección 3: Habilidades y Tecnologías
* **Información a incluir:** Lenguajes que he utilizado en clases y proyectos (Python, Java, C, Assembly MIPS, SQL), motor de base de datos (MySQL) y herramientas (Git, GitHub, VS Code).
* **Información a evitar:** Medidores o porcentajes inventados de nivel de conocimiento (ej. "Python 85%").
* **Elementos visuales:** Insignias de colores (*Shields.io*) organizadas en filas por categoría.
* **Enlaces necesarios:** Enlaces opcionales en las insignias hacia las tecnologías oficiales.
* **Lectura rápida:** Iconos y badges que permiten identificar las herramientas a simple vista.

### Sección 4: Proyectos Destacados
* **Información a incluir:** Fichas de los 3 proyectos (Bases de Datos, MIPS FIFA 2026 y Calculadora Científica) con descripción del problema, tecnologías y enlaces.
* **Información a evitar:** Pegar bloques largos de código fuente directamente en el perfil.
* **Elementos visuales:** Formato de ficha estructurado con viñetas, negritas y separadores horizontales.
* **Enlaces necesarios:** Links directos a las carpetas en `ESPOL-projects` y al repositorio independiente `scientific-calculator`.
* **Lectura rápida:** Estructura idéntica y repetible en las 3 fichas para facilitar la comparación.

### Sección 5: Contacto
* **Información a incluir:** Mi correo institucional/profesional y enlace a mi perfil de LinkedIn o GitHub.
* **Información a evitar:** Redes sociales personales no profesionales (Facebook, Instagram).
* **Elementos visuales:** Lista limpia con iconos o viñetas.
* **Enlaces necesarios:** Enlace para correo y URL directa a LinkedIn.
* **Lectura rápida:** Canales visibles al final con texto claro sobre dónde dar clic.

---

## 4. Fichas de Proyectos Destacados

### Proyecto 1: Sistema de Gestión CRUD de Bases de Datos
* **Nombre:** Interfaz CRUD Python + MySQL (`database-systems/project`)
* **Problema o necesidad que resuelve:** Facilita la administración de datos en una base de datos relacional mediante una interfaz gráfica, evitando tener que ejecutar sentencias SQL manualmente.
* **Tecnologías utilizadas:** Python, MySQL, Conector MySQL/Python, Tkinter.
* **Funcionalidades principales:**
  * Conexión a la base de datos MySQL.
  * Módulo de creación, lectura, actualización y eliminación de registros (CRUD).
  * Vista en tabla que se actualiza automáticamente tras cada cambio.
* **Enlace al repositorio:** [Proyecto Base de Datos](https://github.com/kevin-moralesc/ESPOL-projects/tree/main/database-systems/project)
* **Enlace a demostración:** Capturas de pantalla de las ventanas de la interfaz y consultas en la documentación del repositorio.

---

### Proyecto 2: Simulador de Torneo de Fútbol en Ensamblador
* **Nombre:** Simulador del Mundial FIFA 2026 (`computer-organization/project`)
* **Problema o necesidad que resuelve:** Modela la simulación de partidos y la tabla de posiciones de la fase de grupos a nivel de arquitectura de hardware, demostrando el manejo de memoria y subrutinas en ensamblador.
* **Tecnologías utilizadas:** Assembly MIPS, Mipsy Web / Entorno MARS.
* **Funcionalidades principales:**
  * Selección y validación de selecciones participantes.
  * Simulación automática de partidos con generación aleatoria de goles.
  * Ordenamiento de tabla de posiciones usando Bubble Sort según puntos y diferencia de gol.
* **Enlace al repositorio:** [Proyecto MIPS FIFA 2026](https://github.com/kevin-moralesc/ESPOL-projects/tree/main/computer-organization/project)
* **Enlace a demostración:** Guía de ejecución en línea con Mipsy Web y capturas del menú por consola en su `README.md`.

---

### Proyecto 3: Calculadora Científica Segura
* **Nombre:** Scientific Calculator (`scientific-calculator`)
* **Problema o necesidad que resuelve:** Proporciona una herramienta de escritorio para calcular funciones matemáticas complejas procesando las expresiones de manera segura sin usar funciones vulnerables como `eval()`.
* **Tecnologías utilizadas:** Python 3, Tkinter, Módulo `ast` (Abstract Syntax Trees), Licencia MIT.
* **Funcionalidades principales:**
  * Evaluador seguro de operaciones matemáticas y funciones trigonométricas/algebraicas mediante parser AST.
  * Interfaz de usuario intuitiva compatible con teclado e interfaz gráfica.
  * Manejo explícito de errores sintácticos y operaciones no permitidas (división para cero).
* **Enlace al repositorio:** [scientific-calculator en GitHub](https://github.com/kevin-moralesc/scientific-calculator)
* **Enlace a demostración:** Repositorio independiente desplegado con documentación completa de uso e instrucciones de instalación.