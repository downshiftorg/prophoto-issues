# Changelog

### 6.12.2

Bugfix

* fix errors copying or saving edits to tiles made previous to `6.12.0` [#703](https://github.com/netrivet/prophoto-issues/issues/703)

### 6.12.1

Bugfixes

* fix slightly incorrect alignment of vertically centered rollover grid text
* prevent design on-boarder from hanging when bad menu item data encountered

### 6.12.0

Features, enhancements and bugfixes -- [Blog post](https://www.prophoto.com/blog/prophoto-6-12-0/) (9/14/16)

* **New feature:** Mobile menu toggle can now be a ProPhoto tile with customizeable "active" state [#357](https://github.com/netrivet/prophoto-issues/issues/357)
* **New feature:** Optional background images for grid items & background color/image for whole grids [#677](https://github.com/netrivet/prophoto-issues/issues/677)
* *Enhancement:* overlay grid text vertical alignment control [#676](https://github.com/netrivet/prophoto-issues/issues/676)
* *Enhancement:* control text length of post grid item excerpt text [#678](https://github.com/netrivet/prophoto-issues/issues/678)
* *Enhancement:* allow uploading of "featured" images for categories, for use in category grids [#592](https://github.com/netrivet/prophoto-issues/issues/592)
* *Enhancement:* allow uploading of grid item fallback images [#354](https://github.com/netrivet/prophoto-issues/issues/354)
* fix overlay grid overlays not always perfectly matching size of underlying image [#162](https://github.com/netrivet/prophoto-issues/issues/162)
* fix WP RSS feed request not redirecting to Feedburner when valid Feedburner url set [#569](https://github.com/netrivet/prophoto-issues/issues/569)
* fix background color for light-color font-style previews [#696](https://github.com/netrivet/prophoto-issues/issues/696)
* fix custom grid items set to open link in new page not working for clicks on rollover overlay [#697](https://github.com/netrivet/prophoto-issues/issues/697)

### 6.11.1

Enhancement & bugfix (9/8/16)

* *Enhancement:* re-enable Pinterest "pin site image" Call to Action item now that it should be working reliably
* fix php notice from `6.11.0` that breaks tile display only when `WP_DEBUG` turned on

### 6.11.0

Features, enhancements and bugfixes -- [Blog post](https://www.prophoto.com/blog/prophoto-6-11-0/) (9/7/16)

* **New feature:** Pinterest pinning of individual content images [#229](https://github.com/netrivet/prophoto-issues/issues/229)
* **New feature:** Toggle visibility of nested items in mobile/vertical menu [#282](https://github.com/netrivet/prophoto-issues/issues/282)
* *Enhancement:* allow aligning mobile menu and hamburger icon on site right side
* *Enhancement:* allow translating of menu item and graphic widget urls for WPML [#695](https://github.com/netrivet/prophoto-issues/issues/REPLACE)
* fix problem with phantom image attachments being generated when downsizing threshold set very low [#690](https://github.com/netrivet/prophoto-issues/issues/690)
* fix failure to show customization group "locked" state when jumping between levels with breadcrumbs [#691](https://github.com/netrivet/prophoto-issues/issues/691)
* fix galleries that hang because of missing thumbnail sizes [#688](https://github.com/netrivet/prophoto-issues/issues/REPLACE)
* fix grid display bug when sizing constraints set extremely narrow [#692](https://github.com/netrivet/prophoto-issues/issues/692)
* fix problem importing remote design assets from `us-east-1` Amazon S3 region
* fix display of form submission email subjects to honor timezone setting [#694](https://github.com/netrivet/prophoto-issues/issues/694)

### 6.10.2

Bugfix (9/1/16)

* fix galleries showing up empty in non-primary lanugage when using WPML
* fix incorrect front page displaying when using WMPL string translation
* fix overlay grid background color not displaying after 6.10 update

### 6.10.1

Bugfix (8/31/16)

* fix empty space below grid in certain scenarios (introduced in 6.10.0)

### 6.10.0

New features, enhancements, and bugfixes -- [Blog post](https://www.prophoto.com/blog/prophoto-6-10-0/) (8/31/16)

* **New feature:** Use tile or image for custom form _submit_ button [#550](https://github.com/netrivet/prophoto-issues/issues/550)
* **New feature:** Support opacity option for every customizable color [#430](https://github.com/netrivet/prophoto-issues/issues/430)
* **New feature:** Column border customizations [#314](https://github.com/netrivet/prophoto-issues/issues/314)
* *Enhancement:* Clarify customization UI when customizations inheriting from parent template [#521](https://github.com/netrivet/prophoto-issues/issues/521)
* *Enhancement:* Allow toggling of grid item optional text in every situation [#674](https://github.com/netrivet/prophoto-issues/issues/674)
* *Enhancement:* Allow clicking directly to where inherited customization is coming from in tooltip [#225](https://github.com/netrivet/prophoto-issues/issues/225)
* *Enhancement:* Add clickable breadcrumbs for template/block/row/column items
* *Enhancement:* Use image from embedded gallery as post excerpt image when no other image present [#438](https://github.com/netrivet/prophoto-issues/issues/438)
* *Enhancement:* Ensure grids that don't take up full width of context are centered [#333](https://github.com/netrivet/prophoto-issues/issues/333)
* *Enhancement:* Only permit renaming blocks at highest template level to prevent the illusion of upward inheritance
* fix cropped grids not keeping rows even when differing amounts of text [#421](https://github.com/netrivet/prophoto-issues/issues/421)
* fix password protected galleries not showing password form [#682](https://github.com/netrivet/prophoto-issues/issues/682)
* fix problem with translated `page for posts` in WPML [#681](https://github.com/netrivet/prophoto-issues/issues/681)
* ensure custom grid item opens in new window/tab when set to [#673](https://github.com/netrivet/prophoto-issues/issues/673)
* fix a few fringe problems with form remote email sending [#672](https://github.com/netrivet/prophoto-issues/issues/672)
* improve handling of timezone for form submissions [#667](https://github.com/netrivet/prophoto-issues/issues/667)
* fix application of template-specific watermarking settings [#670](https://github.com/netrivet/prophoto-issues/issues/670)
* fix rare circumstance where ProPhoto bar would not be shown if theme file editing disabled


### 6.9.1

Bugfix (8/16/2016)

* fix custom grid items showing title twice instead of title and text

### 6.9.0

New features -- [Blog post](https://www.prophoto.com/blog/prophoto-6-9-0/) (8/15/16)

* **New feature:** Support for WPML multi-language plugin [#235](https://github.com/netrivet/prophoto-issues/issues/235)
* **New feature:** Forms now offer multiple-choice (radio) and select dropdown field options [#577](https://github.com/netrivet/prophoto-issues/issues/577)

### 6.8.0

Features, enhancements, & bugfixes -- [Blog post](https://www.prophoto.com/blog/prophoto-6-8-0/) (8/10/16)

* **New feature:** Image lazyloading (currently disabled by default) [#410](https://github.com/netrivet/prophoto-issues/issues/410)
* *Enhancement:* Design onboarding menu-item step for connecting content menu items [#639](https://github.com/netrivet/prophoto-issues/issues/639)
* *Enhancement:* Improve usability of included "Morgan" design with simpler templates and better inheritance
* *Enhancement:* Add a "blog" menu item type that always links to blog posts page
* fix thumbnail gallery and grid images not being included in right-click image protection [#665](https://github.com/netrivet/prophoto-issues/issues/665)
* add widget labels for grid widgets replaced by text placeholders
* remove embedded help widget (every admin page still has help link for contacting us)

### 6.7.3

Bugfix (8/5/16)

* fix error that caused proofing plugin users to not see their orders

### 6.7.2

Bugfixes (8/4/16)

* fix wrong layout rendered when returning to layout component after switching templates
* fix tooltip alignment for add-row elements
* fix bug that can cause very small tile borders to be invisible

### 6.7.1

Bugfix (8/3/16)

* fix inability to load Call-to-Action appearance & assignments areas in customizer since `6.7.0`

### 6.7.0

Features, enhancements, & bugfixes -- [Blog post](https://www.prophoto.com/blog/prophoto-6-7-0/) (8/2/16)

* **New feature:** Design _on-boarding_ wizard to guide through front page & template assignments [#638](https://github.com/netrivet/prophoto-issues/issues/638)
* **New feature:** Customizable form submission email subject & body [#551](https://github.com/netrivet/prophoto-issues/issues/551)
* **New feature:** Find all template background images from site front toolbar & click to edit [#637](https://github.com/netrivet/prophoto-issues/issues/637)
* **New feature:** Front-end ProPhoto bar inspect mode inspects and links to blocks, rows, columns, & widgets [#636](https://github.com/netrivet/prophoto-issues/issues/636)
* **New feature:** Form submission success & error redirect urls [#599](https://github.com/netrivet/prophoto-issues/issues/599)
* *Enhancement:* Add domain-based email `sendfrom` and remote email sending to improve email delivery rates [#641](https://github.com/netrivet/prophoto-issues/issues/641)
* *Enhancement:* Override form notification email recipeient on a per-form basis
* *Enhancement:* Don't close customization modals when clicking "save" [#465](https://github.com/netrivet/prophoto-issues/issues/465)
* *Enhancement:* Add toggle for excerpt "read more" link [#575](https://github.com/netrivet/prophoto-issues/issues/575)
* *Enhancement:* Add default "read more" link font styles to included designs
* *Enhancement:* Power customizer state through url route to allow direct linking to any state
* fix google/statcounter analytics wrongly counting admin visits [#656](https://github.com/netrivet/prophoto-issues/issues/656)
* fix incorrect sizing of sticky-block placeholder [#655](https://github.com/netrivet/prophoto-issues/issues/655)
* fix major javascript error when trying to render gallery with zero images [#652](https://github.com/netrivet/prophoto-issues/issues/652)
* isolate javascript modules to prevent error in one from bringing down others [#653](https://github.com/netrivet/prophoto-issues/issues/653)
* fix error loading image in customizer if filename contained comma [#648](https://github.com/netrivet/prophoto-issues/issues/648)

### 6.6.5

Bugfixes (7/28/16)

* prevent & fix problems with non-working front-page and call-to-action settings [#650](https://github.com/netrivet/prophoto-issues/issues/650)
* fix bug causing galleries to hang on very small images [#651](https://github.com/netrivet/prophoto-issues/issues/651)
* fix occasional weird display of long decimal values in tile height field [#649](https://github.com/netrivet/prophoto-issues/issues/649)

### 6.6.4

Enhancement/bugfix (7/26/16)

* import selected P5/4 settings [#619](https://github.com/netrivet/prophoto-issues/issues/619)

### 6.6.3

Bugfixes (7/22/16)

* fix bug resolving page for posts if WordPress option never existed [#647](https://github.com/netrivet/prophoto-issues/issues/647)
* fix email reply-to address header [#646](https://github.com/netrivet/prophoto-issues/issues/646)
* fix slashes being added to saved ProPhoto site settings [#645](https://github.com/netrivet/prophoto-issues/issues/645)
* hide P3 gallery placeholders on site front [#644](https://github.com/netrivet/prophoto-issues/issues/644)

### 6.6.2

Bugfix (7/20/16)

* fix bug affecting a few updaters to `6.6.x` causing static home page setting not to be obeyed

### 6.6.1

Bugfixes (7/20/16)

* fix rare error from archives menu item when zero published posts [#632](https://github.com/netrivet/prophoto-issues/issues/632)
* fix front-end widget link hash broken in `6.6.0`

### 6.6.0

Features & enhancements -- [Blog post](https://www.prophoto.com/blog/prophoto-6-6-0/) (7/20/16)

* Front-page settings now controlled in customizer on a per-design basis
* Reorganize customizer to clearly distinguish between _design_ and _template_ areas [#196](https://github.com/netrivet/prophoto-issues/issues/196)
* Fix problems saving site settings in very rare circumstances [#629](https://github.com/netrivet/prophoto-issues/issues/629)
* Fix deleting menu item from library pops up two modals [#630](https://github.com/netrivet/prophoto-issues/issues/630)

### 6.5.1

Bugfix (7/13/16)

* fix bug causing mobile menu hamburger icon click to not work [#623](https://github.com/netrivet/prophoto-issues/issues/623)

### 6.5.0

Features & enhancements -- [Blog post](https://www.prophoto.com/blog/prophoto-6-5-0/) (7/12/16)

* Add "ProPhoto bar" on front for admins with inspecting and direct links to edit widgets
* Allow max-height constraint based on window size for content images [#395](https://github.com/netrivet/prophoto-issues/issues/395)
* Use form submitted email address as notification reply-to address [#552](https://github.com/netrivet/prophoto-issues/issues/552)
* Cross-browser compatible form required field validation with customizable messages [#587](https://github.com/netrivet/prophoto-issues/issues/587)

### 6.4.7

Hotfix (7/11/16)

* disables caching of front-end query because we didn't consider how templates are resolved ¯\\\_(ツ)_/¯ [#621](https://github.com/netrivet/prophoto-issues/issues/621)

### 6.4.6

Performance enhancement (7/11/16)

* cache main front-end query for faster page loads

### 6.4.5

Bugfixes (7/8/16)

* fix fatal error from Seo class on pages where `$post` can't be found [#618](https://github.com/netrivet/prophoto-issues/issues/618)
* fix fatal errors on `PHP 5.3.6` [#617](https://github.com/netrivet/prophoto-issues/issues/617)
* fix errors related to call-to-action from designs exported at `6.4.0`

### 6.4.4

Bugfixes & performance improvements (7/7/16)

* optimize main design database query for faster page loads
* fix errors copying certain templates & inability to create copies of broken copies [#611](https://github.com/netrivet/prophoto-issues/issues/611)
* fix inability to import P3-era galleries if source post can't be found [#614](https://github.com/netrivet/prophoto-issues/issues/614)
* fix column vertical padding not applied on MS Edge [#612](https://github.com/netrivet/prophoto-issues/issues/612)
* fix inability to delete images in certain scenarios in customizer [#613](https://github.com/netrivet/prophoto-issues/issues/613)
* fix content images broken due to failure to correct for previous site url locations [#609](https://github.com/netrivet/prophoto-issues/issues/609)
* fix password-protected post translation settings not applying [#616](https://github.com/netrivet/prophoto-issues/issues/616)
* fix unintuitive reordering of blocks [#590](https://github.com/netrivet/prophoto-issues/issues/590)
* fix problems with SEO and Facebook meta fields [#529](https://github.com/netrivet/prophoto-issues/issues/529)

### 6.4.3

Bugfix (7/1/16)

* Minor release adding some internal tooling for troubleshooting "undeletable" widgets

### 6.4.2

Bugfixes (6/30/16)

* fixes bug where tile selector would not scroll in a modal window
* fixes bug where exported form widgets would not render on front [#606](https://github.com/netrivet/prophoto-issues/issues/606)
* fixes bug with call to action groups on multi-post pages [#605](https://github.com/netrivet/prophoto-issues/issues/605)
* fixes inheritance issue with "Nav & Logo" block in "About" and "Info" templates in bundled design "Morgan"

### 6.4.1

Bugfix (6/29/16)

* fix fatal errors resulting from call to action database changes

### 6.4.0

Thumbnail galleries, Call to Action, and more -- [Blog post](https://www.prophoto.com/blog/prophoto-6-4-0/) (6/29/16)

* **New feature:** Thumbnail-style galleries [#351](https://github.com/netrivet/prophoto-issues/issues/351)
* **New feature:** Responsive call-to-action items [#223](https://github.com/netrivet/prophoto-issues/issues/223)
* **New feature:** Gallery "full-window" mode: an alternative to "fullscreen" and a great fallback for devices that don't support HTML5 fullscreen api (iPhones, iPads, IE10)
* fix bug deleting widgets caused by possibility of using duplicate widget ids from simultaneous customizer tabs [#603](https://github.com/netrivet/prophoto-issues/issues/603)
* fix non-taxonomy custom post type (like uncategorized proofing galleries) template assignments not applying [#602](https://github.com/netrivet/prophoto-issues/issues/602)
* fix auto-update failures on certain servers caused by too-long temp filename [#601](https://github.com/netrivet/prophoto-issues/issues/601)

### 6.3.1

Bugfixes (6/23/16)

* fix crossfading galleries occasionally going blank when images slow to load [#598](https://github.com/netrivet/prophoto-issues/issues/598)
* fix fatal error caused if plugin widget deactivated before deleting widget from P6 [#596](https://github.com/netrivet/prophoto-issues/issues/596)
* improve display of small-sized image dropzone upload areas

### 6.3.0

New features, enhancements, and bugfixes --  [Blog post](https://www.prophoto.com/blog/prophoto-6-3-0/) (6/22/16)

* **New feature:** Custom grids [#220](https://github.com/netrivet/prophoto-issues/issues/220)
* *Enhancement:* Newly added block or row will now _always_ appear in all child templates, regardless of inheritance state
* *Enhancement:* Many more template assignment controls, including 404, post categories, custom post types, proofing galleries, individual posts, individual galleries [#439](https://github.com/netrivet/prophoto-issues/issues/439)
* *Enhancement:* Hardware acceleration for better tile transitions and border behavior [#501](https://github.com/netrivet/prophoto-issues/issues/510)
* *Enhancement:* Tile text layer alignment options [#459](https://github.com/netrivet/prophoto-issues/issues/459)
* *Enhancement:* Allow linebreaks in tile text layers [#458](https://github.com/netrivet/prophoto-issues/issues/458)
* Fix bug causing script/slanted fonts to be partially cut off in tile text layers [#582](https://github.com/netrivet/prophoto-issues/issues/582)
* Guard against non-standard plugin widgets that can't be rendered [#588](https://github.com/netrivet/prophoto-issues/issues/588)
* Fix hiding of sticky block at responsive breakpoints [#591](https://github.com/netrivet/prophoto-issues/issues/591)

### 6.2.4

Bugfixes & experimental PHP7 support (6/14/16)

* *Enhancement:* PHP7 support (tested, but considered _experimental_ for a few weeks) [#563](https://github.com/netrivet/prophoto-issues/issues/563)
* Fix bug with tiles showing unexpected space below [#567](https://github.com/netrivet/prophoto-issues/issues/567)
* Fix non-working Facebook comments design settings [#568](https://github.com/netrivet/prophoto-issues/issues/568)
* Fix misleading display of inheriting image settings in customizer [#490](https://github.com/netrivet/prophoto-issues/issues/490)
* Fix sticky block mobile menu problem in IE11 [#558](https://github.com/netrivet/prophoto-issues/issues/558)
* Ensure only admin-level logged in users can access ProPhoto customizer

### 6.2.3

Bugfix (6/7/16)

* Fix bug that caused javascript errors for IE10 and older browers without ES6 support

### 6.2.2

Bugfixes (6/7/16)

* Fix inheritance bug with adding new entities from parent templates
[#561](https://github.com/netrivet/prophoto-issues/issues/561)
* Fix bug with excerpt images not being found - (affects things like og:image for Facebook)
[#564](https://github.com/netrivet/prophoto-issues/issues/564)

### 6.2.0

New features & bugfixes -- [Blog post](https://www.prophoto.com/blog/prophoto-6-2-0/) (6/7/16)

* **New feature:** Copy/pasting widgets
* **New feature:** Customizable text/tile/image "Read more" excerpt links for grids and standard excerpts [#297](https://github.com/netrivet/prophoto-issues/issues/297)
* **New feature:** Upload favicon and apple-touch-icon for site identity [#281](https://github.com/netrivet/prophoto-issues/issues/281)
* **Enhancement:** Select multiple gallery images and reorder them as a group [#543](https://github.com/netrivet/prophoto-issues/issues/543)
* Fix inability to drag/drop upload images on galleries admin screens [#548](https://github.com/netrivet/prophoto-issues/issues/548)
* Fix bug that caused mobile menu top/bottom padding customization to not apply [#560](https://github.com/netrivet/prophoto-issues/issues/560)
* Fix bug with positioning of stuck sticky block when mobile menu open [#557](https://github.com/netrivet/prophoto-issues/issues/557)
* Fix bug editing existing embedded grid in post/page [#556](https://github.com/netrivet/prophoto-issues/issues/556)

### 6.1.2

Bugfixes (6/2/16)

* Hopefully fix problem copying _Morgan_ free design on 1and1 and other servers [#555](https://github.com/netrivet/prophoto-issues/issues/555)
* Resolve a few scroll-to link problems [#549](https://github.com/netrivet/prophoto-issues/issues/549)
* Fix improperly rendered Mac command character for Safari 9 [#544](https://github.com/netrivet/prophoto-issues/issues/544)

### 6.1.1

Bugfixes (5/31/16)

* Fix bug that could cause Facebook `<og:image>` image data to not update when featured image changed [#547](https://github.com/netrivet/prophoto-issues/issues/547)
* Fix bug with Proofing plugin auto-updating when WordPress not in English [#546](https://github.com/netrivet/prophoto-issues/issues/546)
* Fix bug extracting uploaded design zips on Windows servers [#545](https://github.com/netrivet/prophoto-issues/issues/545)
* Support extensible grids for Proofing grid types

### 6.1.0

Scroll-to links, usability enhancements, more -- [Blog post](https://www.prophoto.com/blog/prophoto-6-1-0/) (5/27/16)

* **New feature:** Easily create links that smoothly scroll to blocks & rows [#163](https://github.com/netrivet/prophoto-issues/issues/163)
* *Enhancement:* Numerous usability and workflow improvements for managing gallery images
* Minification of generated css for performance
* Add infrastructure for support diagnostics
* Fix bug causing menu re-ordering problems with lengthy menus [#533](https://github.com/netrivet/prophoto-issues/issues/533)

### 6.0.1

Bugfixes (5/25/16)

* Fix bug that caused last form element to be deleted instead of chosen element [#539](https://github.com/netrivet/prophoto-issues/issues/539)
* Fix problem with block-height overrides in Safari [#540](https://github.com/netrivet/prophoto-issues/issues/540)
* Fix bug that could cause unexpected gallery appearance on mobile devices [#538](https://github.com/netrivet/prophoto-issues/issues/538)
* Prevent error messages when saving a widget without changing widget data [#537](https://github.com/netrivet/prophoto-issues/issues/537)
* Fix gallery images not visible in admin if any gallery images deleted [#536](https://github.com/netrivet/prophoto-issues/issues/536)

### 6.0.0

Release, enhancements, & bugfixes (5/24/16)

* Remove beta label
* *Enhancement:* Add user-interface for easily embedding ProPhoto forms in posts/pages
* *Enhancement:* Show template in front-end WordPress admin bar as link to edit that template
* *Enhancement:* Show ProPhoto responsive screensize in front-end WordPress admin bar
* *Enhancement:* Add default spacing for graphic widget label [#464](https://github.com/netrivet/prophoto-issues/issues/464)
* *Enhancement:* Add new tile square should always be first, and scroll to copied tile
* Improve appearance of test-drive and other admin notices on form log page [#535](https://github.com/netrivet/prophoto-issues/issues/535)
* Clear tile image upload dropzone for multiple image layers [#502](https://github.com/netrivet/prophoto-issues/issues/502)
* Fix widget body `h1` font-style overriding widget headline font-style [#511](https://github.com/netrivet/prophoto-issues/issues/511)
* Prevent gallery fullscreen button from appearing on devices that don't support html5 fullscreen api [#516](https://github.com/netrivet/prophoto-issues/issues/516)
* Fix aspect ratio of uploaded design images in Safari [#525](https://github.com/netrivet/prophoto-issues/issues/525)
* Don't force prev/next gallery controls on mobile for auto-starting galleries [#528](https://github.com/netrivet/prophoto-issues/issues/528)
* Fix gallery prev/next arrow alignment when control bar outside of gallery [#531](https://github.com/netrivet/prophoto-issues/issues/531)
* Fix Facebook comments not respecting language setting [#534](https://github.com/netrivet/prophoto-issues/issues/534)
* Remove javascript popup prompt for Zendesk help widget email address
* Don't display input box explanatory help for boxes without help text

### 6.0.0-beta61

Forms & bugfixes (5/18/16)

* **New feature:** Forms [(click here for short explanation)](https://gist.github.com/jaredh159/5a1ac6283a0f9a695815810e0ff08b7e) [#350](https://github.com/netrivet/prophoto-issues/issues/350)
* Fix rare bug that can break api responses [#522](https://github.com/netrivet/prophoto-issues/issues/522)
* Improve grid initialization to prevent momentary jumble [#523](https://github.com/netrivet/prophoto-issues/issues/523)
* Use new updated video for post-registration welcome modal

### 6.0.0-beta60

Bugfixes (5/17/16)

* Fix bug where menu dropdowns in sticky block fall behind tiles in Safari [#523](https://github.com/netrivet/prophoto-issues/issues/523)
* Fix bug with sticky block positioning when block contains responsive image [#526](https://github.com/netrivet/prophoto-issues/issues/526)
* Fix problem downloading design assets on certain Windows servers
* Integration preparation for P6 version of Proofing plugin

### 6.0.0-beta59

Enhancements & bugfixes (5/11/16)

* *Enhancement:* Customizer reloads on the template you were last editing
* *Enhancement:* Clarify language of locked customization groups
* *Enhancement:* Change template-level settings gear label from "Site" to "Template"
* Fix bug with adding of blocks and rows not correctly breaking inheritance [#517](https://github.com/netrivet/prophoto-issues/issues/517)
* Fix bug with hamburger icon placement after opening mobile menu or scrolling down [#518](https://github.com/netrivet/prophoto-issues/issues/518)

### 6.0.0-beta58

Bugfix (5/10/16)

* Fix bug that could cause customizer to hang when switching templates [#515](https://github.com/netrivet/prophoto-issues/issues/515)

### 6.0.0-beta57

Sticky blocks, customizer redesign, and bugfixes (5/9/16)

* **New feature:** Make a block "sticky", with sticky-state customization overrides [#348](https://github.com/netrivet/prophoto-issues/issues/348)
* *Enhancement:* Major redesign of customizer, including faster template switching [#254](https://github.com/netrivet/prophoto-issues/issues/254)
* Fix bug with parent entity-level responsive controls not applying [#514](https://github.com/netrivet/prophoto-issues/issues/514)
* Fix bad selection of gallery style for P5/P4 legacy embedded galleries [#512](https://github.com/netrivet/prophoto-issues/issues/512)
* Fix empty grid-type site-level font style control modal tabs [#510](https://github.com/netrivet/prophoto-issues/issues/510)

### 6.0.0-beta56

Enhancements & bugfixes (5/5/16)

* *Enhancement:* add links to customization tutorials for free included starter designs
* fix broken galleries after beta55 update [#508](https://github.com/netrivet/prophoto-issues/issues/508)
* fix problems switching templates when there are orphan template entities [#509](https://github.com/netrivet/prophoto-issues/issues/509)

### 6.0.0-beta55

Enhancements & bugfixes (5/4/16)

* *Enhancement:* show blocks/rows/columns inheritance, and force un-locking of actions that break inheritance
* *Enhancement:* allow disabling of gallery play/pause control button [#498](https://github.com/netrivet/prophoto-issues/issues/498)
* fix column inheritance bug when dragging widget between rows in non-base template [#507](https://github.com/netrivet/prophoto-issues/issues/507)
* prevent PHP timeout on long-running design copy/import requests [#506](https://github.com/netrivet/prophoto-issues/issues/506)
* prevent tile rendering problems if user inputs invalid custom css or sass [#505](https://github.com/netrivet/prophoto-issues/issues/505)
* prevent P6 text widget from stripping `<style>` tags [#500](https://github.com/netrivet/prophoto-issues/issues/500)
* fix incorrect placement of gallery control bar in a certain combination of settings [#497](https://github.com/netrivet/prophoto-issues/issues/497)
* fix gallery control button shadow not rendering transparent [#499](https://github.com/netrivet/prophoto-issues/issues/499)
* fix incorrectly positioned tile layers in IE10+ when layers larger than tile [#493](https://github.com/netrivet/prophoto-issues/issues/493)
* fix rare bug from non-standard PHP `arg_separator.output` value [#504](https://github.com/netrivet/prophoto-issues/issues/504)
* fix inability to add WordPress comments when Facebook commenting enabled [#396](https://github.com/netrivet/prophoto-issues/issues/396)
* fix single-column grids not obeying gutter value [#496](https://github.com/netrivet/prophoto-issues/issues/496)
* fix inheritance bug in copied sibling templates [#492](https://github.com/netrivet/prophoto-issues/issues/492)
* fix row backgrounds not correctly overlaying background galleries [#495](https://github.com/netrivet/prophoto-issues/issues/495)
* fix invisible blocks and columns when dragging to reorder (Chrome 50+ only)

### 6.0.0-beta54

New free designs, enhancements, & bugfixes (4/27/16)

* **Add 4 new free designs** including [Morgan](https://www.prophoto.com/store/morgan/) from [The Design Space](http://thedesignspace.co/), [Sunny](https://www.prophoto.com/store/sunny) and [Square](https://www.prophoto.com/store/square/) from [La Lune Creative](http://www.lalunecreative.com/) [#349](https://github.com/netrivet/prophoto-issues/issues/349)
* *Enhancement:* fine-grained font-style assignments for widget html tags [#200](https://github.com/netrivet/prophoto-issues/issues/200)
* *Enhancement:* clearly show when changing customization settings will break parent template inheritance
* fix bug importing P5 menus [#491](https://github.com/netrivet/prophoto-issues/issues/491)
* fix horizontal clipping of horizontal menus in certain circumstances [#489](https://github.com/netrivet/prophoto-issues/issues/489)
* improve error feedback for design asset download permission problems


### 6.0.0-beta53

Enhancements & bugfixes (4/22/16)

* *Enhancement:* Display information about how many templates are sharing a widget
* *Enhancement:* Allow for setting color overrides for font layer hover states in tiles
* *Enhancement:* Improve number inputs in tile editor, easier negative value, and keyboard arrow controls [#460](https://github.com/netrivet/prophoto-issues/issues/460)
* fix problems in tiles when empty x or y values [#479](https://github.com/netrivet/prophoto-issues/issues/479)
* fix very large tiles overlapping tile editor sidebar [#478](https://github.com/netrivet/prophoto-issues/issues/478)

### 6.0.0-beta52

Bugfixes (4/21/16)

* fix bug that could cause unexpected red colors in random places [#488](https://github.com/netrivet/prophoto-issues/issues/488)
* fix dropdown menu items falling behind tiles [#486](https://github.com/netrivet/prophoto-issues/issues/486)
* fix paid design upload failures on 32-bit systems [#485](https://github.com/netrivet/prophoto-issues/issues/485)
* fix Pages menu item incorrectly limited to 5 items [#487](https://github.com/netrivet/prophoto-issues/issues/487)

### 6.0.0-beta51

Features & bugfixes (4/20/16)

* **New feature:** New gallery controls (including play/pause) and lots more customization options [#339](https://github.com/netrivet/prophoto-issues/issues/339)
* *Enhancement:* persist paid designs as json manifests (prepares the way for included free designs & more)
* *Enhancement:* convert *Crafted* free design logo to *tile*
* fix post header centering in browsers that need flexbox vendor prefixes [#481](https://github.com/netrivet/prophoto-issues/issues/481)
* fix customizer error panel always visible at narrow screen widths [#473](https://github.com/netrivet/prophoto-issues/issues/473)
* fix tile transitions in old versions of Safari [#480](https://github.com/netrivet/prophoto-issues/issues/480)
* prevent fatal error if plugin widget data missing [#477](https://github.com/netrivet/prophoto-issues/issues/477)
* prevent incorrect failure reports for auto-updates in non-english WordPress installs [#476](https://github.com/netrivet/prophoto-issues/issues/476)
* fix pages dropdown rendering pages in reverse order [#472](https://github.com/netrivet/prophoto-issues/issues/472)

### 6.0.0-beta50

Bugfixes, mostly from WordPress 4.5 update (4/13/16)

* Fix bug causing errors adding new layout entities in customizer for WordPress 4.5 [#468](https://github.com/netrivet/prophoto-issues/issues/468)
* Fix bug causing new widgets to not save in WordPress 4.5 [#468](https://github.com/netrivet/prophoto-issues/issues/468)
* Fix bug causing *rollover* style grids to not render in WordPress 4.5 [#471](https://github.com/netrivet/prophoto-issues/issues/471)
* Fix fatal error from `TileQueryInterface` on only extremely outdated builds of PHP 5.3 [#469](https://github.com/netrivet/prophoto-issues/issues/569)
* Fix bug causing grid excerpts post limit to apply on non-excerpt pages [#467](https://github.com/netrivet/prophoto-issues/issues/467)

### 6.0.0-beta49

Enhancement & bugfixes (4/12/16)

* *Enhancement:* Allow deleting of paid starter designs [#433](https://github.com/netrivet/prophoto-issues/issues/433)
* Fix bug that caused graphic widget images to display too small at certain breakpoints in some browsers [#466](https://github.com/netrivet/prophoto-issues/issues/466)
* Fix bug causing graphic widget images to overlay modal tile selector [#442](https://github.com/netrivet/prophoto-issues/issues/442)
* Fix bug causing newly created tiles to disappear temporarily when switching customizer screens [#461](https://github.com/netrivet/prophoto-issues/issues/461)
* Fix bug causing design thumb not to be imported for remote S3 design bundles

### 6.0.0-beta48

Features, enhancements & bugfixes (4/11/16)

* **New feature:** Support importing designs with assets on Amazon S3
* Increased max slider sizes for widget spacing controls
* Added basic error messaging for ProPhoto and WordPress errors in customizer [#189](https://github.com/netrivet/prophoto-issues/issues/189)
* Improve usability of horizontal dropdown menus on touch devices [#444](https://github.com/netrivet/prophoto-issues/issues/444)
* Add unlink button to ProPhoto text widget [#457](https://github.com/netrivet/prophoto-issues/issues/457)
* Fix bug causing Safari to size background galleries incorrectly under certain circumstances [#451](https://github.com/netrivet/prophoto-issues/issues/451)
* Fix iOS image longpress to save not disabled when image protection turned on [#454](https://github.com/netrivet/prophoto-issues/issues/454)
* Fix bug causing menu items not to save when data exceeded database limit [#452](https://github.com/netrivet/prophoto-issues/issues/452)
* Prevent PHP warning from getting image size of non-existent image [#441](https://github.com/netrivet/prophoto-issues/issues/441)

### 6.0.0-beta47

Enhancements & bugfixes (4/5/16)

* Increase max amounts for widget spacing controls
* Add retina image support for tiles
* Add button to remove tile from graphic widget
* Avoid unexpected css transitions in tiles
* Prevent PHP warnings for missing images [#441](https://github.com/netrivet/prophoto-issues/issues/441)
* Prevent caching of dynamic template css [#450](https://github.com/netrivet/prophoto-issues/issues/450)
* Ensure Pages menu item honors WordPress page order [#448](https://github.com/netrivet/prophoto-issues/issues/448)
* Workaround rare problems auto-updating due to SSL incompatibilities [#445](https://github.com/netrivet/prophoto-issues/issues/445)
* Fix widget alignment affecting horizontal menu dropdown text alignment [#419](https://github.com/netrivet/prophoto-issues/issues/419)
* Fix bug causing comment reply font style to not be applied [#428](https://github.com/netrivet/prophoto-issues/issues/428)
* Fix settings-area modal tutorials showing duplicate content [#425](https://github.com/netrivet/prophoto-issues/issues/425)

### 6.0.0-beta46

Tiles, plugin widgets, and more (3/31/16)

* **New feature:** Tiles (responsive buttons) [#221](https://github.com/netrivet/prophoto-issues/issues/221)
* **New feature:** Support plugin widgets [#228](https://github.com/netrivet/prophoto-issues/issues/228)
* **New feature:** Control at what breakpoint row columns all stack [#328](https://github.com/netrivet/prophoto-issues/issues/328)
* *Enhancement:* Set default gallery style for gallery pages in customizer [#413](https://github.com/netrivet/prophoto-issues/issues/413)
* Fix bug causing problems uploading design zips on PCs [#426](https://github.com/netrivet/prophoto-issues/issues/426)
* Fix PHP errors and warnings for menu items pointing to non-existent posts/categories [#437](https://github.com/netrivet/prophoto-issues/issues/437) [#440](https://github.com/netrivet/prophoto-issues/issues/440)
* Fix font style selector falling behind uploaded image in customizer [#434](https://github.com/netrivet/prophoto-issues/issues/434)
* Fix horizontal dropdown menus falling behind *Crafted* logo [#435](https://github.com/netrivet/prophoto-issues/issues/435)
* Report server environment details for analysis
* Prevent lowering of of `max_upload_filesize` and `post_max_size`
* Increase font style max font size to `250px`

### 6.0.0-beta45

Enhancements & bugfix (3/18/16)

* Separate paid add-on design attribution link with pipe
* Add bluehost.com rebate checkbox to registration modal
* Fix bug causing copied sibling templates to be connected to source [#422](https://github.com/netrivet/prophoto-issues/issues/422)

### 6.0.0-beta44

Enhancements & bugfixes (3/17/16)

* Improved error messaging for design zip upload failures [#416](https://github.com/netrivet/prophoto-issues/issues/416)
* Allow translation of non-translatable category and tag text [#417](https://github.com/netrivet/prophoto-issues/issues/417)
* Fix vertical menu top/bottom padding not applying [#414](https://github.com/netrivet/prophoto-issues/issues/414)
* Fix bug causing rest of post not to render if embedded gallery is first [#420](https://github.com/netrivet/prophoto-issues/issues/420)
* Discourage deleting of inactive widgets that might be in use by P6
* Prevent fatal errors when widgets in use by P6 deleted
* Fix bug causing crafted default rows and columns to be inserted into existing designs on updates
* Fix poor rendering of `background-attachment: fixed` images on browsers that disable it

### 6.0.0-beta43

Bugfix (3/14/16)

* Fix bug causing missing menus and errors during design export

### 6.0.0-beta42

Features & bugfixes (3/14/16)

* *New feature:* Copy templates at same level (siblings) [#269](https://github.com/netrivet/prophoto-issues/issues/269)
* *New feature:* Display designer attribution links
* *Enhancement:* Remove NetRivet attribution link and shorten some ProPhoto link text
* *Enhancement:* Improve readability of inherited template css display
* Fix bug that could strip html out of posts/pages [#411](https://github.com/netrivet/prophoto-issues/issues/411)
* Fix broken import of mobile menu assignment [#409](https://github.com/netrivet/prophoto-issues/issues/409)
* Fix broken grid editing on posts/page for hosts that don't support PUT/DELETE [#405](https://github.com/netrivet/prophoto-issues/issues/405)
* Fix PHP notice on export when no menu widgets [#408](https://github.com/netrivet/prophoto-issues/issues/408)
* Fix gallery grids not rendering in correct order [#394](https://github.com/netrivet/prophoto-issues/issues/394)
* Fix grid content mixup when multiple post-type grids on page [#407](https://github.com/netrivet/prophoto-issues/issues/407)
* Fix inability to turn comment submit button bg to transparent [#412](https://github.com/netrivet/prophoto-issues/issues/412)
* Fix Facebook page widget not responding to certain customizations [#406](https://github.com/netrivet/prophoto-issues/issues/406)

#### 6.0.0-beta41

Features & bugfixes (3/10/16)

* **New feature:** copy designs in "Manage Designs" screen
* **New feature:** create new designs from "Crafted" free starter
* **New feature:** support design store paid designs as design patterns
* Fix bug causing compatibility problems with NextGen Gallery plugin [#335](https://github.com/netrivet/prophoto-issues/issues/335)
* Fix bug that could cause improper display of international characters on certain setups [#398](https://github.com/netrivet/prophoto-issues/issues/398)
* Fix ProPhoto text widget converting absolute urls to relative [#372](https://github.com/netrivet/prophoto-issues/issues/372)
* Fix gallery background cover behavior sizing problem in Firefox [#397](https://github.com/netrivet/prophoto-issues/issues/397)
* Fix invalid css being generated by certain breakpoint settings [#382](https://github.com/netrivet/prophoto-issues/issues/382)
* Fix grid initialization spinner alignment [#400](https://github.com/netrivet/prophoto-issues/issues/400)
* Fix page content area background image not applying [#401](https://github.com/netrivet/prophoto-issues/issues/401)
* Fix custom sass producing harmless but invalid css [#399](https://github.com/netrivet/prophoto-issues/issues/399)

#### 6.0.0-beta40

Enhancements & bugfixes (3/7/16)

* **New feature:** Customizer admin widget labels [#332](https://github.com/netrivet/prophoto-issues/issues/332)
* *Enhancement:* move menus into design, always export mobile menus
* *Enhancement:* allow larger grid border radius to support circular grid images
* *Enhancement:* menu widgets get unique icon in customizer
* Fix post excerpt spacing problem in IE11 [#392](https://github.com/netrivet/prophoto-issues/issues/392)
* Fix incorrect first position of tooltips [#390](https://github.com/netrivet/prophoto-issues/issues/390)
* Fix comment input initial rendering in Firefox [#385](https://github.com/netrivet/prophoto-issues/issues/385)

#### 6.0.0-beta39

Enhancements & bugfixes (3/3/16)

* **New feature:** galleries used in design (widgets or block background) now export/import with design
* *Enhancement:* grid types that can't be imported now replaced with detailed instructional placeholder text widget
* Fix problems with gallery selection in widgets and block customizations [#388](https://github.com/netrivet/prophoto-issues/issues/388)
* Fix background galleries not displaying in certain circumstances [#389](https://github.com/netrivet/prophoto-issues/issues/389)
* Fix incorrect breaking of words on certain devices [#387](https://github.com/netrivet/prophoto-issues/issues/387)
* Fix `null` display of empty template description
* Remove site settings controls for non-working features [#386](https://github.com/netrivet/prophoto-issues/issues/386), [#331](https://github.com/netrivet/prophoto-issues/issues/331)
* Mostly fix difficulty in clicking far-right pencil icons [#374](https://github.com/netrivet/prophoto-issues/issues/374)
* Fixed a bug importing designs on PHP 5.3 only

#### 6.0.0-beta38

Enhancements and bugfixes (3/1/16)

* *Enhancement:* [Scoped custom sass](https://gist.github.com/jaredh159/e92273c0ba4117101e46) for blocks/rows/columns [#324](https://github.com/netrivet/prophoto-issues/issues/324)
* *Enhancement:* Support longer template descriptions with line breaks [#380](https://github.com/netrivet/prophoto-issues/issues/380)
* Fixed bug that could cause widgets to be mixed up on import
* Fixed bug that caused block customization modal to hang if no galleries [#379](https://github.com/netrivet/prophoto-issues/issues/379)
* Fixed bug that could break mobile layouts when really, really long words present [#383](https://github.com/netrivet/prophoto-issues/issues/383)

#### 6.0.0-beta37

Features, enhancements, & bugfixes (2/29/16)

* **New feature:** Background galleries
* **New feature:** Hide/show layout entities at specific breakpoints
* *Enhancement:* Gallery styles are now design level (can be exported with designs)
* *Enhancement:* Support pre-registration for installer plugin
* Fix gallery bug in Firefox where portrait images didn't work in landscape aspect ratios
* Fix widget alignment regression

#### 6.0.0-beta36

Bufix (2/25/16)

* Fix fatal error in Customizer affecting only certain combinations of PHP/libxml [#373](https://github.com/netrivet/prophoto-issues/issues/373)

#### 6.0.0-beta35

Features, enhancements, & bugfixes (2/25/16)

* **New feature:** Control widget visibility at responsive breakpoints [#321](https://github.com/netrivet/prophoto-issues/issues/321) (this [changes behavior slightly](https://gist.github.com/jaredh159/4c117a1cf7052e62a6d9))
* **New feature:** Permit constraining widget images to 1/2 width for better display of small images on retina devices [#326](https://github.com/netrivet/prophoto-issues/issues/326)
* *Enhancement:* expose control for customizing gallery transition (slide/fade) speed [#330](https://github.com/netrivet/prophoto-issues/issues/330)
* *Enhancement:* Vertically center gallery images [#346](https://github.com/netrivet/prophoto-issues/issues/346)
* Hide P6 help widget and link for non-admin users [#369](https://github.com/netrivet/prophoto-issues/issues/369)
* Fix image widget column spacing in IE [#366](https://github.com/netrivet/prophoto-issues/issues/366)
* Fix comments count horizontal alignment not taking effect [#368](https://github.com/netrivet/prophoto-issues/issues/368)
* Fix problem with column top-padding in Firefox [#358](https://github.com/netrivet/prophoto-issues/issues/358)
* Fix problem that could cause template creation to produce corrupt data [#370](https://github.com/netrivet/prophoto-issues/issues/370)
* Try to prevent possibility of downloading cached design export zips
* Fix bug that in rare circumstances could cause template css to have no effect

#### 6.0.0-beta34

Bugfix & enhancement (2/24/16)

* Fixed bug where rows were occasionally created without columns
* Prepping for special design store export process

#### 6.0.0-beta33

Bugfixes & enhancements (2/23/16)

* Base template name/description now editable
* Yoast SEO is detected as active SEO plugin, disabling our SEO options
* Added font controls for comment date/time display
* Fixed problem importing designs that could cause lots of widget problems
* Fixed problem caused by trying to render inherited state of deleted font-style
* Fixed bug with rendering custom uploaded fonts whose name begins with digit
* Fixed bug cuasing it to be impossible to pinch to zoom/scale on touch devices

#### 6.0.0-beta32

Bugfixes (2/20/16)

* Fix a bug that caused `.woff` custom font uploads to fail on windows machines
* Clarify language for individual post/page background area
* Ensure uploaded custom fonts present in exported design zips

#### 6.0.0-beta31

Custom font uploads & bugfixes (2/19/16)

* **New feature:** upload custom font `.woff` files [#292](https://github.com/netrivet/prophoto-issues/issues/292)
* Enhancement: show exact viewport dimensions in tooltip explaining responsive breakpoints
* Fix bug that could cause fatal error with bad grid view data [#345](https://github.com/netrivet/prophoto-issues/issues/345)
* Prevent fatal error from super-janky invalid html in WordPress posts [#343](https://github.com/netrivet/prophoto-issues/issues/343)
* Guard against templates with customizations data integrity issues [#341](https://github.com/netrivet/prophoto-issues/issues/341)
* Fix bug causing some font-styles to not apply where assigned [#340](https://github.com/netrivet/prophoto-issues/issues/340)
* Support extra items in design exports meant for design store

#### 6.0.0-beta30

Bugfixes & enhancements (2/18/16)

* Render embedded P4/5 galleries with main gallery style [#338](https://github.com/netrivet/prophoto-issues/issues/338)
* Prevent fatal error if incomplete image dimensions data [#337](https://github.com/netrivet/prophoto-issues/issues/337)
* Add diagnostic tools for recovering from bad data states

#### 6.0.0-beta29

Gallery thumbnails & bugfixes (2/17/16)

* **New feature:** Gallery thumbstrip thumbnail navigation
* Fix bug causing certain widget and content images to load slowly
* Fix bug in galleries where slides could be temporarily out of order
* Fix bug in galleries that could slow loading speed and performance
* Fix bug causing left-aligned text widgets to align incorrectly when column aligned
* Prevent WordPress from lowering memory limit for admin requests

#### 6.0.0-beta28

Enhancements & bugfixes (2/12/16)

* Enhancement: shortcodes now supported in ProPhoto text widget
* Fix bug causing inheriting text input areas to not be editable
* Fix bug causing small gallery arrows to be vertically aligned incorrectly
* Fix bug causing imported galleries to have no assigned style
* Fix bug that could cause P5 gallery imports to fail

#### 6.0.0-beta27

Features, enhancements, & bugfixes (2/11/16)

* **New feature: Gallery dot navigation**
* **New feature: Add tooltip help in customizer**
* *Enhancement:* Significantly improve gallery initialization appearance
* *Enhancement:* Allow for re-importing of failed or new P5 galleries
* *Enhancement:* Allow for importing of P4 galleries
* Fix gallery custom post pages not displaying gallery title
* Fix PHP warning on post/page save
* Fix bug with responsive settings overriding non-responsive settings incorrectly
* Fix bug with gallery arrow sizes being overridden by entity font styles
* Fix display of gallery fullscreen button when fullscreen not supported
* Fix bug causing watermarking of images to be inconsistent
* Fix bug that prevented site settings comments disable to not save
* Fix bug that could cause grid thumbs to be missing only in admin
* Prevent Yoast SEO plugin metabox from dominating the universe
* Remove lightbox gallery functionality ([click here for more explanation](https://gist.github.com/jaredh159/7a16bf5ef99de2a8e9c5))

#### 6.0.0-beta26

Bugfixes (2/8/16)

* Prevent fatal errors for older builds with [apc cache bug](https://bugs.php.net/bug.php?id=52144)
* Use fullpaths for theme required files to prevent rare issues with PHP included paths
* Fix grid excerpts showing or being broken by plugin shortcodes

#### 6.0.0-beta25

Bugfix (2/5/16)

* Fix for auto-update process not running on customizer screen

#### 6.0.0-beta24

Enhancements & bugfixes (2/4/16)

* Moved copyright and archive-type title font styles into Background and Content > Post Header areas, respectively
* Fixed bug where widget body text font style was not applying to `<li>` text
* Fixed block deleting bug introduced in beta 23
* More enhancements/fixes to ordering blocks, rows, and columns
* Fixed admin title alignment bug that was caused by admin notices

#### 6.0.0-beta23

Enhancements & bugfixes (2/3/16)

* *Enhancement*: add image theft protection prevention of left-click to image source
* *Enhancement*: add customization controls to gallery icons
* Improved reliability and usability of block/row/column reordering in customizer
* Fixed a bug that could cause changes to save to wrong template just after switching templates
* Fixed excerpts not showing where designated
* Fixed an error in deleting designs
* Restored help-widget to customizer screen


#### 6.0.0-beta22

Enhancements & bugfixes (2/1/16)

* *Enhancement*: hide post/page title and/or all content with metabox in edit screen
* *Enhancement*: add font style control for a few areas missing control
* *Enhancement*: font styles now allow line-height control
* *Enhancement*: gallery background color customization
* *Enhancement*: galleries now support featured images, which are used by grids
* *Enhancement*: added some diagnostic tools for troubleshooting errors & bad data
* Fixed a bug that caused warnings for malformed html urls
* Fixed gallery permalink pages intermittently being not found
* Fixed a bug that caused assigned static home page template to not correctly apply
* Prevented plugin conflicts in customizer
* Fixed a bug that could cause templates to not delete
* Fixed a bug that could cause malformed HTML in various places

#### 6.0.0-beta21

New feature, bugfixes, and enhancements (1/28/16)

* **Fullscreen Galleries** - galleries can enable fullscreen support via gallery customizations
* Fixed bug where a user could get stuck in "Let me customize" loop
* Fixed a bug where WordPress would give a 200 OK for requests with errors
* Fixed a bug where Safari incorrectly wrapped columns onto a new line
* Disables "pause on hover" functionality of galleries
* Fixed usability issue with showing template used for "static front" and "blog posts page"
* Fixed a bug where gallery images were being rendered twice
* Fixed display of text in registration/activation modal

#### 6.0.0-beta20

Bugfixes (1/27/16)

* Fix a bug that caused mobile menu to not be seen
* Fixed a bug that could cause columns to not line up side by side when they should
* Fixed site settings in footer area not updating when links removed
* Fixed widget title space below not working when applied at "Site" level

#### 6.0.0-beta19

Bugfix and admin help links (1/26/16)

* Add help link from customizer to [P6 beta documentation](https://www.prophoto.com/beta/prophoto6)
* Add help link from non-customizer admin pages to [P6 beta documentation](https://www.prophoto.com/beta/prophoto6)
* Fix bug for *private*-beta users getting missing menus and customizer white-screen

#### 6.0.0-beta18

Public beta release (1/26/16)

* Initialize with Crafted as included json file instead of migration
* Flatten migrations for public beta launch
* Fix widget import/export when importing/exporting designs
* Fix generic classnames from composer classmap causing interference with plugins


#### 6.0.0-beta17

Importing, features, enhancements and bugfixes (1/25/16)

* **P6 now imports P5 menus, galleries, and grids**
* **Added several widget spacing and alignment options**
* Added search and RSS new menu item types
* Kitty screenshot replaced with new P6 public beta screenshot (thanks Matt Hudson!)
* Prevent simultaneous customizer sessions for data integrity
* Display the number of comments on site front
* Restore comments hide/show functionality
* Convert all `PATCH` requests to `POST` for janky hosts that don't like HTTP verbs
* Default menu customizer to menu most recently updated
* Fixed site custom css not added to template css
* Fixed non-working footer link removal
* Fixed fatal error from default bootstrapped categories menu item
* Fixed page templates not taking effect when set for an individual page
* Fixed font-style editor rendering issues in IE11
* Prevent seeing through to mobile menu background color when site background colors removed
* Fixed a number of menu ordering and re-ordering issues
* Fixed category menu item not using custom title
* Fixed centered post titles not centering at small screen sizes
* Fixed hitting enter when editing design title results in white screen
* Fixed problems with site sizing when content exceeds vheight=1== block
* Fixed fatal errors when no watermark image uploaded
* Fixed save buttons not disabling after successful save
* Fixed saved grids attempting to display trashed galleries
* Prevent non-admin viewing of unregistered sites


#### 6.0.0-beta16

Enhancements and bugfixes (1/19/16)

* Extend responsive customizations to blocks, rows, and columns
* Remove `PDO` server requirement by creating a `$wpdb` Phinx adapter
* Added template and block classes for easy custom CSS targeting
* Fixed bug causing gallery style customizations to not save correctly
* Fixed bug with background-size = cover not applying when set at Site level
* Fixed janky alignment of customizer radio buttons and checkboxes
* Fixed post titles not centering at small screen sizes
* Fixed issues with block content overflowing block due to `vheight`
* Fixed problem with default categories menu item causing modal white screen
* Fixed `pp/uploads/images/null` errors from generated css
* Fixed problems changing gallery style for gallery custom post pages
* Fixed incorrect application of space below posts
* Prevent fatal errors when no watermark image uploaded
* Fixed non-working horizontal menu dropdown opacity setting
* Fixed white-screen when pressing enter from edit design meta title


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
