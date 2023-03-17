# FASTBuild-Installer
Simple [InnoSetup](https://jrsoftware.org/isinfo.php) installer for installing FASTBuild incl. FASTBuild Dashboard for Unreal Engine which will include prerequesites installer. Can run silently.

This is based on [FASTBuild](https://github.com/NineWorldsStudios/FASTBuild) and [FASTBuild-Dashboard](https://github.com/NineWorldsStudios/FASTBuild-Dashboard) which are forks by Nine Worlds Studios.


## How-to use
1. Create a common _RootProjectPath_ for FASTBuild and FASTBuild Dashboard, e.g. E:/projects/fastbuild/
2. Clone and build [FASTBuild](https://github.com/NineWorldsStudios/FASTBuild) into _RootProjectPath_/FASTBuild
3. Clone and build [FASTBuild Dashboard](https://github.com/NineWorldsStudios/FASTBuild-Dashboard) into _RootProjectPath_/FASTBuild-Dashboard
4. Modify the base configuration of th e.iss file with defaults which make sense for your environment.
5. Copy _UEPrereqSetup_x64.exe_ from your Unreal Engine installation _Engine\Extras\Redist\en-us_ to the _Prerequisites_ folder
6. Build the installer via InnoSetup
7. Installer can be found in _RootProjectPath_/FASTBuild-Installer