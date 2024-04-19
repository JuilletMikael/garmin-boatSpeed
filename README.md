# garmin-boatSpeed

## Description

This project is an app made to go on the epix pro 47' of garmin device, as a goal to vibrate when you are further than 300m of the edge of the lake.

## Getting Started

### Prerequisites

List all dependencies and their version needed by the project as :

* IDE used VS Code 1.88.1 or later [official doc]([https://docs.npmjs.com/try-the-latest-stable-version-of-npm](https://code.visualstudio.com/))
* Gamin SDK 7.1.1 or later [official doc](https://developer.garmin.com/connect-iq/sdk/)
* Monkey C Extension for VS code v1.0.11 or later
* git version 2.43.0.windows ou ultérieure [official doc](https://git-scm.com/)
* OS supported Windows 10
* Watch supported 

### Configuration

## Deployment

### On dev environment

Before running the program, make sure you have one of your source files (In the source folder with the .mc extension) open and selected in the editor.

Select Run > Run Without Debugging (Command + F5 on Mac, Ctrl + F5 on other platforms)
You will be prompted with the list of products your application supports. Select one from the list.
If all goes well the simulator will start up and the selected watch will appear:


### On integration environment

To deploy the project first copy the project to the proper folder then duplicate the .env.example to .env and 
update it with your environment's values.

## Directory structure
```shell
├───builds          //All builds of the app 
├───resources       //Ressource file 
│   ├───drawables
│   ├───layouts
│   ├───menus
│   └───strings
└───source          //Source of the project file 
```

## Collaborate

* Workflow
  * [Gitflow](https://www.atlassian.com/fr/git/tutorials/comparing-workflows/gitflow-workflow#:~:text=Gitflow%20est%20l'un%20des,les%20hotfix%20vers%20la%20production.)
  * [How to commit](https://www.conventionalcommits.org/en/v1.0.0/)
  * [How to use your workflow](https://nvie.com/posts/a-successful-git-branching-model/)
  * Propose a new feature in [github issues page](https://github.com/JuilletMikael/RIA-EggFlix/issues) with the tag feature
  * Pull requests are open to merge in the develop branch.
  * Release on the main branch we use GitFlow and not with GitHub release.
  * Issues are added to the [github issues page](https://github.com/JuilletMikael/RIA-EggFlix/issues)

## License


## Contact

* If needed you can create an issue on GitHub we will try to respond as quickly as possible.
