# Jekyll Stuff

All CSS is written via the `styles.scss` file.

Then the files go through concatenation, compression, and auto-prefixing. They get output to styles.css.

`npm run build:css` to build the css and compile it into the styles.css file.

When serving locally using `jekyll serve`, your paths to assets are different then when they go into production. When your site is being served locally, your path to assets will look like `/css/styles.css`.

However, when the site is being served by GitHub Pages, you will need to prepend the repository name like so `/miriamforeducation/css/styles.css`.

## Social Links

https://www.facebook.com/MiriamGCumminsforEducation

