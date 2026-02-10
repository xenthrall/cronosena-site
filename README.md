# 🌐 CronoSENA Site

**Portal oficial del proyecto CronoSENA**, una iniciativa para centralizar, conectar y modernizar la gestión académica y tecnológica de los centros de formación del **SENA** 🇨🇴.

Este repositorio contiene el código fuente del **sitio web público** (`https://cronosena.com`), una página estática desarrollada con **[Astro](https://astro.build)** y **TailwindCSS**, enfocada en velocidad, SEO y escalabilidad.

---

## 🚀 Visión del proyecto

CronoSENA busca crear un ecosistema modular que conecte a los centros de formación del SENA mediante una infraestructura distribuida.  
Cada centro puede tener su propio sistema independiente (por ejemplo, `cata.cronosena.com`) mientras comparte un portal común que actúa como **hub informativo y de acceso**.

**Objetivos del portal:**
- Servir como punto de entrada al ecosistema CronoSENA.
- Permitir buscar y acceder a los sistemas de los diferentes centros.
- Mostrar información institucional, noticias y recursos de apoyo.
- Optimizar posicionamiento SEO para visibilidad pública.

---

## 🧠 Tecnologías principales

| Tecnología | Uso |
|-------------|-----|
|  [Astro](https://astro.build) | Framework base del sitio estático |
|  [TailwindCSS](https://tailwindcss.com) | Estilos rápidos, responsivos y personalizables |
|  [Astro SEO](https://docs.astro.build/en/guides/integrations-guide/seo/) | Mejora de metadatos y visibilidad en buscadores |
|  [GitHub Pages](https://pages.github.com) | Hosting gratuito y automatizado del portal |
|  [TypeScript](https://www.typescriptlang.org) *(opcional)* | Tipado y escalabilidad futura |

---

## 🛠️ Instalación y desarrollo local

Clona el repositorio:

```bash
git clone https://github.com/xenthrall/cronosena-site.git
cd CronoSENA-site
```

Instala dependencias:

```bash
npm install
```


Inicia el entorno de desarrollo:

```bash
npm run dev
```


El sitio se abrirá en:
👉 http://localhost:4321

```csharp
/
├─ public/               # Archivos estáticos (imágenes, íconos, etc.)
├─ src/
│  ├─ components/        # Componentes reutilizables
│  ├─ layouts/           # Plantillas base
│  ├─ pages/             # Rutas y contenido del sitio
│  ├─ styles/            # Configuración de estilos globales
│  └─ data/              # (Opcional) Listado de centros o configuración dinámica
├─ package.json
└─ astro.config.mjs
```
---

## 🏛️ Origen del proyecto

**CronoSENA** fue desarrollado en el **Centro Agroempresarial y Turístico de los Andes (CATA)**, ubicado en el departamento de **Santander, Colombia**.

El sistema nació como parte del **proyecto de formación del programa Tecnólogo en Análisis y Desarrollo de Software del Servicio Nacional de Aprendizaje (SENA)**.

Este desarrollo fue liderado por un equipo bajo el pseudónimo **xenthrall**, con el propósito de crear una herramienta que aporte al mejoramiento de la planificación académica dentro de los centros de formación del SENA.

> ⚠️ **Nota:** CronoSENA **no es un producto oficial del SENA**.  
> Es un sistema formativo desarrollado con fines académicos, implementado y probado en contexto real dentro del CATA.

💡 ¿Quieres contribuir, reportar un problema o proponer mejoras?  
Visita el repositorio oficial en GitHub: [xenthrall/CronoSENA](https://github.com/xenthrall/cronosena)
