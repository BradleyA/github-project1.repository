

#### WARNING: These instructions are incomplete. Consider them as notes quickly drafted on a napkin rather than proper documentation!

I have been using some of these for days, months, or years and just now uploading them. I need to complete some cleanup before it is shareable and documented . . .


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

## License::

Permission is hereby granted, free of charge, to any person obtaining a copy of this software, associated documentation, and files (the "Software") without restriction, including without limitation of rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE. IN NO EVENT SHALL THE AUTHORS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
