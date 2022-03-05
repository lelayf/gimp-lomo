# gimp-lomo

A Script-Fu plugin for the GNU Image Manipulation Program, to apply a Lomo LC-A effect on your photos.

# Installation

- [Download](https://www.gimp.org/downloads/) and install The GIMP on your operating system.
- Identify one of the Script-Fu folders by checking `Edit > Preferences > Folders > Scripts`
- Download the [script](https://raw.githubusercontent.com/lelayf/gimp-lomo/main/gimp-lomo.scm) and place it in one of these folders. This is a script written in the [Scheme](https://groups.csail.mit.edu/mac/projects/scheme/) language, pretty cool if you ask me!
- `Filters > Script-Fu > Refresh Scripts`
- Open an image and Select All (Cmd/Ctrl-A)
- Then `Script-Fu > Utils > Apply Lomo LC-A Effect`
- The defaults are usually pretty good. Feel free to play with the input parameters in the dialog box to adjust saturation, contrast and vignetting.
- `File > Export` to flatten and save back to JPEG (otherwise GIMP would save in its very own XCF format, which keeps track of individual layers, palettes and whatnot)


Like it? Use hashtag __#lomogimp__ in your social media posts!


Default settings on an old classic [I took in 2005 in France](https://www.flickr.com/photos/kmf/4916250/in/photolist-rcqW): two chairs of the [Société Nationale des Sauveteurs en Mer](https://www.snsm.org/)


![](4916250_1664e6e0ae_o.jpg)
Copyright François Le Lay