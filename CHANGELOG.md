# Changelog

#### 6.0.0-beta15

Bugfixes and usability enhancements (1/18/16)

* Improved page meta box for template selection
* Add auto-update support for our new [Test Drive Plugin](https://github.com/netrivet/prophoto-test-drive)
* Fixed incorrect rendering of special characters on front-end
* Fixed footer links removal with valid license
* Fixed errors when deleting designs in the "Manage Designs" screen
* Fixed text diplay errors in "ProPhoto Updates" settings box
* Fixed custom css in child templates
* Guard against errors caused by missing menu items
* Fix error caused by editing existing menu items
* Don't fatal error on embedded gallery that has been deleted
* Don't render trashed gallery


#### 6.0.0-beta14

Bugfixes (1/14/16)

* Fix error causing saving of new FontStyles to not work
* Prevent fatal error when gallery embedded in post is fully deleted
* Do not render gallery in post when gallery has been trashed
* Fix customizer font areas dropdown falling behind uploaded image preview
* Prevent PHP warnings from `ini_set()` from interfering with theme activation
* Fix error on 404 pages
* Fix menu alignment in horizontal menus containing link with no URL
* Fix comment line separation for Crafted design


#### 6.0.0-beta13

Bugfixes (1/14/16)

* Fix bug creating brand new design that resulted in fatal PHP error
* Fix bug in modal displays in customizer for Internet Explorer 11
* Guard against and advise when required `PDO mysql` driver missing, instead of error
* Fix font styling of comment author links


#### 6.0.0-beta12

New features and bugfixes (1/13/16)

* **New Feature: [Multiple templates](https://gist.github.com/jaredh159/849e64eb9eb6cdfc14dc)**
* **New Feature: [Site-level responsive breakpoint customizations](https://gist.github.com/jaredh159/a83a98becb3c782f97d8)**
* *New Feature:* Bulk-create page and gallery menu items
* *New Feature:* [Support using/testing P6 while still running P5](https://gist.github.com/jaredh159/e0ba2ef8186d47c0f407)
* Automatically add newly created menu items to menu currently being edited
* Sort menu items newest on top
* Fix bug that could break site if menu item delete failed
* Fix missing grid items in grids below content
* Prevent fatal errors when widget data can't be found
* Fix bug that caused grids to render wonky with paddings and large borders
* Fix missing support for site-level block height controls
* Fix bug with inherited state and reversion in row max width areas
* Made ProPhoto text widget text alignment more reliable
* Fix bug that made mobile menu impossible to close if window enlarged
* Fix menu bug that made all menus hidden at viewport width of 768px (iPad in portrait)
* Batched several types of customizer API requests for greater speed and error prevention
* Fix bug with uploading design images that had `+` in filename


#### 6.0.0-beta11

Bugfixes (1/4/16)

* Remove non-working grid comments-count customization until feature restored
* Fix wording of grid item padding controls
* Main ProPhoto WordPress admin link goes to Customizer screen, not settings
* Workaround CloudFlare caching error that causes uploaded images to not be seen
* Add db migration to attempt to repair data integrity customization issues from previous bug
* Fix Google fonts only allowing fonts that start with "A"


#### 6.0.0-beta10

Bugfixes (12/31/15)

* Fix bug that could cause column, row, or block customizations to not inherit properly
* Fix bug causing customizer modal screen to break in Firefox
* Fix bug with cropped images in grids not rendering correctly
* Remove non-working gallery grid display options until restored
* Remove non-working grid spacing between option, now controlled by grid instance
* Prevent creation of multiple widgets by mashing on create button


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
