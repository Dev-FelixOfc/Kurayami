# 🌌 Kurayami Theme — Kazuma API

Un tema oscuro profundo, elegante y minimalista con acentos morados neón y estética ciberpunk, desarrollado exclusivamente para el ecosistema de **Kazuma API**. Este entorno elimina por completo los modos claros para ofrecer una experiencia visual inmersiva de alto nivel.

---

## 🚀 Características Principales

* **Estructura Inteligente:** Reemplaza el dashboard oficial de manera dinámica sin alterar los archivos base del núcleo del servidor.
* **Kurayami Palette:** Colores oscuros absolutos (`#040406`) combinados con iluminación eléctrica morada (`#a855f7`).
* **Modularidad por EJS:** Integra componentes parciales (`partials/footer.html`) inyectados directamente por el motor de renderizado de Express.
* **Optimización de Rendimiento:** Estilos e interfaces ultraligeras que no afectan el tiempo de respuesta ni el consumo de recursos de la API.

---

## 📂 Estructura del Repositorio

```text
kurayami/
├── theme-config.json     # Metadatos oficiales, versión y configuración del autor.
├── default.css           # Hoja de estilos global con la paleta de colores Kurayami.
├── dash.html             # Dashboard personalizado optimizado con lógica nativa.
└── partials/
    └── footer.html       # Componente dinámico de pie de página con redirección pro.
```

## 🛠️ Instalación en tu VPS
Para desplegar este tema en tu infraestructura de servidores, sigue estos sencillos pasos desde tu terminal o entorno de desarrollo.

1. Accede a la carpeta de temas de tu proyecto:
```bash
cd (tu_carpeta)/themes
```

2. Clona este repositorio directamente dentro del directorio:
```bash
git clone https://github.com/Dev-FelixOfc/Kurayami
```

3. **Verificación:**
Asegúrate de que la propiedad del tema en tu configuración apunte a Kurayami. El servidor Express detectará automáticamente el archivo dash.html y los parciales internos al arrancar.

👨‍💻 Autor
Félix Ofc — Developer & admin principal
Proyecto Base: API Kazuma
<p align="center">MIT License • © 2026 Kazuma API</p>

