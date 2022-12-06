

# Portfolio Website using SASS

#### **SASS (Syntactically Awesome Style Sheet)** is a CSS Precompiler/Preprocessor which enhances the functionality of CSS.

### Setting Up SASS

The browser does not read SASS files that end with *.scss* or *.sass* extensions hence the Files need to be compiled to regular CSS for the browser to render the style.

We Can setup SASS using *npm* or we can use a *GUI* like *Koala* or a *VS Code extension* such as *Live Sass Compiler*

___

### Setting Up using npm

1. Installing [node](https://nodejs.org/en/download/ "node installation") from the official website
2. Create a package.json file in the local working directory 
    ```
    npm init -y
    ```
   This will create a package.json file with default settings

3. Installing node SASS
    ```
    npm install node-sass -D
    ```
   This will install node-sass as a dev dependency

4. Running node-sass in the terminal

    ```
    "scripts": {
    "sass": "node-sass -w scss/ -o dist/css/ --recursive"
    }
    ```
   Create a Folder to store sass files and a folder where the sass files will  be compiled into CSS 
