# Galería NaturalPic

Galería fotográfica interactiva de naturaleza con buscador y sistema de favoritos. Los usuarios pueden explorar fotografías, buscar por palabra clave y guardar sus imágenes favoritas.

> Nota: Este es un proyecto académico desarrollado durante el Bootcamp Full Stack JavaScript de Desafío LATAM.

## Vista previa

[Ver en GitHub Pages](https://vnasp.github.io/bootcamp-gallery-naturalpic/)

## Funcionalidades

- Galería de fotos de naturaleza con grilla responsiva
- Buscador de fotos por palabra clave
- Agregar y quitar fotos de la lista de favoritos
- Estado global de favoritos con Context API
- Navegación con React Router y página 404
- Datos desde archivo JSON local (formato Pexels)

## Tecnologías

- React 18
- React Router 6
- React Context API
- Bootstrap 5
- Vite

## Estructura del Proyecto

```
src/
├── components/
│   ├── FavoriteEmpty.jsx
│   ├── FavoriteGrid.jsx
│   ├── Footer.jsx
│   ├── Gallery.jsx
│   ├── IconHeart.jsx
│   ├── Navigation.jsx
│   └── Search.jsx
├── context/
│   └── PhotosContext.jsx
├── views/
│   ├── Favorites.jsx
│   ├── Home.jsx
│   └── NotFound.jsx
├── App.jsx
└── main.jsx
```
