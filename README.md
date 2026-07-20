# Documentación de Botky

Este repositorio contiene el código fuente de la documentación oficial de **Botky**, desplegada con [Mintlify](https://mintlify.com) en [botky.mintlify.app](https://botky.mintlify.app) y en el dominio personalizado `docs.botky.chat`.

## Estructura

- `docs.json` — configuración del sitio: navegación, colores de marca, logo, favicon y menú contextual.
- Cada carpeta de nivel superior (`flow-builder/`, `omni-channel/`, `channels/`, `automation/`, `content/`, `tools/`, `tickets/`, `booking/`, `workspace-settings/`, `developers/`, etc.) contiene las páginas `.mdx` de esa sección.
- Todas las páginas viven en la **raíz del repositorio** (no dentro de una carpeta `docs/`), siguiendo la convención que espera Mintlify para este proyecto.

## Desarrollo local

Instala el [Mintlify CLI](https://www.npmjs.com/package/mint) para previsualizar los cambios localmente:

```bash
npm i -g mint
```

Desde la raíz del repositorio (donde está `docs.json`):

```bash
mint dev
```

Previsualiza en `http://localhost:3000`.

## Publicar cambios

Los cambios se despliegan automáticamente a producción al hacer push a la rama `main`, a través de la app de GitHub de Mintlify.

## Soporte

¿Dudas sobre la documentación o el producto? Contacta al soporte de Botky.
