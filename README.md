WARNING: These instructions are incomplete. Consider them as notes quickly drafted on a napkin rather than proper documentation!

The build process looks for a README.md in the same directory as your Dockerfile.
If you have a README.md file in your repository, it is used in the repository as 
the full description. If you change the full description after a build, it’s 
overwritten the next time the Automated Build runs. To make changes, modify the 
README.md in your Git repository.

The statuses are:

Queued: You’re in line and your image will be built soon. Queue time varies 
depending on number of concurrent builds available to you.
Building: Your image is currently being constructed.
Success: The image has been built with no issues.
Error: There was an issue with your image. Click the row to access the Builds 
Details screen. The banner at the top of the page displays the last sentence of 
the log file indicating what the error was. If you need more information, scroll 
to the bottom of the screen to the logs section.

