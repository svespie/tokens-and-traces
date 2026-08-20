# Tokens & Traces — Stan Vespie

Personal research blog and technical notes on machine learning mechanics, computer security vulnerabilities, autograd runtimes, and systems engineering.

Hosted live at [stanvespie.com](https://stanvespie.com).

---

## Writing Workflow

Add new articles as `.md` or `.mdx` files in:
`src/content/blog/`

---

## Project Structure

```text
├── public/
├── src/
│   ├── assets/
│   ├── components/
│   ├── content/
│   │   └── blog/
│   ├── layouts/
│   └── pages/
├── astro.config.mjs
├── package.json
├── tsconfig.json
└── README.md
```

* Pages and routes are located in `src/pages/`.
* Components live in `src/components/`.
* Blog posts and Markdown collections live in `src/content/blog/`.

---

## Commands

All commands are run from the root of the project:

| Command | Action |
| :--- | :--- |
| `npm install` | Installs project dependencies |
| `npm run dev` | Starts local dev server at `localhost:4321` |
| `npm run build` | Builds production static site to `./dist/` |
| `npm run preview` | Previews production build locally |
