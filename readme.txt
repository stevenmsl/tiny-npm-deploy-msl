Publish to NPM
- Package name is unique 
  - "name" in package.json
- Which files to be sent to NPM
  - "files" in package.json
- Split dependencies and devDependencies
  - "dependencies" and "devDependencies"
    in package.json
  - anything in devDependencies will not
    be published to NPM
- Configure the file to run if you are building a CLI
  - bin in package.json 
  - #!/usr/bin/env node in index.ts
- Add a 'prePublish" script
  - prepublishOnly in package.json
  - configure script to run before publishing
- Run "npm publish" 
