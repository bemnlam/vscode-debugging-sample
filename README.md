# vscode-debugging-sample

This GitHub repository contains a [tasks.json](.vscode/tasks.json) and a [launch.json](.vscode/launch.json) to handle package install, project build and browser debugging in VSCode.

See the related blog post: [Debugging Nodejs applications using VSCode](https://blog.lofibean.cc/posts/debugging-nodejs-apps-using-vscode/)

## Install packages

Choose top menu > **Run task...** (<kbd>Cmd</kbd>+<kbd>Shift</kbd>+<kbd>P</kbd> > **Tasks: Run Task**)

Type and search `npm: install all` and hit <kbd>Enter</kbd>

This will run `npm install` for both react apps (**vite-gaudi** and **rsbuild-frank**).

## Run and debug

Launch Debug panel <kbd>Cmd</kbd>+<kbd>Shift</kbd>+<kbd>D</kbd> and choose `Dev (all)` configuration.

After that, click the run button, or <kbd>F5</kbd>.

VSCode debug session will be started and a debug browser will be launched. A Vite app will run at http://localhost:5173 and a Rsbuild app will http://localhost:3000.
