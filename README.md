# Curso IA — Página web de presentación de alumnos

Este proyecto es una página web moderna, desarrollada con **HTML5**, **CSS3** y **JavaScript**, que presenta de forma profesional a un grupo de alumnos. El diseño es completamente **responsive**, utiliza una paleta de colores **azul y blanco**, e incluye menús desplegables, carrusel de imágenes, fichas individuales de alumnos y un modal para ver el currículum detallado.

---

## 🧩 Estructura del proyecto

```
Curso-IA/
│
├── index.html        # Archivo principal del sitio web
├── README.md         # Documentación del proyecto
└── assets/           # (Opcional) Carpeta sugerida para imágenes y recursos adicionales
```

---

## 🎨 Características principales

- **Diseño moderno y limpio**, basado en colores azul y blanco.
- **Cabecera con menú desplegable** (multinivel) con las siguientes secciones:
  - **Herramientas** → Editor CV
  - **Currículum Vitae** → Enviar currículum, Plantillas de currículum
  - **Blog** → Consejos para tu currículum, Tu currículum en inglés, Currículum europeo
  - **Quiénes somos** (sin submenús)
  - **Mi cuenta** → Iniciar sesión, Registrarse
- **Carrusel principal** con imágenes y botones de acción para crear o editar un CV.
- **8 fichas de alumnos**, dispuestas en una **rejilla responsive de 2 columnas**.
- Cada ficha muestra:
  - Fotografía
  - Nombre, primer y segundo apellido
  - Organismo al que pertenece
  - Descripción breve profesional
  - Enlaces para ver CV detallado o contactar
- **Modal con currículum detallado** (perfil, experiencia, educación y competencias).
- **Banner** para acceder al blog corporativo.
- **Pie de página dividido**:
  - Izquierda: enlaces del menú en formato de 2 columnas.
  - Derecha: iconos y enlaces a redes sociales (Twitter, LinkedIn, YouTube, Instagram).

---

## ⚙️ Tecnologías utilizadas

- **HTML5** para la estructura semántica.
- **CSS3** (con enfoque responsive y uso de variables para colores y sombras).
- **JavaScript (vanilla)** para interactividad:
  - Carrusel automático e interactivo.
  - Modal dinámico con datos de cada alumno.
  - Menú móvil con hamburguesa.

---

## 📱 Diseño responsive

El diseño está optimizado para adaptarse correctamente a:

- Dispositivos móviles (hasta 600px)
- Tablets (hasta 900px)
- Escritorios y pantallas grandes

El menú cambia a formato **hamburguesa** en móviles, mientras que la rejilla de alumnos pasa de 2 a 1 columna.

---

## 🧑‍💻 Personalización

Puedes editar el contenido directamente en el archivo `index.html`:

- Para añadir o modificar alumnos, localiza el array `students` en el script JavaScript.
- Cada objeto dentro del array representa un alumno:

```js
{
  nombre: 'Lucía',
  apellidos: 'García Pérez',
  organismo: 'Universidad Tecnológica',
  foto: 'ruta_o_url_de_imagen.jpg',
  perfil: 'Descripción breve del alumno',
  contacto: 'correo@ejemplo.com',
  experiencia: ['Puesto — Empresa (Años)'],
  educacion: ['Título — Institución (Años)'],
  skills: ['Competencia1','Competencia2']
}
```

---

## 🚀 Instrucciones de uso

1. Clona este repositorio o descarga el código:
   ```bash
   git clone https://github.com/tuusuario/curso-ia.git
   ```

2. Abre el archivo `index.html` en tu navegador.

3. (Opcional) Sube los archivos a un servidor o utiliza **GitHub Pages** para publicarlo:
   ```bash
   git add .
   git commit -m "Versión inicial del sitio Curso IA"
   git push origin main
   ```

---

## 📄 Licencia

Este proyecto está publicado bajo la licencia **MIT**, lo que permite su libre uso, modificación y distribución, siempre y cuando se conserve la atribución original.

---

## ✨ Autor

**Curso IA** — Proyecto educativo para la presentación profesional de alumnos.

Creado con ❤️ por Antonio Traverso Ariza y adaptado para uso académico y formativo.
