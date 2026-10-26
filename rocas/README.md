# Terra Lab
Juego educativo del ciclo de las rocas para alumnado de 15 años en adelante. Cinco misiones, modo libre, colección geológica, pistas y sonido opcional. Aplicación estática sin dependencias de ejecución; el servidor utiliza Node.js 20 o posterior.

## Ejecutar

```sh
npm start
```

El servidor escucha en `0.0.0.0:3000`. Se puede cambiar el puerto con `PORT`. Pruebas del modelo geológico: `npm test`. No requiere claves ni servicios externos. Las tipografías de Google son opcionales; hay alternativas locales. El paisaje se incluye como recurso local generado para este proyecto.

## Uso

Selecciona un proceso y pulsa «Aplicar proceso». Una elección incorrecta ofrece una explicación y permite reintentar sin penalización. Cada misión completada aporta 100 puntos. El modo libre permite seleccionar un material pulsando las etiquetas del paisaje y explorar otras rutas; no altera los puntos de las misiones. La colección y la guía amplían los conceptos.

Modelo didáctico simplificado: los procesos representan escalas geológicas y no duraciones físicas calculadas. La compactación y cementación modelan la litificación de sedimentos detríticos; no abarcan todas las vías químicas o biológicas. La fusión puede ser parcial. El metamorfismo ocurre en estado sólido.

## Web en un único archivo

Ejecuta `npm run build` para generar `dist/index.html`. Incluye el código, los estilos y el paisaje en un único HTML, sin peticiones externas. Se puede abrir directamente en un navegador, incluso sin conexión. Para publicarlo, sube ese archivo como `index.html` a cualquier alojamiento web estático. No necesita servidor Node.js en el alojamiento.
