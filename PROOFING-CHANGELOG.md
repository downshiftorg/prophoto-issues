# Proofing Changelog

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
* fix non-displaying product "package" images [#597](https://github.com/netrivet/prophoto-issues/issues/597)
* fix password shortcode forms not working when not logged in
* fix percentage-based auto-discounts on galleries
* show number of items control for recent proofing galleries grid type

### 6.0.0-beta9

Bugfix (6/16/16)

* Fix improperly rendering gallery thumbnails when set to "cropped" [#584](https://github.com/netrivet/prophoto-issues/issues/584)

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

