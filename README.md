# MultiModuleWebApp
Comprehensive repository for different modules

## Prerequisites
Each module have various dependencies, but globally you should have the followings
- [node.js](https://nodejs.org) has to be installed
- Have connection to a [MongoDB](https://www.mongodb.com/download-center#community)

### MongoDB
The app try to connect a MongoDB on local host: `mongodb://localhost:27017/publishing`  
If you want to use an other connection string you should modify that in `.\RESTService\src\app.ts` file

## Get the code
This repository have some git submodule that you have to initialize and update for first time:
```
git submodule init
git submodule update
```
After that, you can maintain submodules separately

## TODO
There are some feature what is missing
- Tests (both in back-end and front-end)
- Make the applications deploy ready
  - Organize environment related properties (like urls, port numbers, connection strings, etc) into file
  - Finalize test and run scripts

## IDE
Suggested IDE is [VS Code](https://code.visualstudio.com/), because there is some preconfigured lunch script which helps you in debug

### Required extensions (for debugging)
- [Debugger for Chrome](https://marketplace.visualstudio.com/items?itemName=msjsdiag.debugger-for-chrome)