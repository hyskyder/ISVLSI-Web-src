# [IEEE Computer Society Annual Symposium on VLSI - ISVLSI](http://www.eng.ucy.ac.cy/theocharides/isvlsi18/index.html)


## Visit our Website

[![Visit](http://www.eng.ucy.ac.cy/theocharides/isvlsi18/img/ISVLSI_lable.png)](http://www.eng.ucy.ac.cy/theocharides/isvlsi18/index.html)
[Visit](http://www.eng.ucy.ac.cy/theocharides/isvlsi18/index.html)



## Edit the Site

This project uses gulp workflow to generate the target files. Source code is in the "dev" folder. Please edit files in the "dev" folder; do not touch the "publish" folder.

## Workflow

### Basic

0. Setup the environment.
1. Edit source files in the "dev" folder.
2. Compile the site:
    * command: `gulp force-html`
3. Upload to the server:
    * command: `./upload2ftp.sh`

### Gulp Pipe

To generate final HTML output, we instruct the gulp to pipe the source files through the following three plugins:

    gulp-data  -->  gulp-swig  -->  gulp-include-file

- - -

## Copyright

Copyright 2018 ISVLSI. All rights reserved. Content is free for viewing.
