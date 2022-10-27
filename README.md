Assignment: CSS Hell
====================

You will skin 3 project gutenberg stories with custom CSS.

You will skin 2 versions of a possible professional homepage for your
self with 2 versions of CSS.

Read requirements.org

Read this comic http://theoatmeal.com/comics/design_hell

git clone https://github.com/abramhindle/CMPUT404-assignment-css-hell.git

# Creating the CSS File
I was able to mimic the old book vibe by slapping a faded-yellow colour background with a vignette, as well as swapping out the text colour for a faded off-black.

I ran into a couple issues with the default margin/padding applied to the body element as well as having my (external file) css rules overridden by the css rules defined in the html file itself. Simply commenting those out solved the issue.

To style the images, I added a style to se their height to 50vh so that they don't take up the whole page when scrolling past. This broke on some books, so I removed the style tags defined on the img tags themselves so my higher level rule wouldn't be overwritten.

For the images that had captions, I noticed that they all were tagged with the 'caption' class, so I added a nice orange colour to all of those using .caption {}.

I also made all of the images black and white using the grayscale filter.

License/Copyright
=================

Textual content is copyright Abram Hindle (C) 2013 under the CC-BY-SA
4.0 unported license. Attribution should be a hyperlink to the
repository and (C) 2013 Abram Hindle visibile in the text.

Code is licensed under the Apache 2.0 license.


