# Islandora Catalog Link

## Introduction

Adds the ability to search a library catalog for citations.

## Requirements

This module requires the following modules/libraries:

* [Islandora Scholar](https://github.com/Islandora/islandora_scholar)


## Installation

Install as usual, see [this](https://drupal.org/documentation/install/modules-themes/modules-7) for further information.

## Configuration

Place the 'Link to library catalog' block and configure it to only show up on citation pages.

The following configuration options can be found at admin/islandora/islandora_catalog_search:

* Open Link in new window - Adds target="_blank" to the link to open the catalog in a new window or tab (depending on your browser).

* Use image for link - Use an image for the link instead of text.

* Catalog URL - The URL to the catalog search without any parameters.

* HTTP title parameter - The name of your search's title parameter. If your search is 'www.search.com?titleparam=citation title' you would enter 'titleparam'

* HTTP author parameter - The name of your search's author parameter. If your search is 'www.search.com?authparam=john smith' you would enter 'authparam'

* HTTP issn parameter - The name of your search's issn parameter. If your search is 'www.search.com?issnparam=1234-5678' you would enter 'issnparam'

* HTTP extra parameters - This is where you enter any extra parameters that are the same for every query. For example, if your query is 'www.search.com?who=library_name&search_type=advanced&title=whatever&author=whatever&issn=whatever' you would enter 'who=library_name search_type=advanced'. You can have any number of these separated by spaces.

* Link image - You can upload an image to use for the link.

* Image width - The width in pixels of the link when using an image.

* Image height - The height in pixels of the link when using an image.

* Link text - The text to use for the link. If using an image, this text is displayed on hover.

## License

[GPLv3](http://www.gnu.org/licenses/gpl-3.0.txt)
