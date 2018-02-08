# Work Log
******************************
## Project:		Customer (Starting with MS Template)
## Date:			2/7/2018
## Author:		Geoff Fox
******************************
Tasks: 
* Task #: Configure folder structure CustGLF/CustGLF and save to GitHub.com
* Task #: Change project to Core 2.0 and update Nuget Packages
* Task #: Add Gulp and run (File from Dan's project)
	Task #2: add to package.json file
	{
		"devDependencies":{
			 "gulp": "^3.9.1",
        "gulp-concat": "^2.6.1",
        "gulp-plumber": "^1.1.0",
        "gulp-uglify": "^3.0.0",
        "run-sequence": "^2.2.0",
        "del": "^3.0.0",
        "del-cli": "^1.1.0",
		}
	}
	Run the following Gulp task to copy required Angular modules into the `wwwroot` folder: 

    `gulp copy:libs`
	Online Ref: https://docs.microsoft.com/en-us/aspnet/core/client-side/using-gulp
* Note: Gulp is being replaced by BundlerMinifier
http://www.talkingdotnet.com/gulp-is-no-longer-default-choice-asp-net-core/

Commit - Updated to work with Gulp.js from Dan W Project
*******************************


