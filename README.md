Setting up R, RStudio, and Git
================
Christopher R. Peterson

# Install R

**Required Version: 4.0.0 or higher**

R is an interpreter that runs scripts written in the R language; it
needs to be installed, but you generally won’t work with it directly.

Go to the [CRAN](https://cran.r-project.org/) (Comprehensive R Archive
Network) website and click the download link for your operating system.

For Windows, click “base,” then “Download R (version) for Windows. Open
the installer and follow the instructions. For Mac OS X, click the
`.pkg` file under”Latest Release" and follow the instructions on the
page. For Linux, follow the page instructions and contact me if you have
questions.

**If you already have R on your system**

Open R and check the version number (it should be the first thing that
pops up). If it is below 4.0.0, you’ll need to install R again (follow
the instructions above).

# Install RStudio

RStudio is a development environment that simplifies and automates a lot
of lot of tedious things that working with R usually requires. It will
be your primary interface with the R language

**Required Version: 1.2 or higher**

[Download RStudio
Desktop](https://rstudio.com/products/rstudio/download/#download) for
the appropriate operating system and install it. You should make sure
you have R installed first.

If you already have RStudio installed, go to Help -\> About RStudio to
check the version number. I recommend version 1.3, but 1.2 will work for
what we’re doing.

# Install Git

Git is a version control system that is used to manage changes in files
for projects. I’ll be routinely updating the files associated with this
course, and Git is the easiest way to make sure you have the most recent
versions of everything.

[Download Git](https://git-scm.com/downloads) for your operating system,
and follow the instructions on the installer.

(Check Windows BS)

## Create a Github account

Create an account on [Github](https://github.com/join).

## Connect Git to RStudio

In RStudio, go to **Tools -\> Global Options** and click **Git/SVN**.
Check the **Enable version control interface for RStudio projects** box.
Apply the changes.

(IMAGE:
<https://www.geo.uzh.ch/microsite/reproducible_research/post/rr-rstudio-git/img/RStudio-setup-git.png>)

If nothing is listed under *Git executable*, click browse and find where
git (or git.exe) has been installed. On Windows, it’s usually something
like `C:/Program Files (x86)/Git/bin/git.exe`. For Linux/OS X, click the
“Terminal” tab in the low-right pane of RStudio and type `which git` to
find the location.

(RSA Key)

Restart Rstudio.

# Installing R packages
