# Fase 1: Análisis

## 1. Perfiles de Referencia

Para iniciar este proyecto, estuve revisando tres perfiles de GitHub para analizar cómo otros desarrolladores presentan su trabajo, organizan sus secciones y qué detalles hacen que un perfil se vea bien o tenga problemas de diseño:

* [Perfil 1: anmol098 (Anmol Pratap Singh)](https://github.com/anmol098/anmol098)
* [Perfil 2: SP-XD (Somnath Paul)](https://github.com/SP-XD/SP-XD)
* [Perfil 3: mayhemantt (Hemant Joshi)](https://github.com/mayhemantt/mayhemantt)

### Tabla Comparativa de Perfiles

| Criterio de Evaluación | [anmol098](https://github.com/anmol098/anmol098) | [SP-XD](https://github.com/SP-XD/SP-XD) | [mayhemantt](https://github.com/mayhemantt/mayhemantt) |
| :--- | :--- | :--- | :--- |
| **Presentación (10s)** | Muestra un estilo técnico como *Technical Lead*. Usa GIF animado, badges de redes y un link para agendar llamadas. | Es un perfil dinámico e informal. Tiene un banner animado de `Hello <coders/>`, dibujo GIF de un programador y contador de visitas. | Temática espacial. Usa un GIF de astronauta en naranja, saludo sencillo y su rol como *Full Stack Developer*. |
| **Estructura y Jerarquía** | Enlaces de redes -> Consola interactiva (`npx`) -> Objeto en JavaScript (*About Me*) -> Estadísticas automáticas. | Banner en GIF -> Insignias de tecnologías -> Clase de pseudocódigo -> Gráficos de dona con estadísticas. | Redes sociales arriba -> Bio con GIF al lado -> Badges de herramientas -> Cuadro animado en *What I do*. |
| **Habilidades** | Las muestra ordenadas dentro de un objeto de JavaScript (Frontend, Backend, Cloud, DevOps, IA). | Usa dos formas: una lista de badges de colores (*Shields.io*) y un bloque de código organizando sus herramientas. | Tiene una fila compacta de insignias con iconos de lenguajes, frameworks y servicios cloud. |
| **Proyectos** | Destaca su herramienta de consola (`npx anmol`) y deja el link a sus repositorios públicos. | No puso tarjetas de proyectos fijados en el README; se enfoca en mostrar su stack y estadísticas. | No tiene tarjetas fijas en el README; manda a sus repositorios y sitio web desde los links principales. |
| **Contacto** | Muestra su sitio web, Twitter/X y un widget de agenda para reuniones de 30 minutos. | Tiene un badge visible arriba y un enlace directo en la lista a su Telegram (`@SP_XD`). | Varios iconos arriba para LinkedIn, Twitter, Dev.to, Spotify y BuyMeACoffee. |
| **Accesibilidad y Móvil** | En celular se ve bien arriba, pero en "A little more about me" el bloque de código no cabe en pantalla y obliga a deslizar a la derecha. | Vistoso en móvil, pero la caja de código `class About extends Me` también se sale y toca hacer scroll horizontal. | Super ordenado en móvil. La imagen del astronauta se acomoda sola abajo del texto *"I don't trust people..."* sin romper el diseño. |

---

## 2. Análisis de Repositorios 

Al revisar los repositorios de estos desarrolladores, noté varias características importantes que hacen que un proyecto esté bien presentado:

| Característica de Calidad | Estado en los Repos | Lo que aprendí / Buenas prácticas |
| :--- | :---: | :--- |
| **Descripción corta, temas (topics) y Demo** | Sí tienen | Sirve para entender de una el proyecto y probarlo con un clic. |
| **README bien completo** | Sí tienen | Explica qué hace el proyecto, qué tecnologías usa, cómo instalarlo y trae capturas. |
| **Licencia y .gitignore** | Sí tienen | Indispensable para saber las reglas de uso y no subir carpetas pesadas. |
| **Historial de Commits** |  Frecuente | Hacen commits seguidos y usan mensajes claros (ej. *feat*, *fix*, *docs*). |
| **Issues, Pull Requests y Ramas** |  A veces | Se nota más en proyectos grandes o cuando trabajan con más personas. |
| **Estructura de carpetas** |  Ordenada | Todo está bien separado en carpetas como `/assets`. |

---

## 3. Requisitos de mi Perfil

Con base en todo lo analizado, definí los puntos que necesito implementar para construir mi propio portafolio:

### Requisitos Funcionales (Lo que debe hacer)
* **RF1 - Presentación personal:** Una sección principal con mi nombre, lo que estudio, mi enfoque profesional y mis redes (sin poner datos sensibles como teléfono o dirección).
* **RF2 - Sección de Proyectos:** Mostrar al menos **3 proyectos** reales, cada uno con su descripción, tecnologías usadas, enlace a su repositorio en GitHub y enlace a la página o demo funcionando.
* **RF3 - Sección de Tecnologías:** Un apartado claro donde explique los lenguajes, frameworks y herramientas que he aprendido a usar.
* **RF4 - Contacto:** Dejar canales claros como mi correo y mi perfil de LinkedIn para que me puedan escribir.

### Requisitos No Funcionales (Cómo debe funcionar)
* **RNF1 - Facilidad de lectura:** Usar letra clara, buen tamaño y colores con buen contraste para que no canse la vista.
* **RNF2 - Adaptable a celulares :** Evitar bloques de código que se salgan horizontalmente en pantallas pequeñas y lograr que las imágenes se acomoden abajo del texto como en el perfil de *mayhemantt*.
* **RNF3 - Accesibilidad:** Poner texto descriptivo (`alt`) a las imágenes para que se entiendan si no cargan o si se usa lector de pantalla.
* **RNF4 - Publicación:** Mantener el código limpio y desplegar el sitio terminado usando **GitHub Pages**.

---
## 4. Revisión de mis Repositorios

Para la sección de proyectos del portafolio seleccioné tres trabajos, combinando proyectos académicos del repositorio centralizado [`ESPOL-projects`](https://github.com/kevin-moralesc/ESPOL-projects) con un proyecto personal independiente:

- **Proyecto 1:** Sistemas de Bases de Datos (`database-systems/project` - Interfaz gráfica en Python conectada a MySQL con operaciones CRUD en tiempo real).
- **Proyecto 2:** Organización de Computadores (`computer-organization` - Simulador del Mundial FIFA 2026 en Assembly MIPS).
- **Proyecto 3 (Personal):** Calculadora Científica ([`scientific-calculator`](https://github.com/kevin-moralesc/scientific-calculator) - Aplicación de escritorio en Python con interfaz Tkinter y evaluador seguro AST).

### Tabla de Diagnóstico

| Criterio a verificar | Proyecto 1 (Bases de Datos) | Proyecto 2 (MIPS FIFA) | Proyecto 3 (Calculadora Científica) |
| :--- | :---: | :---: | :---: |
| ¿Está en un repositorio independiente? | No (está en carpeta) | No (está en carpeta) | Sí |
| ¿Tiene descripción corta, *topics* y link a Demo? | Me falta | Me falta | Falta ajustar *topics* |
| ¿Tiene su propio README.md con capturas y guía? | Me falta | Sí (bien estructurado) | Sí (bien estructurado) |
| ¿Tiene Licencia y archivo `.gitignore`? | Solo en la raíz | Solo en la raíz | Sí (Licencia MIT) |
| ¿Commits seguidos y con mensajes claros? | Por mejorar | Mensajes descriptivos | Mensajes descriptivos |
| ¿Código fuente / entregable disponible? | Interfaz Python + SQL | Código MIPS | Código Python completo |

## 4. Revisión de mis Repositorios

Para la sección de proyectos del portafolio seleccioné tres trabajos, combinando proyectos académicos del repositorio centralizado [`ESPOL-projects`](https://github.com/kevin-moralesc/ESPOL-projects) con un proyecto personal independiente:

- **Proyecto 1:** Sistemas de Bases de Datos (`database-systems/project` - Interfaz gráfica en Python conectada a MySQL con operaciones CRUD en tiempo real).
- **Proyecto 2:** Organización de Computadores (`computer-organization/project` - Simulador del Mundial FIFA 2026 en Assembly MIPS).
- **Proyecto 3 (Personal):** Calculadora Científica ([`scientific-calculator`](https://github.com/kevin-moralesc/scientific-calculator) - Aplicación de escritorio en Python con interfaz Tkinter y evaluador seguro AST).

### Tabla de Diagnóstico

| Criterio a verificar | Proyecto 1 (Bases de Datos) | Proyecto 2 (MIPS FIFA) | Proyecto 3 (Calculadora Científica) |
| :--- | :---: | :---: | :---: |
| ¿Está en un repositorio independiente? | No (está en carpeta) | No (está en carpeta) | Sí |
| ¿Tiene descripción corta, *topics* y link a Demo? | Me falta | Me falta | Falta ajustar *topics* |
| ¿Tiene su propio README.md con capturas y guía? | Me falta | Sí (bien estructurado) | Sí (bien estructurado) |
| ¿Tiene Licencia y archivo `.gitignore`? | Solo en la raíz | Solo en la raíz | Sí (Licencia MIT) |
| ¿Commits seguidos y con mensajes claros? | Por mejorar | Mensajes descriptivos | Mensajes descriptivos |
| ¿Código fuente / entregable disponible? | Interfaz Python + SQL | Código MIPS | Código Python completo |

**Identificación de faltantes:** Tanto el proyecto personal de la Calculadora Científica como el proyecto del Mundial FIFA en MIPS cuentan con sus propios archivos `README.md` bien estructurados. Únicamente al proyecto de Bases de Datos le falta crear su archivo `README.md` individual con sus respectivas capturas. A los dos proyectos universitarios les falta configurar etiquetas (*topics*) y enlaces directos a sus demos o guías en GitHub.
