# public-land-app
A web application for adventure seekers who are looking for public lands in the USA. 

## User Story

```md
AS AN 
I WANT 
SO THAT 
```

## Acceptance Criteria

```md

```

## Usage




## Notes

### Getting Started (for my personal use)...

### When you would like to scaffold a new `vite` application on your own, follow these steps

1. In the command line, navigate to the desired parent folder and run `npm create vite@latest`.

    * 🔑 *Note*: This command will automatically create a sub-folder which will house your React application; you do not need to perform a `mkdir` command to create one manually.

2. Enter the desired name of your new project folder.

3. From the first list of options, select your framework; I'll be using `React`.

4. From the second list of options, select your variant; I'll be using `JavaScript`.

5. `cd` into your newly created project folder and run `npm install`.

    * later I'll add additional NPM packages to our `vite` apps such as 'bootstrap', 'dotenv', and 'axios'.

6. Run `npm dev`/`npm run dev` and navigate to the prompted URL to see the app.

### Further customization (Recommended)

1. Navigate to `package.json` and modify the `scripts` object so that it looks like this example:

```json
  "scripts": {
    "dev": "vite",
    "start": "vite",
    "build": "vite build",
    "lint": "eslint src --ext js,jsx --report-unused-disable-directives --max-warnings 0",
    "preview": "vite preview"
  },
```

* Note the addition of the `"start": "vite"` script.

2. Navigate to the `vite.config.js` file and edit the export object so that it looks like this example:

```js
export default defineConfig({
  plugins: [react()],
  server: {
    port: 3000,
    open: true
  }
})
```

## Links

[GitHub Repo](https://github.com/Gera1313/react-portfolio-2)

[Deployed Site](https://gerardoperez.netlify.app) 

## Licenses

## [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)