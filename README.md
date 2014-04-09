cleanassets
===========

Command line Yii Script to clean assets dir

CleanAssetsCommand assets is console yii script to clean assets or runtime directory.
I use this script to clean project `/assets` folder by my cronbot once a month.
You can use it simply from command line or with cron actions.

##Usage

1. Copy CleanAssetsCommand to `application.commands` folder
2. run `yiic help cleanassets` to see how to use this script

##Command line arguments
**--auto** - makes script to run in silent mode;

**--dir=/path/to/dir** - specifies path to directory. If blank - system default path will be applied;

##Useful info:
[How to Run Yiic directly from your app without a shell](http://www.yiiframework.com/wiki/226/run-yiic-directly-from-your-app-without-a-shell/ "How to Run Yiic directly from your app without a shell") by [jacmoe](http://www.yiiframework.com/user/7189/ "jacmoe")

##Be carefull. Do backups