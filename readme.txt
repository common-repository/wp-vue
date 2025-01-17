=== Wp Vue ===
Contributors: tristup
Donate link: http://www.tristupghosh.com/
Tags: WordPress, Vue, Shortcodes, VUE JS
Requires at least: 4.4
Requires PHP: 7.0
Tested up to: 5.2.2
Stable tag: 0.1.0
License: GPLv2 or later
License URI: https://www.gnu.org/licenses/gpl-2.0.html

== Description ==

WP Vue plugin will provide you the shortcode to show the Posts using the VUE JS. Page will shows as Single Page Application. 

== Major features in WP Vue include: ==

1. Shows the Posts using Vue-JS

2. Can limit the posts [ Else will take default value from Site Settings ]

3. Shows the Pagination

4. Single Page Appplication

5. Do Not reload the page.


== Shortcode & Attributes ==

#With all default values
[wp-vue-posts]

#With Post Per Page Option 
[wp-vue-posts posts_per_page="20"]

#With Offset Option 
[wp-vue-posts posts_per_page="20" offset="10"]

#With Order Option 
[wp-vue-posts posts_per_page="20" offset="10" order="desc"]
Order Options : "desc" for descending, "asc" for ascending

#With Order By Option 
[wp-vue-posts posts_per_page="20" offset="10" order="desc" orderby="date"]
Order By Options : "id" is deafult value, other valid values are "date", "relevance", "include", "title", and "slug"


== Installation ==
 
This section describes how to install the plugin and get it working.

1. Go to Wordpress Dashboard > Plugins > click on Installed plugins > look for add new at the top most of the screen and click here > Add Plugins > upload plugin > choose file -> click here and upload Simple Demo Importer plugin.

2. Activate Plugin through 'Plugins' menu in WordPress.

3. You can start using the Shortcode with all the possible attributes. Happy `Vuing`

== Files ==

1. wp-vue.php : File to start working on
2. wp-vue-template.php : Template file showing the value fetched using Vue
3. main.js : Main JavaScript file to create a fetch request to the Post API endpoint to get the posts. 


== Screenshots ==

1. Screenshot : Shortcode.

== Changelog == 

Intial Commit. 

== Upgrade Notice ==

No Upgrade Notice.
	
== Frequently Asked Questions ==

1. How to create a New Request? 

Answer : Need to create a method in main.js follwoing the VUE JS structure, and call into the template file. 


