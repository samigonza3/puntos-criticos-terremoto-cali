# Puntos de donación

Directorio comunitario de puntos de edificios afectados y los insumos que se necesitan en cada uno.
App de un solo archivo (React vía CDN, sin build). Se despliega arrastrando `index.html` a Netlify.

## Cómo actualizar la información

1. Abre `index.html`.
2. Edita el bloque marcado `EDITA AQUI` al inicio del `<script>`:
   - `ACTUALIZADO`: fecha visible en el encabezado.
   - `NECESIDADES_GENERALES`: insumos base.
   - `ALERTA`: mensaje rojo destacado (deja `""` para ocultarlo).
   - `PUNTOS`: agrega, edita o borra puntos. Cada punto acepta su propia lista `necesidades`.
3. Guarda, haz commit y push. Si Netlify está conectado al repo, publica solo.

## Deploy

- Rápido: arrastra `index.html` a app.netlify.com (drag and drop).
- Con repo: conecta este repositorio en Netlify. Sin comando de build, carpeta de publicación `.` (raíz).
