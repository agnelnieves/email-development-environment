# Email Development Environment

A simple email development starter environment

## Requirements

1. Node
2. Yarn

## ✨ Quick start

1.  **Clone this repository.**

    ```bash
    git clone https://github.com/agnelnieves/email-development-environment.git
    ```

2.  **Start developing.**

    Navigate into the dev environemnt directory and start it up.

    ```sh
    cd email-development-environment/
    yarn install
    yarn start
    ```

## 🛠 Build

```sh
    # install dependencies
    yarn install

    # serve with hot reload
    yarn start
    # Your should be running at http://localhost:3000

    # build for production and launch server
    yarn build

    # generate zip for production
    yarn zip
```

## 🧐 What's inside?

```
    .
    ├── dist
    ├── etc
    ├── node_modules
    ├── src
      ├── assets
        ├── scss
        ├── img
      ├── helpers
      ├── layouts
      ├── pages
      ├── partials
    ├── .babelrc
    ├── .gitignore
    ├── example.config.json
    ├── gulp.babel.js
    ├── LICENSE
    ├── package.json
    ├── README.md
    └── yarn.lock
```

1.  **`/node_modules`**: This directory contains all of the modules of code that your project depends on (npm packages) are automatically installed.

2.  **`src/assets`**: You will find the images, styles and assets for the project.

3.  **`src/layouts`**: You will find all the different layouts for your email template. This can be useful for different email setups.

4.  **`src/pages`**: You will find all the the email pages. Example: Sales, subscription, basic, etc.

5.  **`src/partials`**: You will find all the partial code modules to include in the pages or layouts. Basically the email reusable components.

6. **`example.config.json`**: This example config file is for deploying or testing email templates via [litmus](https://litmus.com/)

7. **`gulpfile.babel.js`**: All Gulp tasks configurations

8. **`LICENSE`**: This is licensed under the MIT license.

9. **`package.json`**: A manifest file for Node.js projects, which includes things like metadata (the project’s name, author, etc). This manifest is how npm knows which packages to install for your project.

10. **`yarn.lock`**: This is an automatically generated file based on the exact versions of your npm dependencies that were installed for your project. **(You won’t change this file directly).**

11. **`README.md`**: A text file containing useful reference information about your project.

## Contributors

+ [Agnel Nieves](https://github.com/agnelnieves)