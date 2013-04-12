# Prestashop responsive theme

This theme is forked from the default prestashop theme of the 1.5.4 version. I used [unsemantic.com](http://unsemantic.com/), which is recommended on [960.gs](http://960.gs/) website, to bring us the power of media queries.

The main reason why I decided to create this theme is that I wanted to offer my customers a mobile view of their shop without having to maintain both mobile and desktop themes. Another advantage is that this theme aims to be a blank theme which can be used by developers to create new themes

## Modifications made

* Added viewport
* Remove the "@import" rule from the main CSS file
* Added the many unsemantic CSS files
* Added the unsemantic CSS link of the main responsive
* Added "alpha" and "omega" exceptions to the grid
* Added "max-width:100%" to images in the left and right column in mobile view
* Removed horiizontal padding to the left and right columns in mobile view
* Replaced "container_9" class name with "grid-container"
* Replaced "grid_9" class name with "grid-100" as main wrapper
* Replaced "grid_6" class name with "grid-65" in the right header block
* Replaced "grid_5" class name with "grid-60" in the center column
* Replaced "grid_2" class name with "grid-20"for the left and right columns
* Replaced "grid_2" class name with "grid-50" in the stores page
* Replaced the width of the center column from "757px" to "80%" when there is no left column
* Added "mobile-grid-100" class name to the right block of the header
* Added CSS and IMG from modules :
** blockcart : mobile view
** blockcurrencies : mobile view
** blocknewproducts : override the left margin in the right column
** blockpermanentlinks : mobile view
** blocksearch : mobile view
** blocktopmenu : override the menu width
** blockuserinfo : mobile view

## TODO

* Make the top menu dropdownable
* Make the shopping cart clickable
