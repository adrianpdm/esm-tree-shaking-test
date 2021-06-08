# ESM Tree Shaking Test (Webpack)

## Pengantar
Projek ini dimaksudkan untuk memberikan studi kasus singkat terkait penggunaan:
- Named import terhadap modul berbentuk CommonJS
  ```javascript
  import { camelCase } from 'lodash'
  ```

- Direct import terhadap modul berbentuk CommonJS
  ```javascript
  import camelCase from 'lodash/camelCase'
  ```

- Named import terhadap modul berbentuk ESModule
  ```javascript
  import { camelCase } from 'lodash-es'
  ```

... dan pengaruhnya terhadap besar bundle.


## Cara Penggunaan
1. Clone project
2. Run `yarn && yarn build:all`
3. Browser akan otomatis membuka laman hasil analisis bundle untuk masing-masing studi kasus.

## Info Output Analisis
1. named-import.html

    Ini adalah report untuk bundle yang dihasilkan dari **named import terhadap CommonJS**.

2. direct-import.html

    Ini adalah report untuk bundle yang dihasilkan dari **direct import terhadap CommonJS**.

3. named-import-esm.html
    Ini adalah report untuk bundle yang dihasilkan dari **named import terhadap ESModule**.
