# phpbb-bootstrap
This is a skeleton theme for phpBB 3.1 making use of Twitter's Bootstrap 3 and the twig templating engine.

The template files have been reworked to make use of twig layouts. The familiar `overall_header.html` and `overall_footer.html` files no longer exist. Both are now found inside `layout_main.html`.

## Requirements
This theme requires Bootstrap v3. This repo only contains phpbb's template files and a few css overrides.

You'll need to put Bootstrap's css and javascript somewhere and add them somewhere inside `layout_main.html`. 

## Notes
In 3.1 phpBB has implemented the twig templating engine. Some of the tags in this template now use twig syntax instead of the older phpBB templating syntax. Not all of the tags have been replaced yet, though.
