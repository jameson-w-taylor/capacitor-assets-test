Reproduction Steps:
1. Run `npm install`
1. Run `npm run assets`
1. Notice CLI output (7 files deleted, 14 files created seemingly duplicates?)
1. Open `public/` directory, notice `manifest.json` exists from Ionic starter template but `public/icons` was not created and no files were actually generated
1. Run `npm run assets` a second time
1. Notice CLI output (14 files deleted, 14 files created)
1. Open `public/` directory, notice no files were actually created
1. Delete `public/manifest.json`
1. Run `npm run assets` a third time
1. Notice CLI output (7 files deleted, 14 files created)
1. Open `public/` directory, notice `manifest.webmanifest` was created but `public/icons` was not and no files were actually generated