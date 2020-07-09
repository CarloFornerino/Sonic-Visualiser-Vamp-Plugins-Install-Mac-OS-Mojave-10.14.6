# Sonic-Visualiser-Vamp-Plugins-Install-Mac-OS-Mojave-10.14.6
Proper installation of Sonic Visualiser Vamp Plugins.

First attempt to install Aubio pack on Sonic Visualiser by downloading: vamp-aubio-plugins-0.5.1-osx.tar.bz2
and following the install instructions: on a Mac:

https://www.vamp-plugins.org/download.html#install

    Put plugins for all users to use in /Library/Audio/Plug-Ins/Vamp
    Put plugins for only the current user in $HOME/Library/Audio/Plug-Ins/Vamp
    The Library folders are hidden by default; see here for details of how to show them
    
This gave me a plugin loading error: vamp plugin image error.
The fix was to install aubio from the Terminal using brew install aubio.
