# expressReactAPI

### Cloning a Project with Submodules

- if you clone with git clone, you can not take data of sumodules. because of that, you must use :

      `git clone --recurse-submodules https://github.com/pietow/expressReactAPI`

- This will also clone the submodules

### Installing node-modules in each submodule:

- submodules have different package.json. you can use this instead of using two npm install..

      `git submodule foreach 'npm install'`

### Structure

This repository consists of a frontend (react) and backend (node/express) repository

# Copyright

- This project copied from @pietow [https://github.com/pietow]. Thank yo so much Piet..
