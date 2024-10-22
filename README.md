# BlackBird Research 📄

Blackbird Research Club is a small but passionate group of students and professionals who are committed to exploring the latest trends and technologies in cybersecurity and software development. We believe in the power of collaboration and continuous learning to drive innovation and excellence.

## 🚀 Project Structure

Inside of our astro repository, you'll see the following folders and files:

```bash
/
├── public/
│   ├── assets/
│   │   └── logo.svg
│   │   └── logo.png
│   └── favicon.svg
│   └── BlackBird-Research-og.jpg
│   └── robots.txt
│   └── toggle-theme.js
├── src/
│   ├── assets/
│   │   └── socialIcons.ts
│   ├── components/
│   ├── content/
│   │   |  blog/
│   │   |    └── some-blog-posts.md
│   │   └── config.ts
│   ├── layouts/
│   └── pages/
│   └── styles/
│   └── utils/
│   └── config.ts
│   └── types.ts
└── package.json
```

Astro looks for `.astro` or `.md` files in the `src/pages/` directory. Each page is exposed as a route based on its file name.

Any static assets, like images, can be placed in the `public/` directory.

All blog posts are stored in the `src/content/blog` directory.

## 📖 Documentation

Documentation can be read in two formats: _markdown_ & _blog post_.

- Configuration - [markdown](src/content/blog/how-to-configure-blackbird-research-theme.md) | [blog post](https://astro-paper.pages.dev/posts/how-to-configure-blackbird-research-theme/)
- Add Posts - [markdown](src/content/blog/adding-new-post.md) | [blog post](https://astro-paper.pages.dev/posts/adding-new-posts-in-blackbird-research-theme/)
- Customize Color Schemes - [markdown](src/content/blog/customizing-blackbird-research-theme-color-schemes.md) | [blog post](https://astro-paper.pages.dev/posts/customizing-blackbird-research-theme-color-schemes/)
- Predefined Color Schemes - [markdown](src/content/blog/predefined-color-schemes.md) | [blog post](https://astro-paper.pages.dev/posts/predefined-color-schemes/)

## 👨🏻‍💻 Running Locally

You can start using this project locally by running the following command in your desired directory:

```bash
# npm 6.x
npm create astro@latest --template satnaing/astro-paper

# npm 7+, extra double-dash is needed:
npm create astro@latest -- --template satnaing/astro-paper

# yarn
yarn create astro --template satnaing/astro-paper

# pnpm
pnpm dlx create-astro --template satnaing/astro-paper
```

Then start the project by running the following commands:

```bash
# install dependencies
npm run install

# start running the project
npm run dev
```

As an alternative approach, if you have Docker installed, you can use Docker to run this project locally. Here's how:

```bash
# Build the Docker image
docker build -t blackbird-research .

# Run the Docker container
docker run -p 4321:80 blackbird-research
```

## 🧞 Commands

All commands are run from the root of the project, from a terminal:

| Command                                    | Action                                                                                                                           |
| :----------------------------------------- | :------------------------------------------------------------------------------------------------------------------------------- |
| `npm install`                              | Installs dependencies                                                                                                            |
| `npm run dev`                              | Starts local dev server at `localhost:4321`                                                                                      |
| `npm run build`                            | Build your production site to `./dist/`                                                                                          |
| `npm run preview`                          | Preview your build locally, before deploying                                                                                     |
| `npm run format:check`                     | Check code format with Prettier                                                                                                  |
| `npm run format`                           | Format codes with Prettier                                                                                                       |
| `npm run sync`                             | Generates TypeScript types for all Astro modules. [Learn more](https://docs.astro.build/en/reference/cli-reference/#astro-sync). |
| `npm run lint`                             | Lint with ESLint                                                                                                                 |
| `docker compose up -d`                     | Run BlackBird Research on docker, You can access with the same hostname and port informed on `dev` command.                      |
| `docker compose run app npm install`       | You can run any command above into the docker container.                                                                         |
| `docker build -t blackbird-research .`     | Build Docker image for BlackBird Research.                                                                                       |
| `docker run -p 4321:80 blackbird-research` | Run BlackBird Research on Docker. The website will be accessible at `http://localhost:4321`.                                     |

## ✨ Feedback & Suggestions

If you have any suggestions/feedback, you can contact me via [my email](mailto:contact@satnaing.dev). Alternatively, feel free to open an issue if you find bugs or want to request new features.

## 📜 License

Licensed under the MIT License, Copyright © 2023

---

Made with 🤍 by [Sat Naing](https://satnaing.dev) 👨🏻‍💻 and [contributors](https://github.com/satnaing/astro-paper/graphs/contributors).
