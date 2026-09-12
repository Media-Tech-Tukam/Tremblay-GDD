# Los Tremblay y el Cofre Esmeralda — GDD

Game Design Document publicado como página web estática (un solo archivo `index.html`).

## Publicar / actualizar

1. Reemplaza `index.html` por la versión nueva.
2. Si agregas imágenes, ponlas en `images/` y referencia `images/nombre.jpg` desde el HTML (o pide que Claude las incruste).
3. `git add -A && git commit -m "Actualiza GDD" && git push`

GitHub Pages sirve automáticamente el `index.html` de la raíz de `main` una vez esté activado en **Settings → Pages**.

## Fotos de los 4 personajes principales

En la sección **Personajes** del GDD, las fichas de Étienne, Éliane, Julien y Lucía se pueden hacer clic y abren un modal de ancho completo con su foto y toda la información.

Para poner o cambiar una foto, solo hay que **agregar el archivo con el nombre exacto** en esta carpeta (no hace falta tocar el HTML):

```
images/personajes/etienne.jpg
images/personajes/eliane.jpg
images/personajes/julien.jpg
images/personajes/lucia.jpg
```

- Formato `.jpg` (si usas `.png` u otro formato, avisa para ajustar la referencia en el HTML).
- Recomendado: foto vertical (relación 4:5 o similar), al menos 800px de ancho.
- Mientras no exista el archivo, el modal muestra un círculo con la inicial del nombre en vez de foto rota.
- Después de agregar las imágenes: `git add -A && git commit -m "Agrega fotos de personajes" && git push`.
