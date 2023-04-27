`````md
# Code 

 [>>INIT<<](init) | [>>FILE<<](file)

 [[toc]]

## docs/index.md

````md

# BiznesPlan 
# Stworzenia Strony Z BiznesPlanem 

[[toc]]

## Inicjalizacja projektu [- 3min]
[>>INIT<<](code/init)
```bash

npm run docs:dev


```


## struktura projektów [- 5min]
[>>FILE<<](code/file)

## struktura projektów [- 45min]
[>>CODE<<](code/)

## Domena .pl [- 10min]
### około 10zł
#### za pierwszy rok 
### około 60zł
#### za kolejne lata

## Build projektu [- 1min]
```bash

npm run docs:build


```

## Hosting [max -1h]
#### 0zł


````
::: details PATH
```txt{8}

.
├── docs
│   ├── code
│   │   ├── file.md
│   │   ├── index.md
│   │   └── init.md
│   ├── contact.md
│   ├── index.md <-----
│   └── .vitepress
│       └── config.js
├── package.json
└── package-lock.json


```
:::

## docs/contact.md

```md

# Contact

> telefon 

> email 


```
::: details PATH
```txt{7}

.
├── docs
│   ├── code
│   │   ├── file.md
│   │   ├── index.md
│   │   └── init.md
│   ├── contact.md <-----
│   ├── index.md 
│   └── .vitepress
│       └── config.js
├── package.json
└── package-lock.json


```
:::

## docs/.vitepress/config.js

```js


module.exports = {

title: "BiznesPlan",
themeConfig: {

    nav: [
        {text: "Home" , link : "/"},
        {text: "Code" , link : "/code/"},
        {text: "Contact" , link : "/contact"}
    ],
},

}


```
::: details PATH
```txt{10}

.
├── docs
│   ├── code
│   │   ├── file.md
│   │   ├── index.md
│   │   └── init.md
│   ├── contact.md
│   ├── index.md 
│   └── .vitepress
│       └── config.js <-----
├── package.json
└── package-lock.json


```
:::
## docs/code/file.md

````md

# file

```

.
├── package.json
└── package-lock.json


```

### do ->


```

.
├── docs
│   ├── code
│   │   ├── file.md
│   │   ├── index.md
│   │   └── init.md
│   ├── contact.md
│   ├── index.md
│   └── .vitepress
│       └── config.js
├── package.json
└── package-lock.json


```



````
::: details PATH
```txt{4}

.
├── docs
│   ├── code
│   │   ├── file.md <-----
│   │   ├── index.md
│   │   └── init.md
│   ├── contact.md 
│   ├── index.md 
│   └── .vitepress
│       └── config.js
├── package.json
└── package-lock.json


```
:::
## docs/code/init.md

````md

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
    "docs:build" : "vitepress build docs",
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
    "docs:build" : "vitepress build docs",
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


````
::: details PATH
```txt{6}

.
├── docs
│   ├── code
│   │   ├── file.md 
│   │   ├── index.md
│   │   └── init.md <-----
│   ├── contact.md 
│   ├── index.md 
│   └── .vitepress
│       └── config.js
├── package.json
└── package-lock.json


```
:::
## docs/code/index.md



::: details PATH
```txt{5}

.
├── docs
│   ├── code
│   │   ├── file.md 
│   │   ├── index.md <-----
│   │   └── init.md
│   ├── contact.md 
│   ├── index.md 
│   └── .vitepress
│       └── config.js
├── package.json
└── package-lock.json


```
:::
`````