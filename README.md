# Redgum Labs simple flat website

## Running locally

### Setup
1. Install [Visual Studio Code / VS Code](https://code.visualstudio.com/download)
1. Install [Github Desktop](https://desktop.github.com/) (optional but makes it easier to push changes to prod)
2. Clone the repo using either Github Desktop OR with SSH permissions `git clone git@github.com:RedgumLabs/RedgumLabs.github.io.git`
3. Install [Node.js](https://nodejs.org/en/download) installed on your computer. 
4. Once installed open Powershell and run `Set-ExecutionPolicy RemoteSigned` and accept. 
5. You will then need to install `http-server` by using the node package manager, NPM, by running `npm install http-server -g` in Powershell. 

### Running
1. Open VS code and open the repository folder
2. Open a terminal using the Terminal tab at the top of VS code
3. In the terminal run `http-server`, this will start a server using the files within the repository folder.
4. Open any browser and go to `localhost:8080` or any other the other addresses shown in the terminal after starting the server.

That should be everything to do quick edits and see changes live.

### Development
Make changes to any of the files, make sure you save them locally (`ctrl + s`) then to see the updates of changes press `ctrl + shift + R` in the browser to refresh ignoring cookies and stored info by the browser.

## Pushing to production
It isn't the best practice to push all our changes straight to production, it's much better to start a branch to make changes in then merge them to the master branch eventually.
Once we have a site we are happy with, we can make changes in a branch to the side to improve and update it, check it, then move it to production at a later time.

