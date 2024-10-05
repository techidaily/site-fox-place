---
title: How to Set Up Apps to Launch at Boot on Windows Desktops
date: 2024-10-03T19:14:38.901Z
updated: 2024-10-05T17:57:38.217Z
tags:
  - user-guide
categories:
  - advancedinstaller
description: This Article Describes How to Set Up Apps to Launch at Boot on Windows Desktops
thumbnail: https://thmb.techidaily.com/8f746ea5ff5f235bd9550c0631527dab7bc233469cd27f4e2765e160c088926b.jpg
---

## How to Set Up Apps to Launch at Boot on Windows Desktops

Table of Contents

* [Introduction](https://tools.techidaily.com/advancedinstaller/products/)
* [Registration](https://tools.techidaily.com/advancedinstaller/products/)
* [Using Advanced Installer](https://tools.techidaily.com/advancedinstaller/products/)
* [Features and Functionality](https://tools.techidaily.com/advancedinstaller/products/)  
   * [Changing Version](https://tools.techidaily.com/advancedinstaller/products/)  
   * [Upgrades](https://tools.techidaily.com/advancedinstaller/products/)  
   * [Synchronized Folders](https://tools.techidaily.com/advancedinstaller/products/)  
   * [File Hashes](https://tools.techidaily.com/advancedinstaller/products/)  
   * [Patches](https://tools.techidaily.com/advancedinstaller/products/)  
   * [Single Package Authoring](https://tools.techidaily.com/advancedinstaller/products/)  
   * [Single Instance Application](https://tools.techidaily.com/advancedinstaller/products/)  
   * [UAC](https://tools.techidaily.com/advancedinstaller/products/)")  
   * [Merge Modules](https://tools.techidaily.com/advancedinstaller/products/)  
   * [Prerequisite Repository](https://tools.techidaily.com/advancedinstaller/products/)  
   * [Native Java Launcher](https://tools.techidaily.com/advancedinstaller/products/)  
   * [Packaging a Java App for Deployment on a Mac OS X](https://tools.techidaily.com/advancedinstaller/products/)  
   * [Pack200 Compression](https://tools.techidaily.com/advancedinstaller/products/)  
   * [LZMA Compression](https://tools.techidaily.com/advancedinstaller/products/)  
   * [AES Encryption](https://tools.techidaily.com/advancedinstaller/products/)  
   * [Smart Edit Control](https://tools.techidaily.com/advancedinstaller/products/)  
   * [Smart Condition Edit Control](https://tools.techidaily.com/advancedinstaller/products/)  
   * [Package User Interface](https://tools.techidaily.com/advancedinstaller/products/)  
   * [Advanced Installer Updater](https://tools.techidaily.com/advancedinstaller/products/)  
   * [Internet Information Services](https://tools.techidaily.com/advancedinstaller/products/)  
   * [SQL Databases](https://tools.techidaily.com/advancedinstaller/products/)  
   * [Serial Validation](https://tools.techidaily.com/advancedinstaller/products/)  
   * [Best Practice](https://tools.techidaily.com/advancedinstaller/products/)  
   * [ISO 19770-2](https://tools.techidaily.com/advancedinstaller/products/)  
   * [Using the Table Editor](https://tools.techidaily.com/advancedinstaller/products/)  
   * [Pin Program to Start Menu Automatically in Windows (App Packaging)](https://www.advancedinstaller.com/user-guide/tiles-show-start.html "Pin Program to Start Menu Automatically in Windows (App Packaging)")
* [Tutorials](https://tools.techidaily.com/advancedinstaller/products/)
* [Samples](https://tools.techidaily.com/advancedinstaller/products/)
* [How-tos](https://tools.techidaily.com/advancedinstaller/products/)
* [FAQs](https://tools.techidaily.com/advancedinstaller/products/)
* [Windows Installer](https://tools.techidaily.com/advancedinstaller/products/)
* [Deployment Technologies](https://tools.techidaily.com/advancedinstaller/products/)
* [IT Pro](https://tools.techidaily.com/advancedinstaller/products/)
* [MSIX](https://tools.techidaily.com/advancedinstaller/products/)
* [Video Tutorials](https://tools.techidaily.com/advancedinstaller/products/)
* [Advanced Installer Blog](https://tools.techidaily.com/advancedinstaller/products/)
* [Table of Contents](https://tools.techidaily.com/advancedinstaller/products/)

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## Pin Program to Windows Start Menu

Microsoft strongly recommends against automatically showing tiles in the Start Menu from Windows as part of the installation. It should always be the user's choice. For this specific reason creating tiles for your application doesn't automatically make them visible in the Start Menu. Advanced Installer enforces asking the installing user for confirmation through the [**PINTOSTART** property](https://tools.techidaily.com/advancedinstaller/products/). 

After enabling [Show on Start](https://tools.techidaily.com/advancedinstaller/products/) option for your application in the [Tiles Page](https://tools.techidaily.com/advancedinstaller/products/), you also need to set the PINTOSTART property to IDYES as follows:

* From the [Dialog Editor page](https://tools.techidaily.com/advancedinstaller/products/) if you have Enterprise or Architect license edition
* By using a [Message Box custom action](https://tools.techidaily.com/advancedinstaller/products/) if you have Professional

The behavior will be:

| **PINTOSTART** not set  | All tiles defined in the Tiles Page will be visible only when users manually pin an application (EXE) or application's shortcut to the Start Menu (context menu -> Pin to Start), after the installation. |
| ----------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **PINTOSTART** \= IDYES | Same as above + tiles with "Show in Start" option enabled will be immediately visible after installation.                                                                                                 |

<!-- affiliate ads begin -->
<span id="1938141">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1938141.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1938141">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1938141.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1938141%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1938141/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Video tutorial

#### Did you find this page useful?

Please give it a rating:

 Thanks!

#### Report a problem on this page

Information is incorrect or missing

Information is unclear or confusing

Something else

#### Can you tell us what’s wrong?

Send message

<ins class="adsbygoogle"
     style="display:block"
     data-ad-format="autorelaxed"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="1223367746"></ins>

<ins class="adsbygoogle"
     style="display:block"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="8358498916"
     data-ad-format="auto"
     data-full-width-responsive="true"></ins>

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://article-posts.techidaily.com/new-2024-approved-ultimate-collection-10-excellent-photo-background-alternators/"><u>[New] 2024 Approved Ultimate Collection 10 Excellent Photo-Background Alternators</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-in-2024-historical-explorations-10-must-see-educational-channels-on-yt/"><u>[New] In 2024, Historical Explorations - 10 Must-See Educational Channels on YT</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-2024-approved-exporting-tweets-as-webmaac-audio/"><u>[Updated] 2024 Approved Exporting Tweets as WebM/AAC Audio</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-in-2024-bringing-your-instagram-aesthetic-to-life-with-square-videos-in-imovie/"><u>[Updated] In 2024, Bringing Your Instagram Aesthetic to Life with Square Videos in iMovie</u></a></li>
<li><a href="https://fox-place.techidaily.com/best-software-solutions-for-capturing-your-android-devices-display/"><u>Best Software Solutions for Capturing Your Android Device's Display</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/chaptered-cinema-on-vimeo-cutting-techniques-explained-for-2024/"><u>Chaptered Cinema on Vimeo Cutting Techniques Explained for 2024</u></a></li>
<li><a href="https://fox-place.techidaily.com/discover-stunning-destinations-remotely-top-virtual-tours-for-worldwide-adventures-at-home/"><u>Discover Stunning Destinations Remotely: Top Virtual Tours for Worldwide Adventures at Home</u></a></li>
<li><a href="https://fox-place.techidaily.com/effective-strategies-to-access-your-locked-iphone-without-a-password/"><u>Effective Strategies to Access Your Locked iPhone Without a Password</u></a></li>
<li><a href="https://fox-place.techidaily.com/expert-tips-and-tricks-for-efficiently-inserting-comments-into-pdf-files/"><u>Expert Tips and Tricks for Efficiently Inserting Comments Into PDF Files</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-how-pgsharp-save-you-from-ban-while-spoofing-pokemon-go-on-xiaomi-redmi-note-12-pro-5g-drfone-by-drfone-virtual-android/"><u>In 2024, How PGSharp Save You from Ban While Spoofing Pokemon Go On Xiaomi Redmi Note 12 Pro 5G? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/master-time-windows-finest-tools-to-maximize-output/"><u>Master Time: Windows' Finest Tools to Maximize Output</u></a></li>
<li><a href="https://fox-place.techidaily.com/step-by-step-tutorial-on-adjusting-folder-preferences-in-microsoft-application-virtualization-app-v-version-n0/"><u>Step-by-Step Tutorial on Adjusting Folder Preferences in Microsoft Application Virtualization (App-V) Version N.0</u></a></li>
</ul></div>

