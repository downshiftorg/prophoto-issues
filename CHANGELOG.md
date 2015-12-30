# Changelog

#### 6.0.0-beta9

Excerpt images, better responsive images, and bug fixes (12/30/15)

* *New feature*: Excerpt images
* Improve responsive image rendering at large screen sizes
* Add debug logging for database errors
* Fix bug with new row creation that could cause fatal errors and white screens
* Fix bug causing spacing to appear on gallery images
* Fix bug during initial theme activation showing WordPress database error warning


#### 6.0.0-beta8

New features, enhancements, and bugfixes (12/24/15)

* *New feature*: Google fonts support (see Customizer > Fonts > Google fonts)
* *New feature*: customizable top/bottom borders for blocks and rows
* Improved row max-width by centering constrained rows
* Added text alignment options for Grid styles
* Increased font style font max size to 100px
* Fixed row-max width setting not working for "Site" level
* Fixed non-working comments options and significantly improved comments customizability
* Fixed bug rendering WordPress admin toolbar on front at small screen resolutions
* Fixed bugs with font style appearances within widgets


#### 6.0.0-beta7

Two new features, plus various enhancements and bugfixes (12/21/15)

* *New feature*: set block height to viewport height
* *New feature*: set background sizing to "cover" or "contain"
* Prevent customizer WP Admin button from returning to front
* Give truncated grid excerpts elipses
* Fix ajax error when saving unchanged grid
* Fix errors and unsightliness caused by gallery shortcodes leaking into grid excerpts
* Fix bug where select post/page grids would not render more than 5 items
* Fix srcset errors when uploading images with spaces in filename


#### 6.0.0-beta6

Includes various fixes and enhancements (12/18/15)

* Temporarily prevent reordering rows between blocks to prevent data corruption
* Fixed bug causing post title font styles to not apply to pages
* Don't show background image options when no image uploaded
* Fixed a bug that could cause grid images to not appear
* Fixed rendering of some input box comments in the content customizations area
* Fixed a bug that could cause some comments to have transparent text color
* Refactored main design query to prevent $wpdb memory errors


#### 6.0.0-beta5

Includes various fixes and enhancements (12/14/15)

* Fixed a bug where some body classes were missing
* Fixed a bug where the WordPress media uploader was not spawning in the Gallery post editor
* Fixed a modal height issue with Firefox. The widget modal should be the correct height now and scroll
* Fixed a comments spacing issue in Firefox
* Fixed a bug where comments were not rendering when enabled via site settings
* Fixed a modal min-height bug in IE10 and 11
* Fixed a customizer menu icon centering issue in IE10
* ProPhoto text widget now shows alignment settings while editing
* Menu builder is now vertically scrollable on smaller resolutions
* The gallery customization screen has an updated header with better styles and usability
* Blurbs and help text containing HTML now render HTML correctly
* Front end edit links now work


#### 6.0.0-beta4

Includes various fixes and enhancements (12/11/15)

* Cropped grid images should have correct aspect ratio
* Fixed bug with grid images not loading correctly
* Fixed a fatal error issue with the responsive image modifier
* Customizer UI now correctly shows style inheritance
* Facebook comments no longer trigger a fatal error preventing the footer from rendering scripts
* General WordPress 4.4 compatibility
* Client side templates no longer trigger errors on hosts with ASP tags enabled
* Gallery custom post type removes the text editor
* New font styles are added to the selectable list and put in focus
* Fixed a bug where new designs could not be created in WordPress 4.4
* Bootstrap CSS gutter set to 0 to address conflict with customizer CSS
* Gallery shortcodes now parse styles correctly
