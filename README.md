# Google-search-clone

This is a small Google-like search UI built with React and Vite.

Deployment
- Vercel: the project may encounter a "Permission denied" when running the default `vite` binary during build. To avoid that, the `build` script in `package.json` was changed to:

```
node ./node_modules/vite/bin/vite.js build
```

- To deploy on Vercel: push your branch and Vercel will run `npm run build`. If you still see issues, try installing dependencies without omitting devDependencies, or add `vite` to `dependencies`.

Development
- Run `npm install` then `npm run dev`.

Files
- `src/` — React source
- `index.html` — App entry
