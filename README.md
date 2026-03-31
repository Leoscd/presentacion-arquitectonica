# Landing de Proyecto Arquitectonico
### Kit generado con SoyLeo AI — soyleoai.com

---

## Que contiene este repositorio

```
/
├── index.html       — Landing page lista para publicar
├── proyecto.json    — Datos del proyecto (editar aqui)
├── CLAUDE.md        — Instrucciones para Claude Code
├── README.md        — Este archivo
└── assets/
    ├── video.mp4
    ├── planta3d.png
    ├── cocina-comedor.png
    ├── habitacion.png
    └── baño.png
```

---

## Publicar en GitHub Pages (5 pasos)

**Paso 1 — Crear repositorio en GitHub**
- Ir a github.com/new
- Nombre: `landing-[nombre-proyecto]`
- Visibilidad: **Public**
- NO marcar "Initialize with README"
- Crear repositorio

**Paso 2 — Subir los archivos**

Desde la carpeta del proyecto, abrir terminal y ejecutar:

```bash
git init
git add .
git commit -m "Landing inicial del proyecto"
git branch -M main
git remote add origin https://github.com/TU-USUARIO/landing-TU-PROYECTO.git
git push -u origin main
```

Reemplaza `TU-USUARIO` y `TU-PROYECTO` con tus datos reales.

**Paso 3 — Activar GitHub Pages**
- Ir al repositorio en GitHub
- Click en **Settings** (engranaje)
- En el menu lateral: **Pages**
- Source: **Deploy from a branch**
- Branch: **main** / **(root)**
- Click **Save**

**Paso 4 — Esperar 1-2 minutos**

GitHub Pages tarda unos minutos en procesar el primer deploy.

**Paso 5 — Tu URL publica**

```
https://TU-USUARIO.github.io/landing-TU-PROYECTO/
```

Esa URL la compartis con el cliente, la mandas por WhatsApp, o la incluís en tu propuesta comercial.

---

## Personalizar para otro proyecto

1. Editar `proyecto.json` con los datos del nuevo proyecto
2. Reemplazar las imagenes en `assets/` con las del nuevo proyecto
3. Abrir Claude Code en esta carpeta y ejecutar:

```
Lee proyecto.json y CLAUDE.md, luego regenera index.html con los nuevos datos.
```

4. Hacer commit y push. GitHub Pages se actualiza automaticamente.

---

## Actualizar datos rapidamente

Para cambiar cualquier dato sin abrir Claude Code, editas `proyecto.json` directamente y luego en Claude Code:

```
Regenera index.html leyendo el proyecto.json actualizado.
```

---

## Creditos

Generado con **SoyLeo AI**
Arq. Leonardo Diaz | Tucuman, Argentina
[soyleoai.com](https://soyleoai.com) | [@soy.leo_ai](https://instagram.com/soy.leo_ai)
