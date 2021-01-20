# Angular Tutorial

This is based on the [Getting started with Angular](https://angular.io/start) guide. 

## :exclamation: TODOs for this README

- [ ] explain how to in


## Setup

### Cloning the project in GitKraken

1. First, Open [GitKraken](https://www.gitkraken.com/git-client). If you already have a project open, close it or open a new tab.
2. Click "Clone a repo", select "GitHub.com" and find this repo in "Repository to Clone"
3. Select where to put it and clone it
4. You can then click "Open Repo" from the notification that appears to open the repo

### Open the project in VS Code

Launch Visual Studio Code, and then choose `File -> Open Folder…`. Navigate to your clone
of the repo and choose `Open`.

You may see a dialog that looks like this if you don't already have the recommended extensions:

![Dialog suggesting installation of recommended extensions](https://user-images.githubusercontent.com/1300395/72710961-bf767500-3b2d-11ea-8ea4-fbbd39c78da5.png)

Don't worry if you don't get the dialog, it is probably because you already have them all installed.

Like in previous labs, click "Install All" to automatically install them.

## Running your project

The first time you run your Angular project, you will need to run `npm install` so that all the dependencies managed by npm will be installed. Once you have successfully run `npm install`, in order to serve up the project, you will type 
**`ng serve`**. This will trigger the various tools in the
client side portion of the project to build and host your client side
application on their own little web-server, available by default at [`localhost:4200`](http://localhost:4200/). If the development server is running, you will be able to see the 