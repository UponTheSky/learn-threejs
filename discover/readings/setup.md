# How to set up the dev environment?
- use [Vite](https://vitejs.dev/) for faster building
  - select `vanilla` > `typescript` when installing

- set up the `vite.config.ts` as the followings:

```ts
import { defineConfig } from 'vite';

export default defineConfig({
  server: {
    open: 'http://localhost:5173' // => this could be updated to be a more sophisticated config
  }
});
```

- install Three.js: `yarn add three && yarn add -D @types/three`

- remove unnecessary files in `src`: `.css`, `.svg`, or `counter.ts`
- modify `main.ts`