# pressbooks-b4l-child

A WordPress child theme for Pressbooks McLuhan theme.

Contributors: @colomet,  @danzhik 

Tags: pressbooks, theme

Tested up to: [![WordPress](https://img.shields.io/wordpress/v/akismet.svg)](https://wordpress.org/download/)


Stable tag: [![Current Release](https://img.shields.io/github/release/Books4Languages/pressbooks-books4languages.svg)](https://github.com/Books4Languages/pressbooks-books4languages/releases/latest/)

License:  [![License](https://img.shields.io/badge/license-GPL--2.0%2B-red.svg)](https://github.com/Books4Languages/pressbooks-books4languages/blob/master/license.txt)

License URI: http://www.gnu.org/licenses/gpl-2.0.html

## Description  

Pressboks B4L child theme is a child theme based on pressbooks Clarke theme. This theme has been modified with support of featured images for posts in back-end and displaying them in the single post front-end.  

## Installation 
1. Clone (or copy) this repository to the ```/wp-content/themes/``` directory.
2. Activate the theme through the 'Themes' screen in WordPress.

## Frequently Asked Questions 


## Requirements 
Theme works with:

- ![PHP](https://img.shields.io/badge/PHP-7.X-blue.svg)

- [![Pressbooks](https://img.shields.io/badge/Pressbooks-V%205.3.0-red.svg)](https://github.com/pressbooks/pressbooks/releases)


- [![McLuhan Theme](https://img.shields.io/badge/McLuhanTheme-V%202.3.0-red.svg)](https://github.com/pressbooks/pressbooks-book/releases).

## Disclaimers 
The modificated Pressbooks child theme is supplied "as is" and all use is at your own risk.

## Screenshots 
You can see all of the screenshots of the theme [here](https://github.com/my-language-skills/pressbooks-b4l-child/blob/developer/books-for-languages-theme/screeenshots/screenshots.md).
## Roadmap


## Changelogs 
### 0.2
* **ADDITONS**
	* New footer

		* New file: **footer.php** Shows the list of resources links,  shows the link with a image of the book on which it is based, shows the related books information and also show the Educational information.

	* In functions.php

		* New function: **is_post_type($type)** returns true if type is a post type part and if  **are_related_books_enabled($post->ID)** return true. 


* **ENHANCEMENTS**
	* Remove the sidebar.php file.

* **List of files revised**

	* functions.php
	* footer.php


### 0.1
* **ADDITONS**
	* New sidebar.php
 	
 		* New file: **sidebar.php** in this file are added new buttons for the new sidebar and new divs that are the pop out for the new buttons. Prints all the information about the resources links that are in pressbooks-metadata-related-content plugin.
 		* New file: **pop-out.js**  that contains the function **click**.
 		* New function: **click** that add or remove the pop-out.  

	* In functions.php
	
 		* New function: **pm_enqueue_scripts**: this function fixes pop-out for  extra sidebar buttons.
 		* New action:**wp_enqueue_scripts**: call a theme_enqueue_styles function.
 		* New action: **wp_enqueue_scripts**: call a pm_enqueue_scripts function.
 	
 	* In style.css
 		* New style: add styles to new buttons in sidebar and add style to pop-out.

		

* **List of files revised**

	* functions.php
	* sidebar.php
	* style.css
	* pop-out.js


## Upgrade Notice 

### 0.2
To use the last version of this theme.

### 0.1
To use the version 0.1 of  Austen theme.

## Credits 
Here's a link to [WordPress Plugin Boilerplate](http://wppb.io/).

Here's a link to [WordPress](https://wordpress.org/)

Here's a llink to [PressBooks](https://pressbooks.org/get-involved/)

Here's a link to [Dilinger](http://dillinger.io/)

Here's a link to [Pandao](https://pandao.github.io/editor.md/en.html)

Here's a link to [Markdown's Syntax Documentation](https://daringfireball.net/projects/markdown/syntax)



