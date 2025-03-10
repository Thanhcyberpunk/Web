=============
Tempera WordPress Theme
Copyright 2013-16 Cryout Creations

Author: Cryout Creations
Requires at least: 4.0
Tested up to: 4.6
Stable tag: 1.4.3
License: GPLv3
License URI: http://www.gnu.org/licenses/gpl.html
Donate link: https://www.cryoutcreations.eu/donate/

We had to follow a very strict recipe to get Tempera just right. We started with a very solid framework of over 200 settings, added a very light user interface, threw in a couple of mobiles and tablets to give it that responsive elasticity, added over 50 fonts, weren't satisfied so we poured all the Google fonts into the mix, then scattered 12 widget areas for consistency, dissolved a slider and unlimited columns into a customizable Presentation Page then mixed it in as well.

We then sprinkled all post formats, 8 layouts including magazine and blog, powdered 40+ social icons and even blended in a customizable top bar for extra density. We also made it translation ready and gave it RTL language support for some cultural diversity. The secret ingredient was love and we might've spilled too much of that. 

But now Tempera has just the right feel and the right texture and is exactly what your empty WordPress canvas needs. NEW! Tempera now comes in 16 different flavors with preset color schemes!


== License ==

This program is free software: you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation, either version 3 of the License, or
(at your option) any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.

You should have received a copy of the GNU General Public License
along with this program. If not, see http://www.gnu.org/copyleft/gpl.html


== Third Party Resources ==

Tempera WordPress Theme bundles the following third-party resources:

Nivo Slider, Copyright 2010 Gilbert Pellegrom 
Nivo Slider is licensed under the terms of the MIT license 
Source: http://dev7studios.com/nivo-slider

FitVids, Copyright 2011 Chris Coyier - http://css-tricks.com + Dave Rupert - http://daverupert.com
FitVids is licensed under the terms of the WTFPLlicense 
Source: http://fitvidsjs.com/

TGM Plugin Activation, Copyright Thomas Griffin
Licensed under the terms of the GNU GPL v2-or-later license
Source: http://tgmpluginactivation.com/


== Bundled Fonts ==

The extra fonts included with the theme are also under GPLv3 compatible licenses:

Ubuntu, Copyright 2010 Dalton Maag
Licensed under the SIL Open Font License, Version 1.0
Source: http://www.google.com/fonts/specimen/Ubuntu

Droid Sans, Copyright Steve Matteson
Licensed under the Apache License v2.00
Source: https://www.google.com/fonts/specimen/Droid+Sans

Oswald, Copyright 2011-2012 Vernon Adams
Licensed under the SIL Open Font License, Version 1.1
Source: https://www.google.com/fonts/specimen/Oswald

Open Sans, Copyright Steve Matteson
Licensed under the Apache License v2.00
Source: https://www.google.com/fonts/specimen/Open+Sans

Bebas Neue, Copyright Dharma Type
Licensed under the SIL Open Font License, Version 1.1
Source: http://dharmatype.com/post/84312257192/bebas-neue

Yanone Kaffeesatz, Copyright 2010, Jan Gerner
Licensed under the SIL Open Font License, Version 1.1
Source: https://www.google.com/fonts/specimen/Yanone+Kaffeesatz

Elusive-Icons Webfont, Copyright 2013, Aristeides Stathopoulos
Licensed under the SIL Open Font License, Version 1.1
Source: http://shoestrap.org/downloads/elusive-icons-webfont/

Font Awesome, Copyright Dave Gandy
Dual-licensed under the terms of the SIL Open Font License, Version 1.1, and the MIT license
Source: http://fortawesome.github.io/Font-Awesome/

All other images bundled with the theme (used in the demo presentation page and admin section, as well as the social icons) are created by Cryout Creations and released with the theme under GPLv3 as well.


== Initial Translations ==

French - Schubertbach 
German - Elina McC
Greek - Kleanthis Manolopoulos
Hungarian - Tamás 
Italian - tinysoulstar, Mirko Milani
Japanese - Yuka Kachi
Persian - Sefid par
Polish - Andrzej
Portuguese (Brazil) - Frederico Ribeiro 
Portuguese (Portugal) - trainmaniac
Russian - Alexander, Mikhail Rodionov
Spanish - Carlol, HacKan


== Changelog ==

