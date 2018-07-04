# Node.js dojo
In this tutorial, you will learn the basics of Node.js and explore its applications in developing scalable network applications

## Prerequisites

To follow along, you will need to install the following software on your local machine:

* [Node.js v8](https://nodejs.org/en/) (which includes [npm](https://www.npmjs.com/get-npm))
* [Yarn](https://yarnpkg.com/en/) (recommended for people in Bath due to proxy issues)
* [Visual Studio Code](https://code.visualstudio.com/)

The tutorial also assumes:

* you understand basic JavaScript and an awareness of [ES6](http://es6-features.org) features
* you are working on Windows OS (there are slight differences in the implementation of Node.js on Linux)

## Setting up your environment

Let's create a directory in which to store the examples you will work with in this tutorial. Open up an instance of Command Prompt and paste the following (replacing with a suitable directory of your choice if you wish):

```powershell
mkdir "C:/Projects/NodeJsDojo"
code "C:/Projects/NodeJsDojo"
```

You can press *Ctrl + '* to open up the integrated terminal in Visual Studio Code and use this for our commands. Pressing *Ctrl + \* splits the terminal into multiple sessions, whilst *Ctrl + Shift + '* opens a new terminal in the dropdown. You can close any unnecessary terminals by entering the command:
```powershell
exit
```
More handy shortcuts can be found [here](https://code.visualstudio.com/docs/editor/integrated-terminal).

Now that you're familiar with the terminal in Visual Studio Code, let's check you have installed Node correctly by entering the command:
```powershell
node --version
```
You should see a version number in the format of `v8.x.x`.

