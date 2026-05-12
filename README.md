# NexoColab – Página de Descarga

Página web estática para la descarga del APK de **NexoColab**, una aplicación móvil P2P para el préstamo organizado de objetos subutilizados en comunidades locales.

Desarrollada como parte del proyecto de grado del Semillero de Investigación SIIANTEC – Ingeniería de Sistemas, TEINCO (2026).

---

## 🚀 Despliegue en GitHub Pages

1. Sube el archivo `index.html` a un repositorio de GitHub.
2. Ve a **Settings → Pages**.
3. En **Source**, selecciona la rama `main` y la carpeta `/ (root)`.
4. Guarda. En unos segundos tu página estará disponible en:

```
https://<tu-usuario>.github.io/<nombre-del-repo>/
```

---

## 🔧 Cambiar el enlace del QR

Abre `index.html` con cualquier editor de texto y busca esta línea cerca del final del archivo:

```js
text: "https://expo.dev/artifacts/eas/ojgoHUDSv5hHQZsgUMjvqU.apk",
```

Reemplaza la URL con el nuevo enlace de descarga. El QR se regenera automáticamente al cargar la página.

También actualiza el botón de descarga directa buscando:

```html
<a class="btn-download" href="https://expo.dev/artifacts/eas/ojgoHUDSv5hHQZsgUMjvqU.apk" ...>
```

Y reemplaza el mismo enlace ahí.

---

## 📁 Estructura del repositorio

```
/
└── index.html      # Página completa (logo, QR y estilos todo en un solo archivo)
└── README.md
```

> El logo de NexoColab está incrustado directamente en el HTML en base64, por lo que no se necesitan archivos de imagen externos.

---

## 🛠 Tecnologías

- HTML5 / CSS3 / JavaScript vanilla
- [QRCode.js](https://github.com/davidshimjs/qrcodejs) – generación del QR en el cliente
- Google Fonts (Syne + DM Sans)
- Sin frameworks, sin dependencias locales

---

## 👥 Equipo

| Nombre | Rol |
|---|---|
| Andres Patiño | Desarrollador |
| Jordan Espinosa | Desarrollador |
| Maicol Cortés | Desarrollador |

**Docente líder:** Carolina Torres  
**Docente de investigación:** Víctor Guzmán  
**Institución:** Corporación Tecnológica Industrial Colombiana – TEINCO  
**Semillero:** SIIANTEC – Semillero de Investigación en Innovación y Aplicación de Nuevas Tecnologías
