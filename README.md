# scheduler - electron

This is a basic Electron application, it needs just these files:

- `package.json` - Points to the app's main file and lists its details and dependencies.
- `main.js` - Starts the app and creates a browser window to render HTML. This is the app's **main process**.
- `index.html` - A web page to render. This is the app's **renderer process**.


## To Use

To clone and run this repository you'll need Git and Node.js

```bash
# Clone this repository
git clone https://github.com/danilobatistaqueiroz/scheduler-electron.git
# Go into the repository
cd scheduler_electron
# Install dependencies
npm install
# Run the app
npm start
```

## You can transform it into a standalone application

First, install electron-packager:  
`npm install electron-packager -g`  
or  
`npm install electron-packager --save-dev`  

execute from the root folder:  
`electron-packager .`  

## Screenshots

![screen2](https://user-images.githubusercontent.com/32627919/39369783-962dd628-4a13-11e8-8322-6ead3538f176.png)

![screen1](https://user-images.githubusercontent.com/32627919/39369785-96526c2c-4a13-11e8-9b27-8eb84c94f0eb.png)

## Links

https://github.com/electron-userland/electron-packager
https://electronjs.org/docs/tutorial/application-distribution


