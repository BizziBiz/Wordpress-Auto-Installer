Wordpress Auto-Installer is a script for cPanel/WHM that will automate a Wordpress install and setup. This script works on the detection of a specific cPanel package, and once selected it will automatically install Drupal to that account.

Installation Instructions
===========================

1. Upload "postwwwacct" to your /scripts folder
2. Modify the postwwacct variables located at the top of the page
	You may need to make database specific tweaks if you do not use "localhost:3306".
	This is located under the "Create the database" section and "drush install" section
3. Create a cPanel package titled "wordpress_autoinstall". Alternatively you can change this in postwwwacct


Usage Instructions
===========================
To setup wordpress accounts all you need to do is select the "wordpress_autoinstall" package when creating a new account with cPanel. 