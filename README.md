# hello-world

It's a simple Angular2 Project. I've followed angular2 quick start guide.

Few Essential steps for understanding the project:

1. In package.json include angular dependencies and other dependencies we need in our project.
2. system.config.js uses System.js which loads the application and library modules -> In index.html file of this project you'll see System.import -> which imports the app
3. tsconfig.json is a configuaration file for TYPESCRIPT compiler (tsc)
4. typings.json is used so that typescript identifies any 3rd party libraries whose definition files are not declared in node modules. 
5. All ".ts" files are transpiled by typescript compiler to ".js" files and generate ".js.map" files

#Folder Structure

directory - hello-world
"app" folder has all .ts files and once transpiled, it contains .js files too.
"node_modules" folder is created when 'npm install' command is executed.
"typings" folder is created using typings.json file and post npm install we do -> 'typings install' under scripts in package.json file



#How to Run this App

To run:

Type npm start in terminal -> which would trigger the watch mode in typescript compiler also run lite server which would open the app in browser. Any changes done and saved in files would be automatically triggered in browser.

Okay... so how is this done? Simple!!! In package.json file, under scripts we've mentioned it.








