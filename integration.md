# Integration

Once you have setup the project and able to customized it, you may implement this to your website by following the instruction below.

### Generate build version

Run the following command in terminal to generate the build version of the project.

```
# using npm >7
npm run build

# using pnpm
pnpm build

# using yarn
yarn build
```


### Build folder

After the generating process is done in terminal, you will see the files generated inside **build/** folder.

    ├── public/                             # Static files (fonts, images, etc.)
    │   ├── bundle.chunk.js                 # Webpack-specific to manage the bundling process
    │   ├── bundle.chunk.js.map             # Source maps for bundle.chunk.js
    │   ├── bundle.css                      # Bundled and compiled styles
    │   ├── bundle.css.map                  # Source maps for bundle.css
    │   ├── bundle.js                       # Related codes packaged into a single file
    │   ├── bundle.js.map                   # Source maps for bundle.js
    │   ├── index.html                      # HTML for preview
    └── ...

To integrate this to your website, go to your web server where your website is hosted and upload the build folder inside the directory of your website with using File manager.

### Link to CSS and JS

Once the bundle is uploaded to your website, you must link the CSS and JS files into the page where you want to display the map.

```
# Add inside <head> tag, ex.
<link rel="stylesheet" type="text/css" href="path/to/map/bundle.css" />

# Add before </body> tag, ex.
<script src="path/to/map/bundle.chunk.js"></script>
<script src="path/to/map/bundle.js"></script>
```

### Add DIV tag

Place a DIV tag with an id of "wtsim-container" somewhere in the page where you want the map to be rendered.

```
<div id="wtsim-container"></div>
```

### Settings

You may use the settings below to configure your map. Just add this anywhere in your script.

##### window.interactiveMap2_Countries
**Type:** Object\
**Default:** {}\
**Example:** {"availableCountries":["AL"],"countryData":{"AL":{"navigationItems":[{"name":"Real Estate Guide","url":"link-to-pdf","type":"pdf"}]}}}

This is data that will be rendered on map. You can also use data-attribute **data-countries** in div tag you created.

##### window.WTSIM_MAIN_TITLE
**Type:** String\
**Default:** '[insert title]'

This will be shown on the top of global map.

##### window.WTSIM_MAIN_DESCRIPTION
**Type:** String\
**Default:** '[insert description]'

This will be shown below the title of global map.

##### window.WTSIM_DEFAULT_COLOR
**Type:** String\
**Default:**  '#dcdfe1'

This will be the color of the countries that are not highlighted.

##### window.WTSIM_ACCENT_COLOR
**Type:** String\
**Default:**  '#cc1f36'

This will be the color of the countries that are highlighted.




