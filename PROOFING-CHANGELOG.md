# Proofing Changelog

### 6.0.19

Bugfixes (10/24/17)

* fix failure to obey "bypass shipping" gallery setting
* don't display admin "send all images" button for parent galleries

### 6.0.18

WP 4.9.0 Compat (10/19/17)

* prevent errors from changes introduced by WordPress in `4.9.0`

### 6.0.17

Bugfix (10/5/17)

* fix bug causing errors adding images to packages between sibling galleries

### 6.0.16

Bugfix (5/17/17)

* guard against rare fatal error from corrupt data

### 6.0.15

Bugfix (4/27/17)

* fix slightly incorrect auto-update timing logic
* compatibility fix for ProPhoto `6.20.x`

### 6.0.14

Bugfixes (4/19/17)

* fix problem showing proofing galleries archives as grid since ProPhoto `6.18.0`
* fix compatibility problem with ProPhoto `6.18.x` causing individual downloading of images to fail
* fix inability within customizer to control number of grid items for recent proofing galleries grid

### 6.0.13

Enhancement (3/21/17)

* prevent image zip order problems caused by setting watermark to design watermark when no watermark set for design

### 6.0.12

Enhancement (3/10/17)

* clarify requirement of WordPress version of at least `4.4.0`, bailing if not compatible

### 6.0.11

Bugfixes (3/8/17)

* fix issue where admin-generated email of order images could include non-purchased images
* fix rare problem with registration incorrectly indicating invalid registration id
* prevent some problems with image order zips caused by caching plugins
* ensure protected gallery landing pages from password shortcode can display large numbers of galleries
* prevent some rare PHP warnings from incorrect/corrupt order data

### 6.0.10

Bugfix (1/22/17)

* fix rare problem where image downsizing threshold could cause delivery of original images when not desired

### 6.0.9

Bugfix (1/20/17)

* fix non-working option to always show collection icon when not hovered, when image added to collection

### 6.0.8

Site compatibility (12/28/16)

* ensure compatibility with new pro.photo site relaunch

### 6.0.7

Bugfix (12/15/16)

* fix more non-localized prices in order reports, for individual cart line items

### 6.0.6

Bugfixes (12/13/16)

* ensure order reports use correct localized currency
* ensure order reports contain phone number when present

### 6.0.5

Bugfix (12/7/16)

* fix rendering bug with cover photo overlay appearance

### 6.0.4

Bugfix (11/29/16)

* make sure child galleries respect parent gallery watermark selection

### 6.0.3

Bugfixes (10/27/16)

* fix rare PHP warnings for certain gallery setups
* allow downloading of images for non-logged-in users when downloads free for all

### 6.0.2

Enhancement (10/26/16)

* switch to communicating with newer, faster, isolated proofing API

### 6.0.1

Bugfix (10/22/16)

* remove debugging code introduced in `6.0.0` causing problems with user download requests

### 6.0.0

Enhancement (10/20/16)

* try to guard against killed processes and surface error messages for user download requests

### 6.0.0-beta32

Bugfix (10/6/16)

* prevent javascript error when resetting cart

### 6.0.0-beta31

Bugfixes (10/5/16)

* fix tiny admin display quirk with very short product names on reorder screen
* fix broken sortable products due to ProPhoto update
* prevent carts from getting stuck when products deleted

### 6.0.0-beta30

Bugfixes (9/28/16)

* fix parent galleries with cover photo header and grid-style children
* fix missing download options for sending images as an admin
* ensure newly added package item variations are properly stored

### 6.0.0-beta29

Enhancement (9/27/16)

* retry failed image api requests in admin order screen

### 6.0.0-beta28

Bugfix (9/10/16)

* "no watermark" should be an option for digital download products

### 6.0.0-beta27

Bugfixes (9/8/16)

* show admin notice if ProPhoto image downsizing is disabled, which causes problems
* ensure that gallery images are deleted when gallery is deleted
* fix problem with invisible product variation text for package products in Firefox

### 6.0.0-beta26

Bugfixes (9/6/16)

* prevent sending digital download emails for orders with zero digital downloads
* fix initial state of collection enable/disable toggle for new galleries

### 6.0.0-beta25

Color opacity compatibility (8/31/16)

* support opacity options for all colors for ProPhoto `6.10.0`

### 6.0.0-beta24

Bugfix & enhancement (8/24/16)

* fix issue on certain servers where admin pre-emptive creation of image sizes hangs on first image
* significantly speed up admin pre-emptive creation of image sizes

### 6.0.0-beta23

Bugfixes (8/10/16)

* fix rare loophole where used-up discount code could be applied to cart total
* fix font-style applied to single modal sidebar title

### 6.0.0-beta22

Forward compatibility (8/8/16)

* update file for future-compatibility with ProPhoto `6.9.0`

