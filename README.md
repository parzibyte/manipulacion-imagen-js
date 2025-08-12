# manipulacion-imagen-js
Convertir imagen a escala de grises, b/n y b/n con Floyd-Steinberg Dithering

## Modificando

1. `npm install`
2. `npm run dev`

## Compilando para producción
1. `npm run build`
2. Distribuye el contenido de `dist`

## Subiendo con rsync (caso propio)
Primero un dry run:

```bash
rsync -rvnzi --delete dist/ usuario@servidor.com:/var/www/misitio/apps/color-imagen-js
```
Luego de confirmar, sin dry run:

```bash
rsync -rvzi --delete dist/ usuario@servidor.com:/var/www/misitio/apps/color-imagen-js
```

## Versión de Node
Node: v24.5.0