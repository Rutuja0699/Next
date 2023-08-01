Hit `ctrl + shift + v` to preview

# NextJS Routing

## Intro

- In React, we do client side routing using `react-router-dom` package and there are other packages as well.
- In NextJS routing is and in built feature provided by NextJS framework.
- NextJS has `file-based routing`
- There are two main folders in NextJS `app folder` (v13 and above ignore this for now) and `pages folder` (v12 and above we will use this for now then shift to app folder)

## Folder structure

- Only `app` and `pages` are two special and reserved folders in nextjs.
- we will focus on `pages` for now.
- rest of the folders and files you create as you want like react.

## Pages

- Routing is very easy in NextJS (easier than react).
- Any file or folder you create inside `pages` will automatically become a route in NextJS.

  - `pages/index.jsx` (this will become `localhost:3000/`) // ignore this route '/' for now
  - `pages/home.jsx` (this will become `localhost:3000/home`)
  - `pages/services.js` (this will become `localhost:3000/services`)

- instead of files even folders can become routes

  - `pages/blog/blogPost.jsx` (this will become `localhost:3000/blog/blogPost`)
  - `pages/blog/author/index.jsx` (this will become `localhost:3000/blog/author`)
  - `pages/blog/author/comment.jsx` (this will become `localhost:3000/blog/author/comment`)

- note: `index.jsx` file inside any folder will become route directory of the folder
- for eg: `pages/news/index.jsx` (this will become `localhost:3000/news`)
- and this is same as above `pages/news.jsx` (this will also become `localhost:3000/news`)
- `pages/news/index.jsx` and `pages/news.jsx` are same routes

### To see all the above in action refer pages folder

#### run all the above routes to see those pages and refer every file and folder

#### Note: above files can be .tsx (typescript) or .jsx (javascript)
