A simple angularjs2 application using typescript.

The build is carried by systemjs which compiles all typescript files into javascript files.

Setup

1. Clone the repository to your local project using

    git clone -git-repository-url

2. run npm install to install all the dependancies mentioned in package.json
3. create a folder named dist at root. this will the build folder for your application. 
3. run npm start to start the application. this automatically compiles the typescript files into javascript files and place them in dist folder. you can change the build folder name(dist) in systemjs.config.js at line:8 