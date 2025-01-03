# CodingProject3
- ```npm init -y``` : setting up a node project and using default values for package.json
- ```npm install typescript``` : install typescript 
- ```npm install @types/node``` : adds ambient types(global types all around) for node js
- ```npx tsc --init --rootDir src --outDir build --esModuleInterop --resolveJsonModule --lib es6 \--module commonjs --allowJs true --noImplicitAny true``` : creates ts config file
- ``` mkdir src``` :  make directory called src 
- ```touch src/index.ts``` : creates the index.ts file
- ```npx tsc``` : compiles typescript project into javascript project
- ```npm install --save-dev ts-node nodemon``` : installed nodemon and ts-node 
    - ```{"watch": ["src"], "ext": ".ts,.js", "ignore":[], "exec": "npx ts-node ./src/index.ts"}``` : nodemon.json
- ```"start":"npx nodemon"```: added the command in the scripts field for package.json 
- ```npm run start```: runs nodemon

# Git - How to Push Changes To Github
- ```git add .```: This adds all of your changed/created files to a box so that it can be sent to github
- ```git commit -m "<your message>"```: This wraps up your box and adds a message that will be tied to your change
- ```git push origin <branch name>```: This pushes your changes to the specified branch