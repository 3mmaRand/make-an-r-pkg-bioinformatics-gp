# Install Package Development toolchain

**For Windows with no admin rights**

Download the latest (recommended) Rtools installer, `Rtools.exe`, from 
https://cran.r-project.org/bin/windows/Rtools/. Run the installer keeping the 
default settings.

**For Windows with admin rights**

Download the latest (recommended) Rtools installer, `Rtools.exe`, from 
https://cran.r-project.org/bin/windows/Rtools/. Run the installer making the 
following selections: keep the default settings for the installation location 
and components to install; check the box to add rtools to the system PATH.

**For Mac**

Install XCode. Either:

1.  Download and install XCode from the Mac AppStore: http://itunes.apple.com/us/app/xcode/id497799835?mt=12
2.  Within XCode go to Preferences : Downloads and install the Command Line 
Tools

Or for a smaller download size:

1. Register as an Apple Developer (free) here: https://developer.apple.com/programs/register/
2. Download the Command Line Tools for XCode appropriate for the version of 
OS X you are running from here: https://developer.apple.com/downloads/

**For Linux**

If you installed `r-base-dev`, when installing R, you should have all you need 
to build packages from source. Otherwise return to the instructions for 
installing R for your distribution and follow the instructions there to install 
the additional tools.

