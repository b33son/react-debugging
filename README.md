Using VSCode Debugger with Create React App:

https://medium.com/@auchenberg/live-edit-and-debug-your-react-apps-directly-from-vs-code-without-leaving-the-editor-3da489ed905f

How to get started in 6 steps

1.  Download the latest release of VS Code and install our Chrome debugger

2.  Create your React app using create-react-app

3.  Use the following config for your launch.jsonfile to configure the VS Code debugger and put it inside .vscode in your root folder.

{
"version": "0.2.0",
"configurations": [
{
"name": "Chrome",
"type": "chrome",
"request": "launch",
"url": "http://localhost:3000",
"webRoot": "${workspaceRoot}/src"
}
]
}

4.  Start your React app by running npm start in your favorite terminal

5.  Start debugging in VS Code by pressing F5or by clicking the green debug icon

Happy debugging! 🎉🎈
