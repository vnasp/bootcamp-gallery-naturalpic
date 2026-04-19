# NaturalPic Gallery

Photo gallery built with React featuring search functionality and a favorites system. Users can browse nature photographs, search by keyword, and save their favorite images.

> Academic project developed during the Full Stack JavaScript Bootcamp at Desafío LATAM.

### Preview

https://vnasp.github.io/bootcamp-gallery-naturalpic/

### Features

- Browse nature photography gallery with responsive grid
- Search photos by keyword
- Add/remove photos from favorites list
- Persistent favorites with Context API
- Client-side routing with 404 page
- Data sourced from local JSON API (Pexels format)

### Technologies

- React 18
- React Router 6
- React Context API
- Bootstrap 5
- Vite

### Project Structure

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
