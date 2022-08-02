# Setup

### Project overview

Once you have downloaded the archive and opened it, you will find a couple of folders with code and configuration files.

    ├── build/                              # Compiled files
    ├── public/                             # Static files (fonts, images, etc.)
    ├── src/                                # Source files - contains all the sources
    │   ├── config/                         # Contains sass files
    │   │   ├── continents.json             # JSON file of each continents
    │   │   ├── countries.json              # JSON file of countries
    │   │   ├── pins.json                   # JSON file of pins coordinates
    │   │   ├── related-countries.json      # JSON file of related countries
    │   ├── styles/                         # Contains sass files
    │   │   ├── index.scss                  # Main sass file for styling
    │   ├── templates/                      # Contains templates used in map
    │   │   ├── child-map-modal.html        # HTML template for modals
    │   │   ├── child-map.html              # HTML template for map
    │   │   ├── main.html                   # HTML template for main
    │   │   ├── map-africa.html             # HTML template for Africa map
    │   │   ├── map-america.html            # HTML template for America map
    │   │   ├── map-asia.html               # HTML template for Asia map
    │   │   ├── map-europe.html             # HTML template for Europe map
    │   │   ├── map-global.html             # HTML template for Global map
    │   ├── App.js                          # Root component
    │   ├── demo.html                       # HTML for demo/preview
    │   ├── index.js                        # Main entry point
    └── README.md
    └── ...

> This is an overview of the most important files and folders in your project. Other files are for webpack config, node_modules, etc.

### Dependencies installation

Install the project dependencies by running one of the following commands:

```
# using npm >7
npm install --legacy-peer-deps

# using pnpm
pnpm install

# using yarn
yarn install
```

### Setup your IDE

The recommended IDE setup is [VSCode](https://code.visualstudio.com/) if you want to get the best possible experience of customizing this software.

### Start in development mode

To start the development server, run one of the following commands:

```
# using npm >7
npm run start

# using pnpm
pnpm start

# using yarn
yarn start
```

This will run on **localhost:8080** via browser.