# Tailwind css configuration
1. npm i tailwindcss gatsby-plugin-postcss autoprefixer
2. ```js
   - module.exports = {
        plugins: [
          {
            resolve: "gatsby-plugin-postcss",
            options: {
              postCssPlugins: [require("tailwindcss"), require("autoprefixer")],
            },
          },
        ],
    }
  ```
3. tailwind config files
    + npx tailwindcss init
    + npm i gatsby-plugin-purgecss