# turku-wordcamp-css
CSS for https://2018.turku.wordcamp.org

### Remote CSS for WordCamp site
Editing the layout for WordCamp sites are done by just editing the CSS. This repo contains CSS for our WordCamp in Turku. The base for the css is copied from Noord-Nederland WordCamp, then converted to SCSS for cleaner editing, so the file might contain some extra lines..

## How to edit
Edit the SCSS file in sass folder. Then compile it to CSS with:
`gulp sass`
Or run the watcher which compiles CSS files automatically when the file is edited:
`gulp sass:watch`

## How to use
The CSS is imported automatically to the site :).