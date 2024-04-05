Inside of this project, you'll see the following folders and files:

```text
/
├── public/
│   ├── backgrounds/
│   │   └── bg-cafe.jpg
│   │   └── vector.svg
│   ├── icons/
│   │   └── Star_fill.svg
│   │   └── Star.svg

├── src/
│   ├── components/
│   │   └── CoffeeCard.astro
│   ├── helpers/
│   │   └── formatNum.ts
│   ├── layouts/
│   │   └── Layout.astro
│   ├── pages/
│   │   └── index.astro
│   ├── types/
│   │   └── index.astro
│   └── env.d.ts
└── package.json
```

Any static assets, like images, can be placed in the `public/` directory.

## 🧞 Commands

All commands are run from the root of the project, from a terminal:

| Command                   | Action                                           |
| :------------------------ | :----------------------------------------------- |
| `npm install`             | Installs dependencies                            |
| `npm run dev`             | Starts local dev server at `localhost:4321`      |
| `npm run build`           | Build your production site to `./dist/`          |
| `npm run preview`         | Preview your build locally, before deploying     |
| `npm run astro ...`       | Run CLI commands like `astro add`, `astro check` |
| `npm run astro -- --help` | Get help using the Astro CLI                     |

## 👀 Want to learn more?

Feel free to check [our documentation](https://docs.astro.build) or jump into our [Discord server](https://astro.build/chat).