### 6.0.0-beta21

Bugfixes (8/5/16)

* always allow non-logged in user to download individual image if download is set to be free for all visitors
* fix post-save display of shipping cost table input box

### 6.0.0-beta20

Bugfixes & enhancements (8/3/16)

* *Enhancement:* support more PayPal currencies
* *Enhancement:* redirect user to "show all" screen after removing last image from filtered collection
* fix non-working default exif-data enable/disable value
* update admin link into customizer to match ProPhoto `6.7.0` routing
* fix problem with bottom value of shipping total cost table admin area
* remove unused product variation description
* improve close modal tooltip language
* fix changing of product quantity from view-cart modal
* fix edit gallery page metabox help icons behavior

### 6.0.0-beta19

Bugfixes (7/25/16)

* support proofing galleries in select posts grids
* fix link to proofing customizer area from main WordPress admin
* ensure correct template is used for generated proofing CSS

### 6.0.0-beta18

Bugfixes (7/21/16)

* fix missing thumbs after window resize while modal displayed

### 6.0.0-beta17

Bugfixes (7/14/16)

* fix authentication of individual image downloads by email address
* fix warning generated for default variation value

### 6.0.0-beta16

Bugfixes (7/11/16)

* fix fatal error from product group pricing
* render child gallery breadcrumb links
* localize currencies for admin order email notifications

### 6.0.0-beta15

Bugfixes (7/7/16)

* use protected gallery title format from proofing settings
* fix php notice from variable typo visible when `WP_DEBUG` enabled

### 6.0.0-beta14

Bugfix (7/4/16)

* fix parent galleries not displaying more than five child galleries

### 6.0.0-beta13

Bugfix (6/28/16)

* fix initialization of product categories so that first category starts selected

### 6.0.0-beta12

Bugfix (6/28/16)

* fix bug in rendering of child galleries as cover photos introduced in `6.0.0-beta11`

### 6.0.0-beta11

Bugfixes (6/28/16)

* fix handling of adjacent posts links for child & non-child galleries
* change strategy for rendering cover photos for better cross-browser consistency
* fix "error saving new user" message with unusual invalid user data
* updates for compatibility with ProPhoto `6.4.0`

### 6.0.0-beta10

Bugfixes (6/22/16)

* fix "from" address for emails sent to users after manual payment submission
* ensure child galleries respect their _order_ numbers
* fix non-displaying product "package" images [#597](https://github.com/downshiftorg/prophoto-issues/issues/597)
* fix password shortcode forms not working when not logged in
* fix percentage-based auto-discounts on galleries
* show number of items control for recent proofing galleries grid type

### 6.0.0-beta9

Bugfix (6/16/16)

* Fix improperly rendering gallery thumbnails when set to "cropped" [#584](https://github.com/downshiftorg/prophoto-issues/issues/584)

### 6.0.0-beta8

Bugfixes (6/15/16)

* Fix failure to render optional content for proofing galleries
* Fix obscure bug in Firefox that can make it hard to read and choose product variations

### 6.0.0-beta7

Bugfixes (6/7/16)

* Prevent grid errors if parent gallery has child gallery with no images
* Don't show child-gallery image management metabox if zero images
* Fix number of images loaded per ajax request to speed up gallery load times

### 6.0.0-beta6

Bugfixes (6/3/16)

* Fix ordering of galleries in admin list galleries screen
* Fixes from `beta5` were not applying, will be working in this build

### 6.0.0-beta5

Child gallery fixes (6/2/16)

* Fix problem with recent proofing galleries showing child galleries
* Fix problem with proofing gallery archive pages showing child galleries
* Use child gallery images for parent gallery excerpt image if no featured image set

### 6.0.0-beta4

Enhancements (5/31/16)

* *Enhancement:* restore proofing logo options commensurate with P5 plugin
* *Enhancement:* restore tutorial videos and first-time popop behavior
* *Enhancement:* support recent proofing galleries grid type

### 6.0.0-beta3

Bugfixes (5/27/16)

* Improve test for incompatible theme
* Fix bug that caused template css cache to be invalidated too frequently
* Prevent attempts to auto-update if not registered

### 6.0.0-beta2

Enhancements & bugfixes (5/25/16)

* *Enhancement:* Add experimental feature: allow ordering from mobile phones
* Correctly save gallery expiration data & trash expired galleries
* Allow customer reviewing of submitted orders
* Fix bug preventing display of blurred background images
* Fix bug when watermark profiles reference nonexistent image

### 6.0.0-beta1

Bugfixes (5/24/16)

* Fix incorrectly aligned tooltips on gallery pages
* Fix funky padding on add-to-cart sidebar button
* Ensure display of admin order details (discount code/amount, taxes, shipping) even when zero
* Fix rendering error for image size creation pop

