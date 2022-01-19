# Testing the PouchDB activeTasks API

Test the new activeTasks API in your browser.

1. Build PouchDB via `$ npm run build`
2. Symlink the dist files to the pouchdb build files via (e.g., assuming the PouchDB directory resides next to this repo)
   1. `pouchdb.js`: `$ ln -s ../pouchdb/packages/node_modules/pouchdb/dist/pouchdb.js`
   2. `pouchdb.indexeddb.js`: `$ ln -s ../pouchdb/packages/node_modules/pouchdb/dist/pouchdb.indexeddb.js`
   2. `pouchdb.find.js`: `$ ln -s ../pouchdb/packages/node_modules/pouchdb/dist/pouchdb.find.js`
3. Install dependencies via `$ npm install`
4. Run the local server via `$ npm run serve` and head to http://localhost:3000/

The website will tell you about the available commands.
