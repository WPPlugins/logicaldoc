=== LogicalDOC WordPress Explorer ===
Contributors: shakilodem
Donate link: http://www.logicaldoc.com/
Tags: logicaldoc, document management, system, software, integration, tool, dms
Requires at least: 4.2.7
Tested up to: 4.7
Stable tag: 1.0.3
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

LogicalDOC WordPress Explorer realizes the integration between LogicalDOC DMS and WordPress

== Description ==

LogicalDOC is a document management software that is designed to handle and share documents within an organization. This plugin allows you to expose in a controlled way a portion of the document repository in WordPress, allowing folder browsing, document downloading and full-text search. 

Features:
* Ability to connect to whatever local or remote LogicalDOC instance
* Display LogicalDOC's document table in Posts or Pages
* Browse the content of folders with breadcrumb facility
* Sort by different metadata
* Perform full-text searches
* Download documents
* Ability to password protect access to a specific resource
* Option to expose a restricted section of the document repository starting from a specific node (Folder ID)
* Customizable columns set
* Possibility of real-time filter the contents of a folder or a search


== Installation ==

1. This plugin requires that the PHP option short_open_tag be enabled (On)
2. Upload the plugin files to the `/wp-content/plugins/logicaldoc` directory, or install the plugin through the WordPress plugins screen directly.
3. Activate the plugin through the 'Plugins' screen in WordPress
4. Click on the new menu item "LogicalDOC" and create your first LogicalDOC's connection setting!
5. Now you can embed the LogicalDOC view in your post or in a page simply by placing the referral to the configuration eg. [logicalDoc id="37"] 


== Frequently Asked Questions ==

= This plugin works with LogicalDOC Community Edition? =

Yes, the plugin works with both LogicalDOC Community Edition (free) than with commercial editions of LogicalDOC

= Which version of LogicalDOC is compatible with this plugin? =

The plugin has been tested and developed with LogicalDOC 7.5.3

= Secure HTTPS works? =

Yes
                                                                                      

== Screenshots ==

1. Creating a new configuration (connection to LogicalDOC)

2. Listing configurations

3. Embed the configuration in a Page

4. Page display on the frontend 

5. Advanced Search form and results (frontend)


== Changelog ==

= 1.0.3 =
* Sanitized GET calls
* Fixed issue of lost sessions on the server caused by download requests

= 1.0.2 =
* Generic function (and/or define) names - fixed #02

= 1.0.1 =
* Generic function (and/or define) names - fixed
* Allowing Direct File Access to plugin files - fixed 
* Including jquery files (or calling them remotely) - fixed

= 1.0.0 =
* Initial release

== Upgrade Notice ==

= 1.0 =
Nothing to do, this is the initial release


