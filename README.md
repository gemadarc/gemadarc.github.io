# Source code for pire.gemadarc.org

## To contents editors

The contents are written in markdown format as described here: https://guides.github.com/features/mastering-markdown/. One can directly edit any file ended with **.md** using the github UI.

### How to add pictures

We save pictures in corresponding directories in our Google drive directory, gemadarc. Right click on the picture, select "Get shareable link", copy the link, go to https://github.com/gemadarc/gemadarc.github.io, edit the md file you need to work on, paste the link to the parenthesis as shown below:

```
![won't work](https://drive.google.com/open?id=0BwM7XYhFgK7odmI0SWo3ZmdwalU)
```

Change "open" to "uc":

```
![a working image](https://drive.google.com/uc?id=0BwM7XYhFgK7odmI0SWo3ZmdwalU)
```

You can click "Preview changes" to see if it works for you. Good luck!

## To site administrators

The contents written in markdown format are converted to HTML format by [jekyll](https://jekyllrb.com/). The layouts of web pages are defined in files in the \_layouts/ directory, which combine files in the \_includes/ directory and those **.md** files.
