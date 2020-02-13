# SettingUp_NodeJS_Environment
You will learn how to setup Node JS environment and all its dependancies required to run Node JS server

# Getting started

To use Node JS as a server side scripting language, you will need setup the environment first. This includes all the needed tools that should be available for Node JS to run. In this course, you will have to setup the environment that is needed to run Node JS server. 

And to do that follow the steps below:

# Installing Node JS
You can right Javascript scripts on your computer, but to run them as server side scripts, you will need to have Node JS installed.

1. Install Node JS server from this link https://nodejs.org/en/download/ get the one compatible with your Operating System.
   Supporting links which can also be used when you are having difficulties
   
 - Windows https://blog.teamtreehouse.com/install-node-js-npm-windows
 - Ubuntu https://tecadmin.net/install-latest-nodejs-npm-on-ubuntu/
 - MacOS https://treehouse.github.io/installation-guides/mac/node-mac.html
 
 Follow the installation procedure until you are done with the installation. For windows make sure you add the Node JS path to environmental variables for easy of access.

2. Open any terminal and type the following command.

  - Windows $ node -v
  - Ubuntu $ node -v
  - MacOS $ node -v

This should give you the version of node thalt is running on your computer.

To test our Node JS server open command prompt and do the following.
```bash
$ node
> .editor
```

```javascript
  const name = "your name"
  const otherName = "your other name"
  const earthBornDate = "add year you think earth was born"
  const yearToDay = "add this year"
  let earthAge = earthBornDate - yearToDay
  console.log("Am " + name + " " + otherName + " and I live on earth which I think is "+earthAge)
  ```
 press control + D to exit editor mode
 
 and enter the following command to save our code from the terminal.

```bash
 > .save nodeTest.js
``` 
 
This will save what we wrote in the editor to nodeTest.js file in the current directory.
Exit node terminal by hiting control + C several times.
 
Run the nodeTest.js as our save by doing the following;
Since we will be in the bash terminal, type ls command to list files that are in that directory and we you should be able to see the nodeTest.js file we created.

To run the script type
```bash
$ node nodeTest.js
```
you should see the output on the console.

# Assignment

Node JS is Jacascript which is justed used at server side. 

Your assignment is to rewrite what we wrote in nodeTest.js file to be in a function which should be called and display the same output as we did with nodeTest.js. 

Save the file as nodeLearned.js you will have to locate the directory of this file and copy it to all the files you will commit to github.

# Submit by commiting this repository with the following files
- nodeTest.js
- nodeFunction.js
- screen shot of terminal showing how you created and saved nodeLearned.js file in a foleder with you name as folder name.









 
 
 
 
 
 
  
  


