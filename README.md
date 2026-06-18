# Diccionario Griego Koine protegido

Carpeta lista para publicar en GitHub Pages.

## Archivos publicables

- `index.html`: pantalla de acceso y descifrado.
- `payload.manifest.json`: metadatos del cifrado.
- `payload/chunk-*.txt`: partes de la aplicación cifrada.
- `robots.txt`: pide a buscadores no indexar.
- `.nojekyll`: evita procesamiento de Jekyll.

## Importante

No subas el HTML original sin cifrar al repositorio público.

Para reconstruir con una clave propia desde la carpeta del proyecto:

```bash
DICCIONARIO_CLAVE="tu-clave-larga" /Users/juanfra/.cache/codex-runtimes/codex-primary-runtime/dependencies/node/bin/node work/build_github_pages_secure.mjs
```
