In order to use this, please run the following commands.

        rm -rf .git (this removes any git tracking)
        npm install (installs the dependecy packages)

You also might want to create you own .gitignore file since I have elected to ignore my own .gitignore file :).
You can do that in the command line like the following.

        touch .gitignore
        open .gitignore
        
Type in the following (in the .gitignore file) if you want to ignore just the node_modules folder, which is standard practice.

        node_modules

You will also need to name the package name, description, author, and license in package.json as well

- includes the following npm packages

    - webpack 4
        - npm i webpack webpack-cli -D
        - npm i html-webpack-plugin -D
        - npm i webpack-dev-server -D
        - npm i css-loader style-loader -D
    - babel
        - npm i babel-core babel-loader babel-preset-env babel-preset-react -D
        - npm install --save-dev babel-plugin-transform-class-properties
    - react
        - npm i react react-dom -S

Enjoy!