= 1.4.3 =
* Improved widgets styling to be easier to override with custom styling
* Fixed topbar overlapped by admin bar when static; converted custom styling to rely on body classes; disabled fixed position on <600px (like the WP admin bar)
* Moved Magazine Layout option under Layout section for better consistency
* Fixed magazine layout option overlapping presentation page posts per columns option
* Changed More Posts button label from theme text to configurable option in the settings page (and included in wpml-config.xml list of strings)
* Added "nirvana_columnreadmore" field to wpml-config.xml
* Added values above 2em for the Line Height option (to support eastern scripts better)
* Fixed meta bar position option applying to single posts (and hiding the Edit button)
* Updated theme URL for new site
* Updated theme news feed URL for new site structure
* Removed bundled es_ES, it_IT, ru_RU, de_DE, fr_FR, ja translations in favour of WordPress Translate ones

= 1.4.2 =
* Added author role meta to improve microformats
* Added time updated and published meta to improve microformats
* Added new WordPress.org theme tags (and removed deprecated ones)
* Removed alt attribute from post thumbnail links and removed unused third parameter $post_image_id from nirvana_thumbnail_link()
* Removed hidden leftover meta separator
* Fixed #content dl font size and line height
* Optimized CSS layout and fixed several typos
* Removed id="columnImageId0" from column images; always 0 because $counter not in loop - it was unnecessary anyway
* Added theme translation domain in style.css
* Updated all instances of the search form (searchform.php, menu hooks) and replaced IDs with classes
* Improved breadcrumbs function, added post formats support
* Fixed topbar overlapped by admin bar when static; converted custom styling to rely on body classes
* Added site title value to as header logo alt/title attributes
* Fixed meta bar borders still visible when meta bar was hidden

= 1.4.1 = 

* Clarified presentation page usage notice when static page is set
* Fixed screen-reader-text elements placement issue on RTL layout
* Clarified customizer link info to indicate settings page is only available when theme is active
* Fixed WordPress 4.4.1+ issue with plugin/theme notifications being moved in the Layout settings section
* Fixed missing sticky post styling on Blog page template
* Added missing arrow glyph to continue reading button in more tag
* Fixed header site title to not use H1 tag when homepage is static
* Fixed undefined notice related to WP_Widget_Recent_Comments when certain comments plugins are used

= 1.4.0.1 = 

* Fixed menu center align issues with multi-line menus
* Fixed presentation page overriding static frontpage (and malfunctioning as a result) 
* Changed social icon links to no longer be nofollow

= 1.4.0 =

* REMOVED THE THEME SETTINGS AND ADDED SUPPORT FOR THE SEPARATE THEME SETTINGS PLUGIN
* Integrated TGM to recommend and auto-install the theme settings plugin
* Fixed settings page to handle changed H3 to H2 headings in WordPress 4.4
* Changed presentation page to be disabled by default (in lack of theme options on fresh install without plugin)
* Added experimental support for PP columns outside their dedicated area
* Fixed main menu centered option interfering with the mobile menu
* Adjusted columns to display read more button even without entering text; improved content conditional checks
* Fixed slight author information misalignment on RTL
* Fixed sub-menu arrows on RTL
* NivoSlider-based gallery/slider plugin should no longer wrongfully add a stop button to the theme's slider
* Fixed presentation-page styling to only be applied when homepage is actually the presentation page
* Added version information to style/script enqueues on both frontend and dashboard (to fix caching issues between updates)
* Rewrote readme file and merged changelog into readme

= 1.3.3 =

* fixed centred multi-line menu change in 1.3.1 breaking submenu alignment
* added arrow indicators for sub-elements on submenu items
* fixed magazine layout alignment on RTL
* fixed sub-sub menu alignment for RTL
* fixed category icon visible for pages in search results
* fixed text inside footer widgets not covered by general text options (and using styling defaults)
* corrected two untranslatable strings
* fixed column links (rewritten in 1.3) not respecting "open in new window" option
* fixed presentation page slider/column image alt attribute HTML handling
* fixed font prototype function wrongfully localizing "general" font value
* added theme information and settings page link in the customizer

= 1.3.2 =

* added failsafe to add_theme_support('title-tag') for WP < 4.1
* fixed search double slash causing issues on some servers
* fixed PHP notice caused by unset top/main/footer menu search
* fixed PHP notice related to browseragent check
* fixed double meta info displayed in single post pages
* fixed PHP notice about old widget constructors being deprecated in WP 4.3

= 1.3.1 =

* fixed ternary operator usage for php <5.3 (introduced in 1.3.0)
* fixed centred main menu alignment functionality for multi-line menus

= 1.3.0 =

