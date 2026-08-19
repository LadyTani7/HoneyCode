# 🐾 HoneyCode

Plataforma web interactiva para aprender a programar desde cero, con lecciones cortas, práctica guiada y una mascota (Honey 🐶) que acompaña todo el recorrido. Inspirada en plataformas como Duolingo, Mimo y Coddy.

> **Estado: en desarrollo activo.** Este proyecto todavía no está terminado — este README se irá actualizando a medida que se agreguen o cambien funcionalidades.

**🔗 Sitio en vivo:** https://honey-code.vercel.app/

## ✨ Funcionalidades actuales

- **12 cursos**: HTML, CSS, JavaScript, TypeScript, Python, Java, C++, Node.js, SQL, Rust, Solidity y Git & GitHub.
- **Lecciones interactivas** progresivas (Novato → Moderado → Experto) con compilador/consola simulada. El curso de C++ está basado en el material real de la clase de Fundamentos de la Programación (UJCV).
- **Vista previa en vivo** del código para las lecciones de HTML/CSS.
- **Zona de Práctica**: 24 ejercicios cortos (2 por lenguaje), independientes de los cursos, con ejemplo y solución revelables.
- **Racha diaria y progreso (XP)** por curso, con aviso cuando la racha está por perderse si no se completa una lección, proyecto o ejercicio en el día.
- **Certificado de finalización** por curso, descargable/imprimible, con botón para compartir en LinkedIn y compartir el logro.
- **Registro e inicio de sesión** (cuenta guardada localmente en el navegador, sin servidor).
- **Sección de Proyectos**: 2 mini proyectos guiados por lenguaje (24 en total) con checklist y seguimiento de completados.
- **Tour guiado "¿Cómo funciona?"** que explica la plataforma paso a paso.
- **Panel Administrativo**: estadísticas generales de la plataforma (cuentas, cursos, lecciones, certificados, progreso) y lista de cuentas registradas, accesible desde el menú superior.
- **Modo oscuro**: alternable desde el menú superior, con paleta propia guardada por navegador.
- **Rutas temáticas**: caminos guiados que agrupan varios cursos relacionados (ej. Desarrollador Web, Ciencia de Datos y Backend, Ingeniería de Software, Blockchain Developer) con progreso conjunto y acceso directo al siguiente curso pendiente.
- **Pistas de Honey**: sugerencias guionadas de la mascota tras varios intentos fallidos en un ejercicio o evaluación, sin IA ni costo asociado.
- **Repaso espaciado**: la plataforma sugiere a diario una lección ya completada para repasar, con acceso directo desde el menú superior.
- **Diseño responsivo**: adaptado para escritorio, celular en vertical y en horizontal.

## 🛠️ Tecnología

- Archivo único (`honey-web-cursos.html`) autocontenido: **React 18** embebido directamente (sin CDN, sin paso de build).
- Sin backend — todo el progreso, cuentas y certificados se guardan en `localStorage` del navegador (por decisión del proyecto: el Panel Administrativo solo muestra datos del navegador en el que se abre).
- Estilo visual: paleta cálida (crema + terracota), tipografías Plus Jakarta Sans / Nunito / JetBrains Mono.
- Desplegado en **Vercel**, con auto-deploy en cada push a `main`.

## 📂 Cómo verlo

Entra directo a https://honey-code.vercel.app/, o abre `honey-web-cursos.html` en tu navegador localmente. No requiere instalación ni servidor.

## 🚧 Pendiente / roadmap

- [ ] Terminar de pulir diseño e interfaz en secciones restantes.
- [ ] Revisar y completar contenido de cursos faltantes.
- [ ] Mejorar sección de Comunidad (actualmente solo enlaza a Cursos).

## 🐶 Créditos

Proyecto de Tania Zepeda — mascota "Honey" y diseño propios.
