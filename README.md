# JMW Blocks Theme

This repository is a small playground to learn how to create 
full-site editing enabled themes for WordPress.

# Minimum Requirements
The documentation for full-site editing is still evolving. I've learned through the 
process of going through documentation on [fullsiteediting.com](https://fullsiteediting.com) and
the [official WordPress documentation on full-site editing](https://developer.wordpress.org/block-editor/how-to-guides/themes/create-block-theme/)
that you must have, at an absolute minimum, the following files and directory
structure to enable full-site editing in your theme:

- index.php
- style.css
- block-templates/index.html

The first two files are typical for WordPress theme registration. The block-templates
directory must contain an index.html file, which essentially replaces the markup that would
traditionally be included in your index.php file.

Additionally, you're _likely_ going to want to include a theme.json file.

# Additional options
The `block-template-parts` directory can include any template parts needed for re-use within 
the theme.
