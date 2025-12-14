# SPOT-AI

**SPOT-AI** es una galería visual experimental construida con **Astro** enfocada en rendimiento, animaciones suaves y una estética minimalista. El proyecto explora navegación tipo SPA, carga optimizada de imágenes y micro-interacciones para mostrar obras visuales generadas con IA.

**Demo:** [https://ux-design-peach.vercel.app](https://ux-design-peach.vercel.app)

---

## Características principales

* **Astro + Vite** para máximo rendimiento
* **Galería dinámica** con rutas estáticas (`/01` → `/27`)
* Navegación fluida tipo SPA (sin recargas completas)
* Efectos visuales y animaciones progresivas
* Imágenes optimizadas en **WebP**
* Arquitectura limpia y escalable

---

## Tecnologías

* **Framework:** Astro
* **Lenguajes:** TypeScript, HTML, CSS
* **Build tool:** Vite
* **Gestor de paquetes:** pnpm
* **Assets:** WebP optimizado

---

## Estructura del proyecto (simplificada)

```text
src/
├── assets/webp        # Imágenes originales
├── components         # Componentes reutilizables (Gallery, Header, ScrollWheel)
├── layouts            # Layout base
├── pages              # Rutas estáticas y dinámicas
│   ├── index.astro
│   ├── info.astro
│   └── [id]/index.astro
├── styles             # Estilos globales
```

El directorio `dist/` contiene el resultado del build final para producción.

---

## Scripts disponibles

```bash
pnpm install   # Instalar dependencias
pnpm dev       # Servidor de desarrollo
pnpm build     # Build de producción
pnpm preview   # Previsualizar el build
```

---

## Concepto del proyecto

SPOT-AI nace como un **playground visual** para experimentar con:

* Presentación de arte generado por IA
* Navegación sin fricción
* UX minimalista inspirada en galerías digitales
* Optimización extrema de imágenes y carga

Es un proyecto orientado a **exploración creativa y técnica**, más que a un producto comercial.

---

## Roadmap / Ideas futuras

* Filtros o categorías
* Transiciones más avanzadas (WebGL / Three.js)
* Modo oscuro/claro
* Mejoras específicas para mobile

---

* GitHub: [https://github.com/AlexF6](https://github.com/AlexF6)

---

