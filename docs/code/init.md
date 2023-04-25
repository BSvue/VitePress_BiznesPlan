# init

## w terminalu 

```bash 

mkdir biznesPlan

cd biznesPlan

npm init

npm install --save-dav vitepress

npm install 

```

## zmiany w pliku package.json

```json

    "docs:dev" : "vitepress dev docs",
    "docs:build" : "vitepress build dose",
    "docs:serve" : "vitepress serve docs",

```

### cały plik 

```json

{
  "name": "biznesplan",
  "version": "1.0.0",
  "description": "",
  "main": "index.js",
  "scripts": {
    "docs:dev" : "vitepress dev docs",
    "docs:build" : "vitepress build dose",
    "docs:serve" : "vitepress serve docs",
    "test": "echo \"Error: no test specified\" && exit 1"
  },
  "author": "",
  "license": "ISC",
  "dependencies": {
    "vitepress": "^1.0.0-alpha.73"
  }
}

```