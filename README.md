# proyectos

Dashboard estático para seguimiento del portafolio TI 2026.

## Publicación en GitHub Pages

Este repositorio ya incluye un workflow para publicar automáticamente en GitHub Pages cuando hagas push a `main`.

### Pasos

1. Confirmar cambios:

```bash
git status
```

2. Agregar y subir:

```bash
git add .
git commit -m "Configura publicación en GitHub Pages"
git push origin main
```

3. Revisar el despliegue en la pestaña `Actions` del repositorio.

4. Abrir el sitio publicado:

`https://tjdeavila-ctrl.github.io/proyectos/`

## Estructura principal

- `index.html`: entrada principal para GitHub Pages.
- `dashboard_portafolio_ti_2026.html`: dashboard principal.
- `proyectos_xlsx_data.js`: datos base del dashboard.