# github-project1.repository
[![GitHub Stable Release](https://img.shields.io/badge/Release-0.0-blue.svg)](https://github.com/BradleyA/github-project1.repository/releases/tag/0.0)
![GitHub Release Date](https://img.shields.io/github/release-date/BradleyA/github-project1.repository?color=blue)
[![GitHub Commits Since](https://img.shields.io/github/commits-since/BradleyA/github-project1.repository/0.0?color=orange)](https://github.com/BradleyA/github-project1.repository/commits/)
[![GitHub Last Commits](https://img.shields.io/github/last-commit/BradleyA/github-project1.repository.svg)](https://github.com/BradleyA/github-project1.repository/commits/)

[![GitHub Open Issues](https://img.shields.io/github/issues/BradleyA/github-project1.repository?color=purple)](https://github.com/BradleyA/github-project1.repository/issues?q=is%3Aopen+is%3Aissue)
[![GitHub Closed Issues](https://img.shields.io/github/issues-closed/BradleyA/github-project1.repository?color=purple)](https://github.com/BradleyA/github-project1.repository/issues?q=is%3Aclosed+is%3Aissue)
[<img alt="GitHub Clones" src="https://img.shields.io/static/v1?label=Clones&message=43&color=blueviolet">](https://github.com/BradleyA/github-project1.repository/blob/master/images/clone.table.md)
[<img alt="GitHub Views" src="https://img.shields.io/static/v1?label=Views&message=175&color=blueviolet">](https://github.com/BradleyA/github-project1.repository/blob/master/images/view.table.md)
[![GitHub Size](https://img.shields.io/github/repo-size/BradleyA/github-project1.repository.svg)](https://github.com/BradleyA/github-project1.repository/)
![Written in Bash](https://img.shields.io/badge/written%20in-bash-blue.svg)
[![MIT License](http://img.shields.io/badge/License-MIT-blue.png)](LICENSE)

----

Automated build from GitHub code to Docker image on dockerhub

#### If you like this repository, select in the upper-right corner, star, thank you.

#### WARNING: These instructions are incomplete. Consider them as notes quickly drafted on a napkin rather than proper documentation!

I have been using some of these for days, months, or years and just now uploading them. I need to complete some cleanup before it is shareable and documented . . .

Docker Hub account:  allup2u72

The build process looks for a README.md in the same directory as your Dockerfile.
If you have a README.md file in your repository, it is used in the repository as 
the full description. If you change the full description after a build, it’s 
overwritten the next time the Automated Build runs. To make changes, modify the 
README.md in your Git repository.

The status:

Queued: You’re in line and your image will be built soon. Queue time varies 
depending on number of concurrent builds available to you.

Building: Your image is currently being constructed.

Success: The image has been built with no issues.

Error: There was an issue with your image. Click the row to access the Builds 
Details screen. The banner at the top of the page displays the last sentence of 
the log file indicating what the error was. If you need more information, scroll 
to the bottom of the screen to the logs section.

#### Author
[<img id="github" src="images/github.png" width="50" a="https://github.com/BradleyA/">](https://github.com/BradleyA/)    [<img src="images/linkedin.png" style="max-width:100%;" >](https://www.linkedin.com/in/bradleyhallen) [<img id="twitter" src="images/twitter.png" width="50" a="twitter.com/bradleyaustintx/">](https://twitter.com/bradleyaustintx/)       <a href="https://twitter.com/intent/follow?screen_name=bradleyaustintx"> <img src="https://img.shields.io/twitter/follow/bradleyaustintx.svg?label=Follow%20@bradleyaustintx" alt="Follow @bradleyaustintx" />    </a>

#### System OS script tested
 * Ubuntu 14.04.3 LTS (amd64,armv7l)
 * Ubuntu 16.04.5 LTS (armv7l)

#### Design Principles
 * Have a simple setup process and a minimal learning curve
 * Be usable as non-root
 * Be easy to install and configure

#### License
MIT License

Copyright (c) 2020  [Bradley Allen](https://www.linkedin.com/in/bradleyhallen)

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
