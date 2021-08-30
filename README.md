# Tailwind-Koala
HomePage https://esterified.github.io/Tailwind-Koala
Instagram Copy https://esterified.github.io/Tailwind-Koala/instagram
## Steps to install TailwindCSS using NPM
- Initialize NPM
- Install tailwindcss using npm
- Initialize tailwindcss config with full config
- Compile the tailwind css file
- Include the tailwind stylesheet in your webpages
- Implement blocks from [TailBlocks](https://tailblocks.cc/).

## Its that Simple!

- ### Initialize NPM
  Run command `npm init -yes`

- ### Install tailwindcss using npm
  Run command `npm install tailwindcss`

- ### Initialize tailwindcss config with full config
  You can add the following scripts in your `package.json` file
  ```@json
  "tailwind-config":"npx tailwindcss init --full",
  "tailwind":"npx tailwindcss -i ./src/tailwind.css -o ./css/tailwind.css",
  ```
  `npx tailwindcss init --full` will generate the `tailwind.config.js` file with all customization ptions for the theme.
- ### Compile the tailwind css file
  `npm run tailwind-config` and
  `npm run tailwind`
- ### Include the tailwind stylesheet in your webpages
  ```@html
  <link href="./css/tailwind.css" rel="stylesheet">
  ```
- ### Implement blocks from [TailBlocks](https://tailblocks.cc/).
  Also visit [Tailwindcss](https://tailwindcss.com/docs/) for more info. 
