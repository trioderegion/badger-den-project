# Badger Den Template Project
Template repository for quickstarting FVTT development using the "Badger Den" Rollup plugin.

## Setup
After cloning this repo or one using this as a template, the following commands will build the included "Hello World" module ready for use in Foundry.
```
npm install
npm run release
```

## Example Profiles and NPM Scripts
- `npm run release`: Builds a compressed, "production" version of the module without sourcemaps. Clears output directory and creates both the module files and distribution .zip.
- `npm run test`: Builds a compressed version of the module with sourcemaps. Clears output directory and creates only the module files.
- `npm run dev`: Builds an uncompressed version of the module with sourcemaps. Starts watch mode and monitors/rebuilds on non-static file changes. Does _not_ clear output directory and creates only the module files.
- `npm run dev-once`: Same as `dev`, but does not enable watch mode.
