---
title: How to Set Up Apps to Launch at Boot on Windows Desktops
date: 2024-10-09T22:00:25.102Z
updated: 2024-10-10T16:33:31.190Z
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
<a href="https://aligracehair.sjv.io/c/5597632/2135397/19272" target="_top" id="2135397">
  <img src="//a.impactradius-go.com/display-ad/19272-2135397" border="0" alt="https://techidaily.com" width="180" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135397/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://screen-capture.techidaily.com/2024-approved-optimizing-virtual-engagements-with-these-top-10-essential-apps/"><u>2024 Approved Optimizing Virtual Engagements with These Top 10 Essential Apps</u></a></li>
<li><a href="https://fox-place.techidaily.com/customize-components-rules-and-preferences-through-admin-control-panel/"><u>Customize Components' Rules & Preferences Through Admin Control Panel</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/download-the-latest-epson-v39-scanner-software-compatible-with-win7-win8-and-win10/"><u>Download the Latest Epson V39 Scanner Software Compatible with Win7, Win8 & Win10</u></a></li>
<li><a href="https://fox-place.techidaily.com/easy-steps-transforming-your-audio-files-from-ogg-format-to-compatible-mp3/"><u>Easy Steps: Transforming Your Audio Files From OGG Format to Compatible MP3</u></a></li>
<li><a href="https://fox-place.techidaily.com/easy-techniques-to-restore-lost-footage-on-your-android-device/"><u>Easy Techniques to Restore Lost Footage on Your Android Device</u></a></li>
<li><a href="https://fox-place.techidaily.com/enhancing-your-programs-with-advanced-edit-parameter-options/"><u>Enhancing Your Programs with Advanced Edit Parameter Options</u></a></li>
<li><a href="https://some-techniques.techidaily.com/from-skyboxes-to-studio-walls-top-9-drone-software-showdowns-for-2024/"><u>From Skyboxes to Studio Walls Top 9 Drone Software Showdowns for 2024</u></a></li>
<li><a href="https://activate-lock.techidaily.com/in-2024-how-to-remove-find-my-iphone-without-apple-id-on-your-apple-iphone-11-pro-max-by-drfone-ios/"><u>In 2024, How to Remove Find My iPhone without Apple ID On your Apple iPhone 11 Pro Max?</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-how-to-unlock-oneplus-nord-ce-3-lite-5g-phone-without-google-account-by-drfone-android/"><u>In 2024, How to Unlock OnePlus Nord CE 3 Lite 5G Phone without Google Account?</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-the-top-5-android-apps-that-use-fingerprint-sensor-to-lock-your-apps-on-tecno-spark-go-2024-by-drfone-android/"><u>In 2024, The Top 5 Android Apps That Use Fingerprint Sensor to Lock Your Apps On Tecno Spark Go (2024)</u></a></li>
<li><a href="https://ios-location-track.techidaily.com/in-2024-top-10-telegram-spy-tools-on-apple-iphone-12-mini-for-parents-drfone-by-drfone-virtual-ios/"><u>In 2024, Top 10 Telegram Spy Tools On Apple iPhone 12 mini for Parents | Dr.fone</u></a></li>
<li><a href="https://vp-tips.techidaily.com/legal-tunes-collection-top-10-free-music-for-mindfulness-for-2024/"><u>Legal Tunes Collection – Top 10 Free Music for Mindfulness for 2024</u></a></li>
<li><a href="https://fox-place.techidaily.com/optimizing-your-website-enhancing-security-with-ssl-configuration/"><u>Optimizing Your Website: Enhancing Security with SSL Configuration</u></a></li>
<li><a href="https://fox-place.techidaily.com/proven-techniques-efficiently-cleaning-up-your-photos-by-eliminating-unwanted-elements/"><u>Proven Techniques: Efficiently Cleaning Up Your Photos by Eliminating Unwanted Elements</u></a></li>
<li><a href="https://fox-place.techidaily.com/step-by-step-guide-to-converting-your-videos-from-webm-to-avi-format/"><u>Step-by-Step Guide to Converting Your Videos From WebM to AVI Format</u></a></li>
<li><a href="https://win11-tips.techidaily.com/techniques-for-animating-items-on-screen-tutorial-for-engaging-content/"><u>Techniques for Animating Items on Screen - Tutorial for Engaging Content</u></a></li>
<li><a href="https://fox-place.techidaily.com/understanding-and-editing-isapi-filter-options-in-iis-manager/"><u>Understanding and Editing ISAPI Filter Options in IIS Manager</u></a></li>
</ul></div>

