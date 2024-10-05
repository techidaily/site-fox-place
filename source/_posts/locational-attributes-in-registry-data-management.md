---
title: Locational Attributes in Registry Data Management
date: 2024-10-01T21:46:01.347Z
updated: 2024-10-05T19:28:07.681Z
tags:
  - user-guide
categories:
  - advancedinstaller
description: This Article Describes Locational Attributes in Registry Data Management
thumbnail: https://thmb.techidaily.com/946eb20cab96390f79aadddebd59f08cdd8697ebfd4d415c6dfeb99e2e1d4fd0.jpg
---

## Locational Attributes in Registry Data Management

Table of Contents

* [Introduction](https://tools.techidaily.com/advancedinstaller/products/)
* [Registration](https://tools.techidaily.com/advancedinstaller/products/)
* [Using Advanced Installer](https://tools.techidaily.com/advancedinstaller/products/)  
   * [GUI](https://tools.techidaily.com/advancedinstaller/products/)  
   * [Working with Projects](https://tools.techidaily.com/advancedinstaller/products/)  
   * [Installer Project](https://tools.techidaily.com/advancedinstaller/products/)  
         * [Product Information](https://tools.techidaily.com/advancedinstaller/products/)  
         * [Resources](https://tools.techidaily.com/advancedinstaller/products/)  
         * [Package Definition](https://tools.techidaily.com/advancedinstaller/products/)  
         * [Requirements](https://tools.techidaily.com/advancedinstaller/products/)  
         * [User Interface](https://tools.techidaily.com/advancedinstaller/products/)  
         * [System Changes](https://tools.techidaily.com/advancedinstaller/products/)  
         * [Server](https://tools.techidaily.com/advancedinstaller/products/)  
         * [Custom Behavior](https://tools.techidaily.com/advancedinstaller/products/)  
                  * [Search](https://tools.techidaily.com/advancedinstaller/products/)  
                              * [File To Search Properties](https://tools.techidaily.com/advancedinstaller/products/)  
                              * [Component Location Properties](https://tools.techidaily.com/advancedinstaller/products/)  
                              * [Registry Location Properties](https://tools.techidaily.com/advancedinstaller/products/)  
                              * [INI Location Properties](https://tools.techidaily.com/advancedinstaller/products/)  
                              * [XML Search Properties](https://tools.techidaily.com/advancedinstaller/products/)  
                              * [Folder Location Properties](https://tools.techidaily.com/advancedinstaller/products/)  
                              * [Extended Search Properties](https://tools.techidaily.com/advancedinstaller/products/)  
                              * [Search Results](https://tools.techidaily.com/advancedinstaller/products/)  
                  * [Properties Page](https://tools.techidaily.com/advancedinstaller/products/)  
                  * [Custom Actions](https://tools.techidaily.com/advancedinstaller/products/)  
                  * [Table Editor](https://tools.techidaily.com/advancedinstaller/products/)  
   * [Patch Project](https://tools.techidaily.com/advancedinstaller/products/)  
   * [Merge Module Project](https://tools.techidaily.com/advancedinstaller/products/)  
   * [Updates Configuration Project](https://tools.techidaily.com/advancedinstaller/products/)  
   * [Windows Store App Project](https://tools.techidaily.com/advancedinstaller/products/)  
   * [Modification Package Project](https://tools.techidaily.com/advancedinstaller/products/)  
   * [Optional Package Project](https://tools.techidaily.com/advancedinstaller/products/)  
   * [Windows Mobile CAB Projects](https://tools.techidaily.com/advancedinstaller/products/)  
   * [Visual Studio Extension Project](https://tools.techidaily.com/advancedinstaller/products/)  
   * [Software Installer Wizards - Advanced Installer](https://tools.techidaily.com/advancedinstaller/products/)  
   * [Visual Studio integration](https://tools.techidaily.com/advancedinstaller/products/)  
   * [Alternative to AdminStudio/Wise](https://tools.techidaily.com/advancedinstaller/products/)  
   * [Replace Wise](https://tools.techidaily.com/advancedinstaller/products/)  
   * [Migrating from Visual Studio Installer](https://tools.techidaily.com/advancedinstaller/products/)  
   * [Keyboard Shortcuts](https://tools.techidaily.com/advancedinstaller/products/)  
   * [Shell Integration](https://tools.techidaily.com/advancedinstaller/products/)  
   * [Command Line](https://tools.techidaily.com/advancedinstaller/products/)  
   * [Advanced Installer PowerShell Automation Interfaces](https://tools.techidaily.com/advancedinstaller/products/)
* [Features and Functionality](https://tools.techidaily.com/advancedinstaller/products/)
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

## Registry Location Properties

### Root

 The Registry Hive Root. Can be one of "Classes Root", "Current User", "Local Machine" or "Users". 

### Key and Name

 The path to the registry location. Use the\[... \] button to browse the registry and select a key and value using the [Registry Picker Dialog](https://tools.techidaily.com/advancedinstaller/products/). Also, you can insert reference to a file, folder or property using [Smart Edit Control](https://tools.techidaily.com/advancedinstaller/products/).

### Type

 Specifies how to interpret the value found in that registry location: as a path to a file, a folder or raw data. 

* The value contains a path to a file
* The search result property will contain the path to the file's folder if the file **is present** on the target machine. The returned value will be **null** if the file's parent folder does not exist.

| Location exist     | Location does not exist |                    |                        |
| ------------------ | ----------------------- | ------------------ | ---------------------- |
| File location      | C:\\A\\B\\My\_File.txt  | File location      | C:\\A\\B\\My\_File.txt |
| Registry contents  | C:\\A\\B\\My\_File.txt  | Registry contents  | C:\\A\\C\\My\_File.txt |
| **Returned Value** | **C:\\A\\B**            | **Returned Value** | **null**               |

* The value contains a path to a directory
* The result search property will contain the path to the folder if it **is present** on the target machine.The returned value will be **null** if the folder of the directory does not exist.

| Location exist     | Location does not exist |                    |          |
| ------------------ | ----------------------- | ------------------ | -------- |
| File location      | C:\\A\\B                | File location      | C:\\A\\B |
| Registry contents  | C:\\A\\B                | Registry contents  | C:\\A\\C |
| **Returned Value** | **C:\\A\\B**            | **Returned Value** | **null** |

* Retrieve the raw value
* The search result property will be equal with the value extracted from the registry and will be null if the registry value **does not exist**

![Important](https://cdn.advancedinstaller.com/svg/common/IconMessageInfo.svg)When retrieving the raw value of a registry entry you will get these results:

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2012401/19272" target="_top" id="2012401">
  <img src="//a.impactradius-go.com/display-ad/19272-2012401" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2012401/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

* for string entries, the searches property will contain the registry entry's actual value
* for binary entries, the searches property will contain the registry entry's value preceded by the "#x" characters (for example "#xValue")
* for dword entries, the searches property will contain the registry entry's value preceded by the "#" character (for example "#Value")

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1948937/19272" target="_top" id="1948937">
  <img src="//a.impactradius-go.com/display-ad/19272-1948937" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1948937/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### Search the 64-bit portion of the registry

 Check this if you want to search in the 64-bit registry section. 

![Important](https://cdn.advancedinstaller.com/svg/common/IconMessageInfo.svg)In case of [Merge Module](https://tools.techidaily.com/advancedinstaller/products/) projects the following attributes can be made configurable at merge time:

<!-- affiliate ads begin -->
<a href="https://dhgate.sjv.io/c/5597632/1186864/12108" target="_top" id="1186864">
  <img src="//a.impactradius-go.com/display-ad/12108-1186864" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://dhgate.sjv.io/i/5597632/1186864/12108" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

* Root
* Key
* Name
* Type

![Tip](https://cdn.advancedinstaller.com/svg/common/IconMessageTip.svg)For more information about the resources and attributes that can be configured, please see: [Configurable Merge Modules Page](https://tools.techidaily.com/advancedinstaller/products/).

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1925468/19272" target="_top" id="1925468">
  <img src="//a.impactradius-go.com/display-ad/19272-1925468" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1925468/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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
<li><a href="https://fox-boxes.techidaily.com/new-how-to-soften-your-iphone-pics-a-detailed-breakdown-4-ways/"><u>[New] How to Soften Your iPhone Pics A Detailed Breakdown (4 Ways)</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/new-in-2024-new-era-facebooks-quintessential-features-showcased/"><u>[New] In 2024, New Era Facebook's Quintessential Features Showcased</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-2024-approved-interplatform-video-uploading-twitter-and-tumblr-synced/"><u>[Updated] 2024 Approved Interplatform Video Uploading Twitter & Tumblr Synced</u></a></li>
<li><a href="https://screen-recording.techidaily.com/updated-basic-obs-setup-tips-for-budget-machines-for-2024/"><u>[Updated] Basic OBS Setup Tips for Budget Machines for 2024</u></a></li>
<li><a href="https://fox-place.techidaily.com/1-ini-file-editor-customize-settings-with-ease/"><u>1. 'INI File Editor: Customize Settings with Ease'</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/2024-approved-fast-track-fun-turning-animated-art-into-sticky-messages-quickly/"><u>2024 Approved Fast Track Fun Turning Animated Art Into Sticky Messages Quickly</u></a></li>
<li><a href="https://fox-place.techidaily.com/configuring-isapi-filters-through-the-settings-interface/"><u>Configuring ISAPI Filters Through the Settings Interface</u></a></li>
<li><a href="https://fox-place.techidaily.com/discover-the-ultimate-selection-of-excellent-apps-compatible-with-ios-8/"><u>Discover the Ultimate Selection of Excellent Apps Compatible with iOS 8</u></a></li>
<li><a href="https://fox-place.techidaily.com/easy-guide-transforming-your-androids-pdf-files-into-editable-word-documents-in-2020/"><u>Easy Guide: Transforming Your Android's PDF Files Into Editable Word Documents in 2020</u></a></li>
<li><a href="https://unlock-android.techidaily.com/how-to-lock-apps-on-honor-magic-6-to-protect-your-individual-information-by-drfone-android/"><u>How to Lock Apps on Honor Magic 6 to Protect Your Individual Information</u></a></li>
<li><a href="https://fox-place.techidaily.com/how-to-successfully-add-music-to-an-android-smartphone-or-tablet/"><u>How to Successfully Add Music to an Android Smartphone or Tablet</u></a></li>
<li><a href="https://win11.techidaily.com/make-file-examination-easier-integrate-diskspace-insight-into-windows-menu/"><u>Make File Examination Easier: Integrate DiskSpace Insight Into Windows Menu</u></a></li>
<li><a href="https://win-howtos.techidaily.com/overcoming-the-challenge-of-unloaded-buildings-in-pubg-now-corrected/"><u>Overcoming the Challenge of Unloaded Buildings in PUBG - Now Corrected</u></a></li>
<li><a href="https://fox-place.techidaily.com/securing-access-understanding-authentication-techniques/"><u>Securing Access: Understanding Authentication Techniques</u></a></li>
<li><a href="https://fox-place.techidaily.com/top-methods-for-converting-popular-youtube-tracks-into-physical-cd-format-successfully/"><u>Top Methods for Converting Popular YouTube Tracks Into Physical CD Format Successfully</u></a></li>
<li><a href="https://some-guidance.techidaily.com/tracing-the-evolutionary-path-of-windows-movie-maker-for-2024/"><u>Tracing the Evolutionary Path of Windows Movie Maker for 2024</u></a></li>
<li><a href="https://fox-place.techidaily.com/ultimate-steps-for-seamless-transition-of-spotify-playlists-into-apple-music-collection/"><u>Ultimate Steps for Seamless Transition of Spotify Playlists Into Apple Music Collection</u></a></li>
</ul></div>

