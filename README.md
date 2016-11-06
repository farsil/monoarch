# Monoarch 
Monoarch is a theme for
[Plymouth](https://www.freedesktop.org/wiki/Software/Plymouth/) which exhibits
a monochrome white on black look and feel. It displays the Arch Linux logo and
a spinner. 

![Splash screen preview](https://farsil.github.io/monoarch/images/monoarch.png)

# AUR Package 
The AUR package for this theme is [plymouth-theme-monoarch](https://aur.archlinux.org/packages/plymouth-theme-monoarch/). You may use your favourite AUR helper or proceed with manual installation as described [here](https://wiki.archlinux.org/index.php/Arch_User_Repository#Installing_packages).

The package does not alter your Plymouth configuration, you have to change the theme manually. In order to do so, type:

    # plymouth-set-default-theme -R monoarch

And you're done.

# Installation
Files should be placed in the Plymouth themes directory,
which is usually `/usr/share/plymouth/themes`. You may install the theme by simply cloning the repository:

    # cd /usr/share/plymouth/themes/ 
    # git clone https://github.com/farsil/monoarch.git 

Remember to change the Plymouth theme:

    # plymouth-set-default-theme -R monoarch

# Removal
Simply remove the directory:

    # rm -rf /usr/share/plymouth/themes/monoarch
    
Remember to change your theme again otherwise Plymouth will fall back to its 
default one.

# Using with distributions other than Arch Linux 
Nothing prevents you from doing that. If you want to replace the Arch Linux
logo with your favourite distribution's, you may want to change the
`images/logo.png` file to suit your liking.

# Credits
DeviantArt user Kahlil88, author of the
[paw-arch](http://kahlil88.deviantart.com/art/Paw-Arch-Plymouth-Theme-208418769)
theme I used it as a base to build my code.
 
Arch Linux logo taken from
[https://www.archlinux.org/art/](https://www.archlinux.org/art/).

Spinner pictures and a large part of code taken from the default Plymouth themes.
