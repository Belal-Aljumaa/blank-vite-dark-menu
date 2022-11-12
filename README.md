# blank-vite-dark-menu

This is a minimal React site created with Vite with an implemented React Router menu.

![grafik](https://user-images.githubusercontent.com/92271729/201470999-311057c9-73d5-4d34-ab0b-b6cfaf7c8b5b.png)

## includes:

- TypeScript
- Sass
- React Router (v6) 
- only one Sass file (`App.scss`) - the file `index.css` was deleted
- CLI with page component creator: `npm run cp`
- page-load flicker bug fixed in index.html:
```
  <style>
    body {
      background-color: #333;
    }
  </style>
```

## how to install

- download zip
- copy all files to new directory, e.g. `/home/yourname/projects/site001`
- open VSCode in that directory (`code .`)
- `npm i`
- `npm run dev`
