# monoarch 
monoarch is a theme for
[Plymouth](https://www.freedesktop.org/wiki/Software/Plymouth/) which exhibits
a monochrome white on black look and feel. It displays the Arch Linux logo and
a spinner. 

# Installation 
Files should be placed in the Plymouth themes directory,
which is usually `/usr/share/plymouth/themes`. Until I will make a proper AUR
package, you may install the theme by simply cloning the repository:

    # cd /usr/share/plymouth/themes/ # git clone
    https://github.com/farsil/monoarch.git 

After that, simply change the Plymouth theme:

    # plymouth-set-default-theme -R monoarch

And you're done.

# Uninstall Simply remove the directory:

    # rm -rf /usr/share/plymouth/themes/monoarch

# Using with distributions other than Arch Linux 
Nothing prevents you from doing that. If you want to replace the Arch Linux
logo with your favourite distribution's, you may want to change the
`images\logo.png` file to suit your liking.

# Credits
DeviantArt user Kahlil88, author of the
[paw-arch](http://kahlil88.deviantart.com/art/Paw-Arch-Plymouth-Theme-208418769)
theme I used it as a base to build my code.
 
Arch Linux logo taken from
[https://www.archlinux.org/art/](https://www.archlinux.org/art/).

Spinner pictures and a large part of code taken from the default Plymouth themes.
