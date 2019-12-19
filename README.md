# Vue Pokédex

A Pokédex made for fun in Vue.js.

The Pokédex includes the first 251 Pokémon, with:

- Descriptions and types
- Base statistics
- Special attacks
- Evolutionary forms
- Audio samples

<img src="public/screenshot_v2.png" alt="Vue Pokédex" style="max-width:75%;margin: 0 auto;">

## Getting Started

### Prerequisites

- Node.js &amp; npm

To download Node.js and npm, visit the [Node.js downloads page](https://nodejs.org/en/download/) and select the version labelled **LTS**.

After installing Node.js, run the following command to verify that everything has been installed correctly.

```bash
npm -v && node -v
```

### Running the application

```bash
# Download project dependencies
npm install

# Run the application on localhost:8080
npm run serve
```

### Key files and folders

```
  .
  ├── docs/              # Compiled application for GitHub Pages
  ├── public/            # Static assets
  ├── src/               # Main Vue application files
  |   ├── assets/        # Audio, sprites, global CSS
  |   |   └── ...
  |   ├── components/    # Vue components
  |   ├── json/
  |   |   └── data.json  # Scraped Pokédex data
  |   ├── App.vue
  |   ├── event-bus.js   # Connector to pass data b/n children
  |   └── tests/         # Unit tests
  ├── README.md
  └── package.json       # Requirements for npm installation
```