* added title-tag theme support (for WordPress 4.1)
* fixed header widget overlapping logo/title when no header image is used
* fixed sup/sub styling resets
* added slide title to alt attribute
* added presentation page column title to image alt attribute
* made presentation page column images clickable links
* moved pp column display function to includes/widget.php and made pluggable
* preliminary WPML / Polylang support for custom theme options - presentation page content and socials (currently only tested on Polylang)
* merged WooCommerce compatibility code and styling
* updated Spanish translation

= 1.2.8 =

* fixed responsive styling regression introduced in 1.2.3 affecting the presentation page columns width
* improved headings font size option to apply to presentation page titles as well
* fixed PHP notice in settings page when theme news are not available
* fixed slides count limitation when using custom posts by ID
* fixed category page with intro to follow category excerpt option, not homepage excerpt option
* fixed some textareas/inputs line-height issues on Chrome and IE
* theme now remembers the settings subsection you were on after saving (for easier navigation)

= 1.2.7 =

* improved two somewhat untranslatable strings (that used esc_attr__() )
* removed baseline vertical alignment from styling reset to correct some weird alignment layouts
* fixed Google fonts merging issue when subsets are used 
* fixed an untranslatable string (thanks to seemannKP)
* fixed max-width leftovers in editor-style.css (among other things making large images appear distorted in the editor)
* fixed ol double digits numbering not fitting into view
* fixed 2 typos in settings page
* added Portuguese (Brazil) translation
* added Japanese translation
* fixed layout/image border option non-clickable on IE 11
* fixed disappearing/too small images inside tables issue on Chrome
* (absolutely positively definitely) fixed Ajax "Load More" posts button (hopefully...)

= 1.2.6 =

* fixed "array to string conversion" notices (on PHP 5.5)

= 1.2.5 =

* fixed "More Posts" button on presentation page affecting blog pages

= 1.2.4 =

* optimized Google font calls
* added link to the theme's settings page in the customizer
* made all CSS minify-able (should now support all caching plugins that perform resource minification)
* fixed a reverse border styling affecting menu items when menu is centered
* improved RTL styling (partially provided by lior)
* fixed title tag issue
* fixed undefined notices on options save

= 1.2.3 =

* various menu fixes
* finally fixed presentation page "More Posts" button
* fixed a weird save issue affecting only some servers caused by an apostrophe in the sample in custom footer text (thank to Gordon and Bembis for helping us with the test environment)
* fixed wp.media issue
* corrected title tag code to adhere to latest Wordpress rules
* removed meta template tag
* removed leftover meta author tag
* replaced wp_convert_bytes_to_hr() (deprecated) with size_format()
* replaced get_bloginfo('url') with home_url()

= 1.2.2 =

* improved responsiveness (a bit more) for the whole theme and specifically the header area
* the header widget position is now responsive
* added option to remove hover effect on presentation page columns
* fixed theme still partially responsive after responsiveness disabled (reported by Rico)
* added option for presentation page posts column count
* updated translation files

= 1.2.1 =

* fixed breadcrumbs not handling tag pages correctly
* updated Italian translation
* updated Russian translation
* (hopefully) fixed Chrome/image related RTL issue (reported by Greenwood)
* fixed parent menu items of the current page having the wrong background colour in the dropdown menu
* fixed hide table option doesn't hide table head borders
* fixed menu disappearing after switching between desktop and (the new) mobile menu (introduced in 1.2)
* improved custom widgets support in presentation page columns

= 1.2 =

* added a brand new mobile menu
* added "Contact" social icon (same icon as Email) – can be used to link to the contact page/section/form
* added "Phone" social icon for callable phone number links on touch-enabled devices
* added zoom option to allow up to 3x zoom on mobile devices
* added header widget area size (can be set to: 60%, 50%, 33%, 25%; default to 33%)
* added new menu right align option to correctly display the menu items in the same order as left/center; the old right align menu item was kept under a different name to better handle multi-line menus
* added Spanish translation (frontend only)
* added underline on links in slider captions
* slides automatic excerpts length is now half of the configured posts excerpt length
* fixed page templates to display breadcrumbs
* removed unneeded continue reading link filter on slider posts
* improved colour handling in responsive mode
* theme's javascript code files should now be minify-able
* disabled code added in 1.0 which should have made the footer always stay at the bottom of the page (but malfunctioned)
* improved the theme's wp_title filter to avoid doubling of site title with 3rd party feed plugins
* improved custom comments compatibility (thanks to phpcodemonkey)

