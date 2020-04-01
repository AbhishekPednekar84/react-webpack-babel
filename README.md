## Creating a React application from scratch

This repository can be used as the starter project for a **`react`** application. It uses `babel` to compile the project and `webpack` to run the development server and bundle the output. To get started, simply clone the repository, write the **`react`** code in the `/src` directory and execute the `npm start` command to run the project or `npm run build` to generate the output build in the `/dist` folder.

### Packages used <br />
**React**
1. react
2. react-dom

**Webpack**
1. webpack
2. webpack-dev-server
3. webpack-cli
4. html-webpack-plugin

**Babel**
1. babel-loder
2. babel-core
3. babel-preset-react
4. babel-preset-env

### Cloning the contents of the repository (minus the root folder)
In an empty directory run 
1. `git init`
2. `git remote add origin https://github.com/AbhishekPednekar84/react-webpack-babel.git`
3. `git pull origin master`

**Note**: You may need to setup an SSH key to the above `git` commands. 
1. To generate a key (using git bash) in `~/.ssh`, run `ssh-keygen -t rsa -b 4096 -C "email@domain.com"`
2. Add the private key to the ssh agent `ssh-add <private_key_name>`
3. Add the public key (`cat <public_key_name>`) in the Github user settings

### Summary of commands
1. Initialize a new package - `npm init`
2. Install `react` and `react-dom` - `npm install --save react react-dom`
3. Install `webpack` as a dev dependency - `npm install --save-dev webpack webpack-cli webpack-dev-server html-webpack-plugin`
4. Install `babel` as a dev dependency - `npm install --save-dev babel-loader @babel/core @babel/preset-env @babel/preset-react` 
5. Run the application -  `npm start`
6. Generate the build- `npm run build`
