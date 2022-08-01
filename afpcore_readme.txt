=== Auto Funnel Press ===
Contributors: none
Requires at least: 5.3
Tested up to: 6.0.1
Stable tag: 2.0.39
Requires PHP: 5.6.40
License: Commercial & GPLv2
License URI: https://www.gnu.org/licenses/gpl-2.0.html

Automated Funnel System to facilitate capture and management of users and affiliate systems.

== Description ==

Automated Funnel System to facilitate capture and management of users and affiliate systems.

== Installation ==

1. Upload the plugin files to the '/wp-content/plugins/afp_core' directory, or install the plugin through the WordPress plugins screen directly.
2. Activate the plugin through the 'Plugins' screen in WordPress.
3. Use the AFP Settings->AFP License screen to activate your license before being able to configure AFPv2.
4. Use the AFP Settings->AFP Settings screen to configure the system options.

== Frequently Asked Questions ==

= A list of frequently asked questions can be found on the official website. =

[AFPv2 FAQ](https://autofunnelpress.com/faq/ "Auto Funnel Press - FAQ")

== Screenshots ==

== Changelog ==

= 2.0.39 =
* Added AFP Network Landing Input shortcode

= 2.0.38 =
* Added AFP Network Input shortcode
* Updated AFP Updater
* Updated AFP License System
* Upgrade internal fields library

= 2.0.37 =
* Updated AFP Blocks to new WordPress editor standards
* Updated admin notices to be more dynamic for system states
* Added Nested Block functionality for both Confirmation states
* Fixed issue with orphaned user relationship data
* Upgrade internal fields library
* Upgrade internal Stripe library
* Upgrade internal Authorize.net library
* Upgrade AFP update mechanism
* Deprecated several functions in favor of new standards
* Deprecated Confirmation block
* Various fixes and code adjustments

= 2.0.36 =
* Added registration restrictions
* Added minimal registration option
* Upgrade internal fields library

= 2.0.35 =
* Fixed issue with network landing link processing referring id links

= 2.0.34 =
* Added shortcode for landing page network link
* Upgrade internal fields library

= 2.0.33 =
* Added adjustments for Dynamics Update
* Updated cookie capture fallback
* Upgrade internal fields library

= 2.0.32 =
* Fixed issue with certain network group outputs

= 2.0.31 =
* Added dynamic messaging for different admin interactions
* Modified the field sanitation for network blocks so url parameters would correctly pass
* Fixed issue where user could create a redirect loop on homepage
* Fixed an output ID duplication which could cause problems with multiple form blocks on a page
* Upgrade internal fields library

= 2.0.30 =
* Fixed compatibility issue with WordPress 5.5 Release
* Upgrade internal fields library

= 2.0.29 =
* Add support for AFP Dynamics extension

= 2.0.28 =
* Upgrade internal fields library
* Fixed issue with some configurations that could cause confirmation emails to have duplicate headers

= 2.0.27 =
* Added CSV download option to Child User Block

= 2.0.26 =
* Upgrade internal fields library
* Fixed an issue with promotion link redirection on dynamic variable changes

= 2.0.25 =
* Fixed an issue with url scheme shifts on certain redirections with Reading Settings defined

= 2.0.24 =
* Added validation for login page selection to prevent page id conflicts
* Added a new layout option for Network Block
* Added a reset field option for Network Block
* Added a Test Link option for Network Block
* Added option to not redirect to dashboard for logged in users
* Updated instructional messaging to be more clear on certain AFP Settings
* Fixed issue with email replacement shortcodes not working correctly on some email types
* Fixed issue with Network Link shifts when re-ordering the position in admin

= 2.0.23 =
* Added option to define a custom login page
* Added User Login block with password reset option
* Removed No Front landing option because of non-workable conflicts with promotion link redirection
* Fixed issue with Capture on Registration Secondary Admin List capture

= 2.0.22 =
* Updated outgoing email execution to try and prevent possible double sends
* Added option to set Network Block links to open in new window

= 2.0.21 =
* Updated Logging details to provide better output information for various AR selections
* Fixed issue with AWeber list conflict for other AR list data when multiple AR info is saved in the system
* Secured loophole on promotion link variable anomalies

= 2.0.20 =
* Updated options for Pre-Capture Survey
* Added validation option for custom profile fields to fix saving issue
* Fixed referral email default message

= 2.0.19 =
* Upgrade internal fields library
* Added option to enable customizing the landing page urls
* Added option to customize promotion link output
* Added pre-capture survey option
* Added referral notice email option

= 2.0.18 =
* Update core files to be ready for AFPv2 Theme and Dynamics Extension

= 2.0.17 =
* Updated Network Access Restriction with the same Network Retrieval methods employed in previous update
* Fixed a critical issue on Default Admin for Network Access Restriction

= 2.0.16 =
* Added User relationship management option for Admins
* Fixed a conflict with GetResponse and Sendshark List IDs

= 2.0.15 =
* Upgrade internal fields library
* Added CSS style for dynamic profile view
* Added option to hide block from public profile view
* Updated blocks for public profile view to be more consistent
* Updated style fall-back on certain flex block fields
* Fixed issue that sometimes could happen where referred user wasn't mapped to default admin if no query_var could be found
* Fixed issue that sometimes could happen for parent profile on unmapped or invalid user relationships

= 2.0.14 =
* Fixed critical issue due to internal system file not updated to latest

= 2.0.13 =
* Created a conditional fallback for certain network user data
* Fixed issue with Avatar block for Admin users
* Fixed integration anomaly for Zapier fields

= 2.0.12 =
* Added User Avatar block
* Added Password Update block
* Added Top 10 User block

= 2.0.11 =
* Changed profile page restrictions on certain user blocks (Referred User List, AutoResponder Setup)
* Fixed conflict with Sendshark List and AWeber List selection

= 2.0.10 =
* Upgrade AFP AWeber List DB
* Changed AWeber list association
* Fixed issue with Landing Group defaults
* Deprecated AWeber List ID Field

= 2.0.9 =
* Added Capture and Mail logging for support assistance
* Added option to disable Welcome Email
* Updated welcome email with conditional meta value

= 2.0.8 =
* Added Zapier Extension support
* Added User Parent block
* Update user parent shortcodes
* Update settings page support info
* Update Stripe library integration with condition to resolve duplicate errors
* Fixed issue with manual user confirmation settings
* Fixed AWeber integration output

= 2.0.7 =
* Changed conditional display for extended member profile blocks
* Fixed issue with some pre-defined conditions for certain AFPv2 System configurations
* Resolved PHP Warning

= 2.0.6 =
* Added some helpful notices for activating AFP Extensions
* Fixed issue with Elementor associated Registration widget with custom field settings

= 2.0.5 =
* Added Dynamic Member Profile Options
* Added Dynamic Profile features with System Registration
* Added Additional Capture Page Options
* Fixed issue with some conditional system configurations

= 2.0.4 =
* Fixed an issue with GetResponse capture output

= 2.0.3 =
* Updated transmission operations
* Added additional notes and information to the admin for various AFPv2 settings.
* Fixed issue with visual selection for Sendshark Campaigns
* Fixed some additional notices for PHP 7.3 Compatibility
* Fixed some changes for WordPress 5.3

= 2.0.2 =
* Update settings page information for Shortcodes
* Update license settings for extensions
* Update internal Library for WordPress 5.3
* Update Core for Extension Release
* Added additional capture fields for supporting services
* Fixed issue with User AutoResponder selection

= 2.0.1 =
* Fix issue with Stripe price calculation
* Update license connection url for SSLVerify
* Update license options for Managed AFPv2

= 2.0.0 =
* Auto Funnel Press Rebuild Release

== Upgrade Notice ==

= 2.0.24 =
This version fixes an issue where reordering items with Unique IDs would shift the outputs based on the order

= 2.0.15 =
This version fixes a potential critical issue for users with invalid / broken relationships and default fallback mapping

= 2.0.14 =
This version fixes a critical issue on a file that did not get updated from version tagging transition

= 2.0.11 =
This version fixes a selection conflict that happens between Sendshark selection and AWeber selection

= 2.0.10 =
This version creates a new DB upgrade to address certain AWeber account list ids.

= 2.0.6 =
This version fixes an issue with the AFP Elementor extension that breaks operation. Upgrade immediately.