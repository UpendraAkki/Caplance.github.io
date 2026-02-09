## Lumesonic

A modern, responsive web application built with **React**, **TypeScript**, and **Tailwind CSS**, bundled with **Vite** and a component system based on **shadcn-ui**.  
This repository contains the full frontend codebase for the Lumesonic web app.

---

### Project links

- **Production URL**: https://57934188.lumesonic.pages.dev  
- **Cloudflare Pages project**: https://lumesonic.pages.dev  
- **GitHub repo (Caplance GitHub Pages)**: [`UpendraAkki/Caplance.github.io`](https://github.com/UpendraAkki/Caplance.github.io.git)  
- **Overview video (YouTube)**: [`https://youtu.be/LDq4B2bHaII`](https://youtu.be/LDq4B2bHaII)

---

### Features

- **Modern frontend stack** with React + TypeScript + Vite
- **Tailwind CSS** for rapid, utility‑first styling
- **shadcn-ui** component primitives for consistent UI
- **Fast local development** with hot module reloading
- **Cloudflare Pages** deployment workflow (via `wrangler`)

---

### Getting started

#### Prerequisites

- **Node.js** (LTS recommended)  
- **npm** (bundled with Node.js)

#### Installation

```sh
# Clone the repository
git clone <YOUR_GIT_URL>

# Enter the project directory
cd <YOUR_PROJECT_NAME>

# Install dependencies
npm install
```

#### Running the app locally

```sh
npm run dev
```

This will start the Vite dev server. Open the URL printed in the terminal (usually `http://localhost:5173`) in your browser.

---

### Available npm scripts

- **`npm run dev`**: Start the Vite development server.
- **`npm run build`**: Create an optimized production build in the `dist` folder.
- **`npm run preview`**: Preview the production build locally (after running `npm run build`).
- **`npm run deploy`**: Convenience command for deploying to Cloudflare Pages (see below).

---

### Deployment

#### Quick deploy (recommended)

```sh
npm run deploy
```

#### Manual deploy to Cloudflare Pages

```sh
# 1. Build the project
npm run build

# 2. Deploy the built assets
npx wrangler pages deploy dist --project-name=lumesonic
```

#### First-time Cloudflare setup

1. Install dependencies: `npm install`  
2. Build the project: `npm run build`  
3. Deploy with Wrangler:  

   ```sh
   npx wrangler pages deploy dist --project-name=lumesonic
   ```

The live deployment is currently available at: https://57934188.lumesonic.pages.dev

---

### UI screenshots

All screenshots are stored under `public/Images`. Below is a gallery of key flows and pages.

#### Landing and navigation

<table>
  <tr>
    <td><img src="public/Images/Screenshot 2026-02-09 192005.png" alt="Landing view 1" /></td>
    <td><img src="public/Images/Screenshot 2026-02-09 192056.png" alt="Landing view 2" /></td>
  </tr>
  <tr>
    <td><img src="public/Images/Screenshot 2026-02-09 192153.png" alt="Navigation and header" /></td>
    <td><img src="public/Images/Screenshot 2026-02-09 192212.png" alt="Hero / call to action" /></td>
  </tr>
</table>

#### Core flows

<table>
  <tr>
    <td><img src="public/Images/Screenshot 2026-02-09 192230.png" alt="Core flow 1" /></td>
    <td><img src="public/Images/Screenshot 2026-02-09 192345.png" alt="Core flow 2" /></td>
  </tr>
  <tr>
    <td><img src="public/Images/Screenshot 2026-02-09 192405.png" alt="Core flow 3" /></td>
    <td><img src="public/Images/Screenshot 2026-02-09 192439.png" alt="Core flow 4" /></td>
  </tr>
  <tr>
    <td><img src="public/Images/Screenshot 2026-02-09 192456.png" alt="Core flow 5" /></td>
    <td><img src="public/Images/Screenshot 2026-02-09 192523.png" alt="Core flow 6" /></td>
  </tr>
</table>

#### Detailed views and states

<table>
  <tr>
    <td><img src="public/Images/Screenshot 2026-02-09 192541.png" alt="Detail view 1" /></td>
    <td><img src="public/Images/Screenshot 2026-02-09 192612.png" alt="Detail view 2" /></td>
  </tr>
  <tr>
    <td><img src="public/Images/Screenshot 2026-02-09 192628.png" alt="Detail view 3" /></td>
    <td><img src="public/Images/Screenshot 2026-02-09 192641.png" alt="Detail view 4" /></td>
  </tr>
  <tr>
    <td><img src="public/Images/Screenshot 2026-02-09 192652.png" alt="Detail view 5" /></td>
    <td><img src="public/Images/Screenshot 2026-02-09 192708.png" alt="Detail view 6" /></td>
  </tr>
  <tr>
    <td><img src="public/Images/Screenshot 2026-02-09 192718.png" alt="Detail view 7" /></td>
    <td></td>
  </tr>
</table>

### Development notes

- The project uses **Vite** for fast builds and HMR.
- UI components are primarily built with **shadcn-ui** and **Tailwind CSS** utilities.
- Configuration for Cloudflare Pages / Wrangler is managed via `wrangler.toml` in the project root.

---

### Contributing

1. Fork the repository.
2. Create a new branch for your changes:

   ```sh
   git checkout -b feature/my-change
   ```

3. Commit and push your work:

   ```sh
   git commit -m "Describe your change"
   git push origin feature/my-change
   ```

4. Open a pull request.

---

### License

This project does not currently specify a license. If you intend to open‑source it, consider adding a `LICENSE` file (e.g. MIT, Apache‑2.0) and updating this section accordingly.
