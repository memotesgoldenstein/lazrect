# **LAZRECT**

## **CLI Commands**

> ```bash
> # install dependencies
> npm install
>
> # serve with hot reload at localhost:8080
> npm run dev
>
> # build for production with minification
>
> npm run build
>
> # test the production build locally>
> npm run serve
>
> # run tests with jest and enzyme
> npm run test
> ```

For detailed explanation on how things work, checkout the [CLI Readme](https://github.com/developit/preact-cli/blob/master/README.md).

## **Tailwindui**

> ```bash
>
> # install tailwindcss dependencies
>  npm install tailwindcss@latest
>
> ```
>
> ```html
> // add default font family
> <link rel="stylesheet" href="https://rsms.me/inter/inter.css" />
> ```
>
> ```javascript
> // tailwind.config.js
> const defaultTheme = require("tailwindcss/defaultTheme");
>
> module.exports = {
>   theme: {
>     extend: {
>       fontFamily: {
>         sans: ["Inter var", ...defaultTheme.fontFamily.sans],
>       },
>     },
>   },
>   plugins: [require("tailwindcss"), require("autoprefixer")],
> };
> ```
>
> ```bash
>
> # install Headless UI dependencies
> npm install @headlessui/react @heroicons/react
> ```
>
> ```javascript
> // postcss.config.js
> module.exports = {
>   plugins: {
>     "postcss-import": {},
>     tailwindcss: {},
>     autoprefixer: {},
>   },
> };
> ```
>
> ```javascript
> //package.json
> "plugins": [
>    [
>      "@babel/plugin-transform-react-jsx",
>      {
>        "pragma": "h",
>        "pragmaFrag": "Fragment"
>      }
>    ]
>  ],
>  "skipLibCheck": true
> ```
