# InstallTypescript


Ini adalah panduan langkah demi langkah untuk menginstal typescript.

## Instalasi

1. **Buat Project Baru**: Buatlah folder project baru dan buka terminal di dalamnya.
    ```bash
    mkdir instalation-ts
    cd instalation-ts
    ```
2. **Masuk VSCode**: Jalankan perintah untuk masuk VSCode di project Anda.
    ```bash
    code .
    ```
2. **Inisialisasi Node.js**: Jalankan perintah untuk menginisialisasi project Node.js.
    ```bash
    npm init -y
    ```
   ## Tampilan setelah di init
   
  > {
  
  >"name": "instalation-ts",
  
  >"version": "1.0.0",
  
  >"description": "",
  
  >"main": "index.js",
  
  >"scripts": {
  
   > "test": "echo \"Error: no test specified\" && exit 1"
  
  >},
  
  >"keywords": [],
  
  >"author": "",
  
  >"license": "ISC"
> }



4. **Instalation Typescript**: Install Typescript.
    ```bash
    npm install typescript --save-dev
    ```

5. **Konfigurasi Typescript**: Buat file konfigurasi Typescript.
    ```bash
    npx tsc --init
   ```
    Add the paths to all of your template files in your (`tsconfig.json`)
   ```
   target: es2016
    module: commonjs
    strict: true
    esModuleInterop: true
    skipLibCheck: true
    forceConsistentCasingInFileNames: true
    ```


7. **Buat Folder src dan file Typescript**
    
    Buat folder src dan didalamnya buat file typescript (`script.ts`).

8. **Write your code**
    ```
    function greet(name: string) {
    return `Hello, ${name}!`
    }

    const message = greet("yasir")
    console.log(message)
    ```
9. **Compile your code**
    ```
    npx tsc
    ```
10. **Setelah compile file ts ke js kemudian run**
    ```
    node script.js
    ```
11. **Output**
    ```
    Hello, yasir!
    ```

## PLUGIN
## Yasir Rizqi