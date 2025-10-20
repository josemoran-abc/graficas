# Gráficas para embeber en ArcGIS Experience Builder

Este repositorio contiene una página **index.html** con la gráfica *"Composición · Regeneración natural (individuos)"* lista para publicarse con **GitHub Pages** y compartirse mediante enlace público.

## Publicación rápida en GitHub Pages

1. Cree un repositorio nuevo en GitHub (por ejemplo: `graficas-restauracion`).
2. Descargue este archivo ZIP y **cárguelo** al repositorio (botón *Upload files*).
3. Asegúrese de que el archivo `index.html` esté en la raíz del repositorio.
4. Vaya a **Settings → Pages** y en *Build and deployment* seleccione:
   - **Source**: *Deploy from a branch*
   - **Branch**: `main` (o `master`) y carpeta `/ (root)`
5. Guarde. GitHub generará un enlace público del tipo:
   `https://USUARIO.github.io/NOMBRE_DEL_REPO/`
6. Pruebe el enlace en un navegador. Si carga correctamente, ya puede **embeber** ese URL en un *Embed widget* de **Experience Builder**.

> **Nota**: Si el repositorio aún no tiene la rama `main`, suba los archivos y GitHub la creará. La activación de Pages puede tardar 1–2 minutos tras el primer push.

## Cómo embeber en Experience Builder

Use un *Embed* o *IFrame* con un alto suficiente, por ejemplo:

```html
<iframe
  src="https://USUARIO.github.io/NOMBRE_DEL_REPO/"
  width="100%"
  height="520"
  style="border:0;"
  loading="lazy"
  referrerpolicy="no-referrer-when-downgrade"
  allowfullscreen>
</iframe>
```

## Contenido de este paquete

- `index.html` → página principal (gráfica con Chart.js y etiquetas).
- `Comp_Reg_Nat.html` → copia del mismo contenido con el nombre original.
- `.nojekyll` → asegura que GitHub Pages sirva los archivos sin procesar.

---
Generado: 2025-10-20 17:27:21
