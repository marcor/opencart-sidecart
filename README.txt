===============================================
   OPENCART Side Cart Module 1.0
===============================================

Loosely based on Ben Johnson's Cart Module v.1.7 available from here:
http://www.opencart.com/index.php?route=extension/extension/info&extension_id=2184


Requirements
==============
Opencart v. 1.5.2.1
vQmod v. 2.1 (http://code.google.com/p/vqmod/)

Although not necessary I also suggest you install the free vQmod Manager extension:
http://www.opencart.com/index.php?route=extension/extension/info&extension_id=2969


Installation
==================
1) Copy the admin, catalog and vqmod directories to the root directory of your installation. 

2) Copy common.js into the catalog/view/javascript directory.
If you don't want to overwrite the file, take a look at the code: I commented all the additions 
I made so that you can easily copy and paste them without losing your own customizations.

3) You might want to hide the thumbnails if they push the content over the borders of the 
columns. You can do this by adding this line to your theme's stylesheet.css:
    
.box .mini-cart-info .image { display: none; }




