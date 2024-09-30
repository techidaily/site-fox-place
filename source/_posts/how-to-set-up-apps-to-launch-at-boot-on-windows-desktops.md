---
title: How to Set Up Apps to Launch at Boot on Windows Desktops
date: 2024-09-23T09:08:08.668Z
updated: 2024-09-30T12:57:36.311Z
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
<a href="https://appsumo.8odi.net/c/5597632/2043594/7443" target="_top" id="2043594">
  <img src="//a.impactradius-go.com/display-ad/7443-2043594" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2043594/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://article-posts.techidaily.com/new-2024-approved-free-and-top-tier-comparing-the-leading-srt-apps/"><u>[New] 2024 Approved Free & Top-Tier Comparing the Leading SRT Apps</u></a></li>
<li><a href="https://article-posts.techidaily.com/new-cheerful-footage-extractor-analysis-for-2024/"><u>[New] Cheerful Footage Extractor Analysis for 2024</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/new-maximizing-your-photography-with-polarrs-enhanced-features/"><u>[New] Maximizing Your Photography with Polarr's Enhanced Features</u></a></li>
<li><a href="https://fox-helps.techidaily.com/updated-bass-bridges-and-high-beats-understanding-sound-mixing-for-2024/"><u>[Updated] Bass Bridges & High Beats Understanding Sound Mixing for 2024</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/updated-in-2024-savespace-pros-review-summary/"><u>[Updated] In 2024, SaveSpace Pros Review Summary</u></a></li>
<li><a href="https://fox-place.techidaily.com/1-download-various-format-options-zapkolik-video-in-mp4-mov-avi-flv-and-more/"><u>1. Download Various Format Options: Zapkolik Video in MP4, MOV, AVI, FLV, and More</u></a></li>
<li><a href="https://fox-place.techidaily.com/1-ultimate-xtube-video-grabber-convert-and-save-from-xtube-in-multiple-formats-mp4-avi-wmv-mov/"><u>1. Ultimate XTube Video Grabber: Convert and Save From xTube in Multiple Formats (MP4, AVI, WMV, MOV)</u></a></li>
<li><a href="https://fox-place.techidaily.com/1-unlock-exclusive-educational-content-free-downloads-from-discovery-ed/"><u>1. Unlock Exclusive Educational Content: Free Downloads From Discovery Ed</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/2024-approved-step-by-step-approach-to-finding-youtube-collaborators/"><u>2024 Approved Step-by-Step Approach to Finding YouTube Collaborators</u></a></li>
<li><a href="https://fox-place.techidaily.com/complete-guide-downloading-various-file-formats-from-evilchili-including-mp4-mov-and-more/"><u>Complete Guide: Downloading Various File Formats From EvilChili, Including MP4, MOV, and More</u></a></li>
<li><a href="https://fox-place.techidaily.com/complete-tutorial-installing-allavsoft-software-in-mac-catalina-systems/"><u>Complete Tutorial: Installing Allavsoft Software in Mac Catalina Systems</u></a></li>
<li><a href="https://tech-savvy.techidaily.com/entrepreneurs-guide-navigating-through-essential-ai-applications/"><u>Entrepreneur's Guide: Navigating Through Essential AI Applications</u></a></li>
<li><a href="https://os-tips.techidaily.com/how-to-troubleshoot-issues-with-receiving-texts-from-iphones/"><u>How to Troubleshoot Issues with Receiving Texts From iPhones</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/in-2024-the-ultimate-instagram-photography-guide-for-crafting-perfect-covers/"><u>In 2024, The Ultimate Instagram Photography Guide for Crafting Perfect Covers</u></a></li>
<li><a href="https://fox-place.techidaily.com/sharing-your-flipbook-ebooks-on-social-media-easy-guide-for-facebook-twitter-and-linkedin-flipbuilder/"><u>Sharing Your FlipBook eBooks on Social Media - Easy Guide for Facebook, Twitter & LinkedIn | FlipBuilder</u></a></li>
<li><a href="https://fox-place.techidaily.com/the-mechanics-of-sharing-with-flipbuilder-insights-and-tips/"><u>The Mechanics of Sharing with FlipBuilder: Insights and Tips</u></a></li>
<li><a href="https://fox-place.techidaily.com/transform-your-pdfs-into-engaging-digital-flipbooks-including-precise-page-selection-and-navigation-learn-more-at-flipbuildercom/"><u>Transform Your PDFs Into Engaging Digital Flipbooks, Including Precise Page Selection & Navigation - Learn More at [FlipBuilder.com]</u></a></li>
<li><a href="https://fox-place.techidaily.com/transforming-your-flipbuilder-menus-aesthetics-altering-background-colors-easily/"><u>Transforming Your FlipBuilder Menu's Aesthetics: Altering Background Colors Easily</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/unlocking-creative-potential-on-tiktok-through-voiceovers/"><u>Unlocking Creative Potential on TikTok Through Voiceovers</u></a></li>
</ul></div>

