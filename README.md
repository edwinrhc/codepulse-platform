# 📘 CodePulse: Sistema de Gestión de Blogs

CodePulse es una aplicación web completa para la **gestión y publicación de blogs**, que integra un backend en C# con ASP.NET Core y un frontend moderno en Angular 17. Está diseñada para permitir la creación, edición, eliminación y visualización de publicaciones, categorías e imágenes.



---

## 🚀 Tecnologías Utilizadas

### 🧠 Backend - ASP.NET Core (C#)
- Framework: **ASP.NET Core Web API**
- Seguridad: **Autenticación JWT** (si aplica)
- ORM: **Entity Framework Core**
- Base de Datos: **SQL Server**
- Documentación API: **Swagger (OpenAPI)**

📁 Ruta del backend: `./API`

---

### 🎨 Frontend - Angular 17
- Framework: **Angular 17**
- Librerías:
  - [`ngx-markdown`](https://github.com/jfcere/ngx-markdown) para renderizar contenido en Markdown.
  - `Bootstrap` para estilos responsivos.
- Comunicación: **HTTPClient con servicios REST**
- Animaciones y navegación: Router + Animations

📁 Ruta del frontend: `./UI/codepulse`

---

## 📦 Dependencias clave (Angular)

```json
"@angular/core": "^17.0.0",
"ngx-markdown": "^17.1.1",
"rxjs": "~7.8.1",
"zone.js": "~0.14.0"
