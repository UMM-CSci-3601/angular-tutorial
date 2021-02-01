# Angular Tutorial

This is based on the [Getting started with Angular](https://angular.io/start) guide. 
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
application on their own little web-server, available by default at [`localhost:4200`](http://localhost:4200/). If the development server is running, you will be able to see the application (a simple "phone store").

When you open it in the browser you should be greeted with something that looks like this:

![image](https://user-images.githubusercontent.com/1300395/105233127-07f4b400-5b2f-11eb-9c6f-3f51594f684e.png)

---

## Follow along with the tutorial

**Make sure you commit often with good commit messages as you go
through the tutorial.**

Now your job now is to go through [the "Getting started with Angular" tutorial](https://angular.io/start), up to (but not including) the last section ("Deploying an application").

> You might want to read that last section on deployment, but our
> deployment mechanism in this class will be totally different than
> what they describe there.

To "do the lab", you will essentially follow along and do whatever it
says to do in the tutorial. This is mostly adding or modifying content
in various files that will already exist in this repository.

There are, however, times, when you need to create a new _component_ or
_service_ (terms explained in the tutorial). In the tutorial you do this
through a StackBlitz menu, which won't exist for you. You will instead
use `ng generate` in the terminal.

For example, roughly in the middle of the first section of the tutorial,
you encounter this:

![StackBlitz generate component menu](images/StackBlitz_component_menu.png)

We will instead generate this new component in the terminal using:

```bash
ng generate component product-alerts
```

**You must be at the top level of your project in the terminal window
when you enter an `ng generate` command.**

This will do the same thing that the menu would do in StackBlitz, but
via the terminal instead. After you do that you should check that you
indeed get the same new files that the tutorial says that you should.

There will be various other times in the tutorials where they tell you
to generate either a _component_ or a _service_. You should always do
that through either `ng generate component ...` or
`ng generate service ...` as appropriate (with the name of the component
or service in place of the `...`s above). (Note that the tutorial
_always_ tells you the name of the component or service that you are
creating. Make sure you use the correct name or subsequent steps will
likely not work.)
