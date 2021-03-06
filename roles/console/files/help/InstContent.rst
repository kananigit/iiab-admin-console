IIAB Admin Console - Install Content
====================================

The options on this menu allow you to download and install content onto Internet-in-a-Box.  As of this release all of this content comes from the internet, but in the future there will be menu options to copy from a portable hard disk drive.

These options are aimed at people who plan to set up the server in a location where there is a relatively high bandwidth connection and then deploy it where there is little or no connectivity.

Get ZIM Files from Kiwix
------------------------

### Overview

The words ZIM and Kiwix are probably unfamiliar, but the content is very familiar and highly desirable, including all or some of the following for more than 100 languages:

* Wikipedia
* Wiktionary
* TED Talks
* Project Gutenberg Books
* Wikibooks
* Wikiquote
* Wikinews
* Wikivoyage
* Others

Kiwix.org supplies a server that is installed on Internet-in-a-Box and also hosts all of this content.

### Do this First

Click on the button labelled **Refresh Kiwix Catalog** if you have not done so before or if it has been a month or more since you last did so.  This will retrieve the latest list of content hosted at Kiwix.org.

### How it works

When you Click on this menu option you will see a list of any content already installed, any in the process of being installed, and all content available in the languages selected.

To select more languages Click on the button labelled **Select Languages**.  You will see the six languages with the most speakers in the world.  Click **More Languages** for others.  Check the language you want and then click **Show Content** or the **x** in the top right of the screen.

Next **Check the Titles** you want to download.  You will see the total space available and the amount required for your selections.  Be aware that the download process can require approximately double this amount.

When you have made your selections click **Install Selected ZIMs**.  Jobs will be created on the server to download, unzip, and install the selected content.  These are large files and the download can take a long time.  Visit **Display Job Status** on the **Utilities** menu to see when they have completed or any problems encountered.  It is not necessary to keep the browser open during the download.

### Don't Forget

When each of the ZIM files has been downloaded and installed the Kiwix server will be restarted automatically. This can also be done manuall by clicking **Restart the Kiwix ZIM Server**.

Make sure that the **Kiwix** service is enabled under **Configure** - **Services Enabled**.

Get OER2GO(RACHEL) Modules
--------------------------

### Overview

Many people have heard of RACHEL as a source of Educational Content. The RACHEL repository is also known as OER2GO and contains modules accessible with a web server such as:

* CK-12
* English Storybooks
* Hesperian Health Guides
* Practical Action
* And Many Others

### Do this First

When you installed the Admin Console the latest version of the OER2Go catalog was downloaded. When you click this menu option the system will check to see if it is still less than a month old and will recommend downloading again if it is not.

To get the latest version Click on the button labelled **Refresh OER2GO Catalog**.

### How it works

When you Click on this menu option you will see a list of any content already installed, any in the process of being installed, and all content available in the languages selected.

To select more languages Click on the button labelled **Select Languages**.  You will see the six languages with the most speakers in the world.  Click **More Languages** for others.  Check the language you want and then click **Show Content** or the **x** in the top right of the screen.

Next **Check the Titles** you want to download.  You will see the total space available and the amount required for your selections.

When you have made your selections click **Install Selected Modules**.  Jobs will be created on the server to download and install the selected content.  These are large files and the download can take a long time.  Visit **Display Job Status** on the **Utilities** menu to see when they have completed or any problems encountered.  It is not necessary to keep the browser open during the download.

### Don't Forget

Downloaded Modules will appear on the server in a URL like /modules/Name of the Module. If you are using IIAB-Menu, there will already be a menu definition for most modules, but you may need to create your own. You may also need to add a reference to the module to your menu file.

Download Khan Academy Videos
----------------------------

### How it works

KA Lite from the Learning Equality Foundation is installed on Internet-in-a-Box for offline viewing of Khan Academy videos and exercises.  It has its own options to select language and download videos.  To access this functionality simply click **Launch KA Lite** and another tab will open where you can login and manage content.

### Don't Forget

Make sure that the **KA Lite** and **KA Downloader** services are enabled under **Configure** - **Services Enabled**.

Remove Content
--------------

Over time you may find that ZIM or OER2GO/RACHEL modules are no longer needed or in need of upgrade. So you may want to delete some of the ones that are install

In addition, when you install ZIM files or OER2GO/RACHEL modules you are downloading large files from the internet.  These are not removed in case there is a problem and the installed needs to be rerun.

After you are sure that everything has been installed successfully you can remove some or all of these files to free up space on the disk.

Here is how to verify that an item has been installed:

* Look at the installation page and ensure that the item is marked as installed.
* Look at the Server menu to see if the item is accessible and brings up content.

To remove a module or file check the corresponding box and click **Delete Checked Files**.

Actions
-------

**Restart the Kiwix ZIM Server** and **Refresh Kiwix Catalog** are covered above.

**Refresh ZIMs Installed** recalculates the amount of space used on the disk.
