![revit-github-banner](https://user-images.githubusercontent.com/79079633/142411267-7c6d3a90-6815-45ee-9a24-3c6fc4e2c3b4.png)


![GitHub last commit](https://img.shields.io/github/last-commit/cryinkfly/Autodesk-Revit-for-Linux?style=for-the-badge)
![GitHub issues](https://img.shields.io/github/issues-raw/cryinkfly/Autodesk-Revit-for-Linux?style=for-the-badge)
![GitHub Repo stars](https://img.shields.io/github/stars/cryinkfly/Autodesk-Revit-for-Linux?style=for-the-badge)
![GitHub forks](https://img.shields.io/github/forks/cryinkfly/Autodesk-Revit-for-Linux?style=for-the-badge)
![GitHub](https://img.shields.io/github/license/cryinkfly/Autodesk-Revit-for-Linux?style=for-the-badge)

Autodesk Revit is a building information modelling software for architects, landscape architects, structural engineers, mechanical, electrical, and plumbing engineers, designers and contractors, what you can use only on a system where is Windows installed as the operating system.

But the problem is that there are also people like me who don't want to use either of these two operating systems on there systems. Then these users have installed a Linux distribution such as openSUSE Leap, Ubuntu or Fedora.

And so I got the idea to start this project here to find a way to solve this problem. 

I started looking at different tools and my choice was Wine! 

With this nice tool we don't need longer two operating systems for Autodesk Revit, when we will create a fantastic project in the future or if you want to work on a project with other people.

Is that a great idea for the future?

Personally, I think this idea is good and for this reason I will do my best to give you the opportunity to use it on Linux as well!

---

You will get more information about this program, then you can visit the original website of Autodesk Revit with this link: https://www.autodesk.de/products/revit/features

---

Still in Progress!

---

## Screenshots
<div>
<img src="https://github.com/cryinkfly/Autodesk-Revit-for-Linux/blob/main/files/images/installation/%231-welcome.png" width="300px" height="200px">
<img src="https://github.com/cryinkfly/Autodesk-Revit-for-Linux/blob/main/files/images/installation/%232-configure-installation-path.png" width="300px" height="200px">
</div>
<div>
<img src="https://github.com/cryinkfly/Autodesk-Revit-for-Linux/blob/main/files/images/installation/%233-error-1603.png" width="300px" height="200px">
</div>

---

## Downloads

Still in Progress!

---

## Hardware and Software Requirements

Still in Progress!

- Internet connection (Cable/DSL speeds recommended)!
- Latest graphics driver!
- Latest wine version (winehq-staging), because with some versions of wine where no internet connection works!
- Latest winetricks version (GitHub: https://github.com/Winetricks/winetricks)!

---

## Getting Started

Still in Progress!

Install Autodesk Revit for Linux client:

1.) Check my GitHub-Documentation & Videos before you install Autodesk Revit on your system!

2.) Open a terminal and run this command (Use winetricks file!):

    WINEPREFIX=$HOME/.wineprefixes/revit sh winetricks -q cmd corefonts msxml4 msxml6 vcrun2019 dotnet48 fontsmooth=rgb win10

3.) Copy all DLLs* from [here](https://github.com/cryinkfly/Autodesk-Revit-for-Linux/tree/main/files/extras/Windows-DLLs) to /drive_c/windows/system/ and /drive_c/windows/system/32 !

4.) Download the RevitWebInstall.exe and run this command:

    WINEPREFIX=$HOME/.wineprefixes/revit wine RevitWebInstall.exe
    
5.) The installation is currently crashing with error 1603, 205 or [131372 (solved)](https://github.com/cryinkfly/Autodesk-Revit-for-Linux/issues/1) at around 16%.

*Notice: Diese DLL-files can you find in the extracted RevitWebInstall.exe!

---

## Which work areas and functions have I tested:

Still in Progress!

---

## Important Notice

With the help of my script, You get a way to install Autodesk Revit on your Linux system. 

Certain packages and programs that are required will be set up for You, but it's important to know, that my script only helps You to get the program to run and nothing more! 

And so, You must to purchase the licenses directly from the manufacturer of the program Autodesk Revit!

---

## License

All my scripts are released under the MIT license, see <a href="https://github.com/cryinkfly/Autodesk-Revit-for-Linux/blob/main/LICENSE.md">LICENSE.md</a> for full text.