= 1.1 =
 
* -skipped to avoid numbering confusion-

= 1.0.1.1 =

* undid force footer to window bottom

= 1.0.1 =

* removed arbitrary max-width  (html .mceContentBody) from Dashboard editor CSS (as it created confusion on the width and alignment of content)
* moved slider caption to bottom 20% instead of top for mobile devices
* added option to disable latest news in the theme settings page
* replaced the Presentation Page's "Nothing Found" message when there are no published posts with an explanatory placeholder message
* improved behaviour by hiding the slider caption title / text when left empty in the settings
* the Presentation Page columns widget area function is now pluggable via child theme
* add ‘color schemes' to WordPress theme description
* forced footer to window bottom *** this caused issues and 1.0.1.1 was created to undo

= 1.0 =

* added 16 preset color schemes (all color schemes from Parabola plus 2 new ones!)
* added an option for editing the space between the menu and content and another option for editing the content's left-right padding; you'll find both options under the Graphics Settings
* further enhanced the Presentation Page responsiveness (mostly the columns)
* fixed header background color setting not applying properly
* fixed the slider's left & right arrows visibility on dark backgrounds
* fixed 'More posts' loading gif animation not showing on dark backgrounds
* fixed top bar full width/site width options not working properly
* fixed HTML5 inputs display issues
* fixed Google fonts not working when extended sets were declared
* added Persian translation
	
= 0.9.9 = 

* Full frontend responsiveness
* Full presentation page responsiveness – column images keep aspect ratio when scaling
* Full admin responsiveness – you can easily and intuitively use the theme settings page from any device now
* Added colour fields failsafe (restor '#' if missing)
* Added 'Disable' options for presentation page slider and columns
* Fixed menu borders when menu alignment changes

= 0.9.8 = 

* Replaced Presentation Page pagination with Ajax 'More Posts' button
* Fixed 'Continue reading' button on all browsers
* Added support for HTML and shortcodes inside the Presentation Page columns
* Fixed spacing issues on the Presentation Page when certain components were enabled/disabled
* Fixed line height for slider titles
* Fixed site title font size not reducing on mobile
* Fixed giant smileys in captions :)
* Added Italian and Polish languages

= 0.9.7 = 

* the 'Continue reading' button always starts in a new line now
* added shortcode support  in the Presentation Page titles
* fixed main menu submenus going behind the slider navigation
* fixed sidebar links not changing colors to those set in the theme settings
* fixed blockquotes inside posts on the Presentation Page
* added support for all HTML5 inputs on hover as well
* added Russian language
* added a new hi-res screenshot (880x660px)

= 0.9.6 = 

* fixed bug in post information metas on single pages
* CSS styling now affects all HTML5 input types
* fixed caption alignment issues
* presentation page titles now accept HTML tags
* fixed click-able area on the header that was only half width due to header widget

= 0.9.5 =

* removed hardcoded fonts from the Presentation Page (they’re assigned the font set in the Headings Font setting)
* the header widget is no longer behind the header image
* the empty sidebar placeholders now show up properly
* fixed import/export settings not working on some rare occasions
* socials on 'Left Side' now show when enabled
* fixed a small icon fonts issue
* added an alert for variable limit reached
* added French language

= 0.9.4.1 = 

* approved in the repository
* Presentation page columns now show text on mobile browsers
* Fixed columns responsiveness when using data from posts
* Fixed some text domain issues in the comments
* Fixed the 'Continue Reading' button's animation on Google Chrome and mobile browsers
* Fixed logo and header upload inputs saving the same data in the theme settings
* Added recommended size information for the column images inside the Columns widget area

= 0.9.3 = 

* improved presentation page columns sizing
* fixed XSS vulnerability in frontend.js
* checked and corrected WordPress 3.8 readyness (admin styling and theme tags)

= 0.9.2 = 

* Fixed excessive pagination in custom category pages
* Replaced query_posts with WP_Query in page-with-intro and blog-page templates
* Removed the focus to the search form in 404 pages
* Fixed search input on Google Chrome

= 0.9.1 =

* All external links in the Tempera Settings page now open in a new tab
* All info boxes in the Tempera Settings page can now be hidden
* Added pagination to the Presentation Page if Show Posts is enabled
* Removed leftover default.mo from the theme directory
* The ​http:// protocol has been removed when enqueuing Google fonts
* Fixed back to top button not changing to the color of the content 

= 0.9 = 

* Initial theme release
