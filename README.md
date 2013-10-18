Solar Theme for Ghost
=====================

A stylish theme for [Ghost](http://ghost.org/) blogs, based on the [Solarized](http://ethanschoonover.com/solarized) color palette.

![Screenshot](http://i.imgur.com/P94J69S.png)


Features
-------

* **Two color schemes** — One for Solarized Dark and one for Solarized Light. Just swap the reference to the `colors-dark.css` file with `colors-light.css` if you don't like light-on-dark.
* **Responsive Design** — Solarized adapts to fit any screen size.


Installation
--------------

1. Clone the repository and upload the `solar` directory to your Ghost blog's `content/themes` folder.

2. Go to the Settings page of the Ghost backend and select `solar` from the Theme dropdown.

3. There is no step 3.


Customization
-------------

Solar supports Ghost's logo and cover image features, and will work perfectly fine with or without them. If you wish to upload a cover image, it will appear above the rest of the page. An uploaded logo replaces the textual blog name. (If you later decide you don't want a logo or cover image, you can remove it by clicking on the appropriate option in Settings and selecting the trash can icon.)


To-Do
-----

* Add syntax highlighting, possibly with [Prism.](http://prismjs.com/) There's already basic code block styling in place, but no syntax highlighting yet.
* The Jekyll version of Solar has linkblog support, while the Ghost one does not. This is because there isn't a finalized plugin API for Ghost yet, and there is no built-in linkblogging or post meta feature as of yet. This may change as Ghost's feature set is filled out more.


License
---------

GPLv2 or higher