# FASTBuild-Installer
Simple [InnoSetup](https://jrsoftware.org/isinfo.php) installer for installing FASTBuild incl. FASTBuild Dashboard for Unreal Engine which will include prerequesites installer. Can run silently.

This is based on [FASTBuild](https://github.com/aesirinteractive/FASTBuild) and [FASTBuild-Dashboard](https://github.com/aesirinteractive/FASTBuild-Dashboard) which are forks by Aesir Interactive.


## How-to use
1. Checkout and install InnoSetup
2. Clone and build [FASTBuild](https://github.com/aesirinteractive/FASTBuild)
3. Clone and build [FASTBuild Dashboard](https://github.com/aesirinteractive/FASTBuild-Dashboard)
4. Fill the placeholder entries in the FBDashboard-setup.iss file with your specific paths
5. Compile the installer via InnoSetup
