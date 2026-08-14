# 🐾 HoneyCode

Plataforma web interactiva para aprender a programar desde cero, con lecciones cortas, práctica guiada y una mascota (Honey 🐶) que acompaña todo el recorrido. Inspirada en plataformas como Duolingo, Mimo y Coddy.

> **Estado: en desarrollo activo.** Este proyecto todavía no está terminado — este README se irá actualizando a medida que se agreguen o cambien funcionalidades.

## ✨ Funcionalidades actuales

- **12 cursos**: HTML, CSS, JavaScript, TypeScript, Python, Java, C++, Node.js, SQL, Rust, Solidity y Git & GitHub.
- **Lecciones interactivas** progresivas (Novato → Moderado → Experto) con compilador/consola simulada.
- **Vista previa en vivo** del código para las lecciones de HTML/CSS.
- **Racha diaria y progreso (XP)** por curso.
- **Certificado de finalización** por curso, descargable/imprimible, con botón para compartir en LinkedIn y compartir el logro.
- **Registro e inicio de sesión** (cuenta guardada localmente en el navegador, sin servidor).
- **Sección de Proyectos**: 2 mini proyectos guiados por lenguaje (24 en total) con checklist y seguimiento de completados.
- **Tour guiado "¿Cómo funciona?"** que explica la plataforma paso a paso.

## 🛠️ Tecnología

- Archivo único (`honey-web-cursos.html`) autocontenido: **React 18** embebido directamente (sin CDN, sin paso de build).
- Sin backend — todo el progreso, cuentas y certificados se guardan en `localStorage` del navegador.
- Estilo visual: paleta cálida (crema + terracota), tipografías Plus Jakarta Sans / Nunito / JetBrains Mono.

## 📂 Cómo verlo

Solo abre `honey-web-cursos.html` en tu navegador. No requiere instalación ni servidor (aunque también puede servirse con cualquier servidor estático simple).

## 🚧 Pendiente / roadmap

- [ ] Terminar de pulir diseño e interfaz en secciones restantes.
- [ ] Revisar y completar contenido de cursos faltantes.
- [ ] Mejorar sección de Comunidad (actualmente solo enlaza a Cursos).
- [ ] Ver viabilidad de backend real para sincronizar progreso entre dispositivos.

## 🐶 Créditos

Proyecto de Tania Zepeda — mascota "Honey" y diseño propios.
