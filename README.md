# basic-webapp

> A Vue.js project

## Build Setup

How to set up dev environment:
1. If you do not already have it installed, install Vue.js CLI in your command line by running `npm install -g vue-cli`. 

2. After Vue-CLI is installed, run the command `vue init webpack test-project` to create the files necessary for the project.

3. Answer the questions that are prompted, such as Project Name: basic-webapp etc.

4. Change directories into basic-webapp.

5. Run `npm install` to install all of the project dependencies.


How to run the development server:
1. Open the project in your text editor

2. Open the terminal from inside the editor and run the command `npm run dev` to launch the dev server and view your project.


How to build the code for deployment:
1. Open project in text editor.

2. Open 'HelloWorld.vue' file.

3. Make changes to HTML/CSS/JS as required in the project. 

How to deploy the site
1. Configure webpack and GitHub by updating the `dist` folders to `docs` under 'Config' folder > `index.js` under `index` and `assetsRoot`. 

2. Remove the '/' from `assetsPublicPath`. 

3. Run `npm run build` in command line to build out `docs` files.  

4. Commit and push changes to GitHub.

5. In GitHub repository, go to Settings > GitHub Pages and choose 'Master branch /docs folder' and save.

6. Go back to main repository page for the project, paste in new url for project into 'Website' section. 



For a detailed explanation on how things work, check out the [guide](http://vuejs-templates.github.io/webpack/) and [docs for vue-loader](http://vuejs.github.io/vue-loader).
