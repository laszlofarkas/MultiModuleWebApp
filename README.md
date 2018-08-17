# MultiModuleWebApp
Comprehensive repository for different modules

## Prerequisites
Each module have various dependencies, but globally you should have the followings
- [node.js](https://nodejs.org) has to be installed
- Have connection to a [MongoDB](https://www.mongodb.com/download-center#community)

### MongoDB
The app try to connect a MongoDB on local host: `mongodb://localhost:27017/publishing`  
If you want to use an other connection string you should modify that in `.\RESTService\src\app.ts` file

## TODO
There are some feature what is missing
- Rendering reach data into svg on Reach Dashboard
- Update reaches graph with new reaches coming from websocket
- Tests (both in back-end and front-end)
- Make the applications deploy ready
  - Organize environment related properties (like urls, port numbers, connection strings, etc) into file
  - Finalize test and run scripts

## IDE
Suggested IDE is [VS Code](https://code.visualstudio.com/), because there is some preconfigured lunch script which helps you in debug

### Required extensions (for debugging)
- [Debugger for Chrome](https://marketplace.visualstudio.com/items?itemName=msjsdiag.debugger-for-chrome)