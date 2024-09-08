---
title: "Free LUT Strategies for Enhancing AR Experiences"
date: 2024-09-07T20:55:50.827Z
updated: 2024-09-08T20:55:50.827Z
tags: 
  - screen-recording
  - ai video
  - ai audio
  - ai auto
categories: 
  - ai
  - screen
description: "This Article Describes Free LUT Strategies for Enhancing AR Experiences"
excerpt: "This Article Describes Free LUT Strategies for Enhancing AR Experiences"
keywords: "\"Free LUT Tips,AR LUT Techniques,Enhance AR with LUTs,LUT Optimization Guide,Low-Cost AR Improvements,Strategies for AR Upscaling,Aren't LUTs Crucial?\""
thumbnail: https://www.lifewire.com/thmb/xBH9hBuHTmAlBY5tsEJzrsZCnPc=/400x300/filters:no_upscale():max_bytes(150000):strip_icc()/ConnectedCarTech_metamorworks_GettyImages-966859036_CROPPED-a9460403602c4b67a7a8c1acd599c9be.jpg
---

## Free LUT Strategies for Enhancing AR Experiences

Color LUTs (Lookup Textures) are tables of RGB color values. In Spark AR, you can use color LUTs to quickly create color gradation effects throughout the scene. Go through the article and create your color LUT effect.

<!-- affiliate ads begin -->
<a href="https://25home.pxf.io/c/5597632/2123473/16836" target="_top" id="2123473">
  <img src="//a.impactradius-go.com/display-ad/16836-2123473" border="0" alt="https://techidaily.com" width="254" height="90"/>
</a>
<img height="0" width="0" src="https://25home.pxf.io/i/5597632/2123473/16836" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Part 1\. What are Luts in Spark AR used for?

To create a color filter effect in [Spark AR](https://sparkar.facebook.com/ar-studio/), you need a color LUT in Spark AR.

To develop AR effects for mobile cameras, you can use the Mac and Windows augmented reality platform Spark AR Studio. Imagine it like Sketch or Photoshop for augmented reality. The color values of the camera texture are mapped to the x, y, and z coordinates of the location in the color LUT. This location contains a corresponding output color that is drawn over the scene to create a color gradient effect.

![create a color gradient effect](https://images.wondershare.com/filmora/article-images/2022/08/how-to-use-luts-in-spark-ar-1.jpg)

## Part 2\. How to use LUTs in Spark AR?

**How to apply a color LUT to the whole scene in Spark AR:**

##### Step1Add a color LUT to your project

1. In the Assets panel, click Add Asset.
2. Select Import, then Color LUT, and select your file from your computer.

When you import a color LUT, compression is always set to None, and filtering is set to Low by default.

##### Step2Apply to the whole scene

1. In the Assets panel, right-click the LUT color.
2. Select Actions and then **Apply to Camera**.

A patch graph is automatically set that applies a color LUT to the entire scene.

![apply to the whole scene](https://images.wondershare.com/filmora/article-images/2022/08/how-to-use-luts-in-spark-ar-2.jpg)

<!-- affiliate ads begin -->
<span id="1976998">
					<video width="128" height="480" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1976998.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1976998">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1976998.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:80px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1976998%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1976998/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
**The color LUT patch graph**

The patch graph that renders the color gradation effect looks like this:

![color lut patch graph](https://images.wondershare.com/filmora/article-images/2022/08/how-to-use-luts-in-spark-ar-3.jpg)

<!-- affiliate ads begin -->
<a href="https://ursime.pxf.io/c/5597632/2136548/16384" target="_top" id="2136548">
  <img src="//a.impactradius-go.com/display-ad/16384-2136548" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ursime.pxf.io/i/5597632/2136548/16384" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
**To create the effect:**

* Fix Scene Render Pass renders cameraTexture0 and all objects in the scene that are children of the device. This creates the output texture.
* ColorLUTShader looks up the RGBA values of this texture in the Tension color LUT array and converts them to a new green color. This will change the texture and create a gradient effect.
* Finally, the Screen Output patch renders the green color.

<!-- affiliate ads begin -->
<a href="https://25home.pxf.io/c/5597632/2123478/16836" target="_top" id="2123478">
  <img src="//a.impactradius-go.com/display-ad/16836-2123478" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://25home.pxf.io/i/5597632/2123478/16836" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Part 3\. Free LUTs resource for Spark AR

Here are the best free LUTs resources for Spark AR:

### 1\. [Frost Zombie (Technical Showcase)](https://we.tl/t-1uj4wJKluG)

Client filter pieces occasionally end up on the scrap heap. It was a poor Frost Zombie in this instance. Since this is one of my simpler filters, I felt it was okay to publish the build information. Four objects make up much of the scene: an EyeColor block, a custom canvas segmentation, a face mesh, and an emitter for the breath mist (my personal favorite). To show the layers used in generating the primary zombie texture, I also moved to Substance Painter. This is a demonstration of my methods rather than a step-by-step manual.

![frost zombie](https://images.wondershare.com/filmora/article-images/2022/08/how-to-use-luts-in-spark-ar-4.jpg)

<!-- affiliate ads begin -->
<a href="https://25home.pxf.io/c/5597632/2123477/16836" target="_top" id="2123477">
  <img src="//a.impactradius-go.com/display-ad/16836-2123477" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://25home.pxf.io/i/5597632/2123477/16836" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### 2\. Fur

Here are the key building principles.

* Geometric layers, often known as shells, produce depth.
* Normals is used to create shells from a single mesh.
* Alpha decreases with each shell.
* Deeper shells are darker.
* Height is generated from a single grayscale channel.
* No fur is generated in the black areas of the height texture.

![fur](https://images.wondershare.com/filmora/article-images/2022/08/how-to-use-luts-in-spark-ar-5.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2115914/19272" target="_top" id="2115914">
  <img src="//a.impactradius-go.com/display-ad/19272-2115914" border="0" alt="https://techidaily.com" width="250" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2115914/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### 3\. Shockwave

Even while using large image sequences is frequently discouraged, you can still use them to make some extremely spectacular effects! I'll explain how the screen tap computation procedure relates to texture position in this walkthrough. If you want to apply this approach and texture sequence in your projects or give it a try.

![shockwave](https://images.wondershare.com/filmora/article-images/2022/08/how-to-use-luts-in-spark-ar-6.jpg)

<!-- affiliate ads begin -->
<span id="1983472">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1983472.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1983472">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1983472.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1983472%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1983472/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### 4\. Transition Curves

There are 11 distinct animation curves included with Spark AR in the Transition patch. Here is a helpful visual aid because it might be challenging to distinguish between a quartic and a quintic when working on a project. With the SDF circle doubled (to sharpen the edge) and inserted into the Patch Pack's alpha channel, the circles are likewise straightforward rectangles. Since RGB values are three times one, the object is white.

![transition curves](https://images.wondershare.com/filmora/article-images/2022/08/how-to-use-luts-in-spark-ar-7.jpg)

### 5\. Realistic Smoke

By adding smoke to a scene, you can easily add a lot of detail and realism. Nothing revolutionary is happening here. The particle emitter creates flat planes of smoke texture that are forced upward. The force slowly shifts left and right as seen in the patch editor. The Fade particle script (created by Josh Beckwith) enlarges the particles and fades them out at the same time.

![realistic smoke](https://images.wondershare.com/filmora/article-images/2022/08/how-to-use-luts-in-spark-ar-8.jpg)

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134218/18498" target="_top" id="2134218">
  <img src="//a.impactradius-go.com/display-ad/18498-2134218" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134218/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2115910/19272" target="_top" id="2115910">
  <img src="//a.impactradius-go.com/display-ad/19272-2115910" border="0" alt="https://techidaily.com" width="120" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2115910/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### 6\. Rainbow Glitter

Given how beautifully Glitter Rain was received, I believed it would be fitting to broaden the potential with an HDR setting. While Glitter Rain made use of two different colors, this technique makes use of an entirely colorless substance and gets its color information via HDR.

![rainbow glitter](https://images.wondershare.com/filmora/article-images/2022/08/how-to-use-luts-in-spark-ar-9.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2118306/7443" target="_top" id="2118306">
  <img src="//a.impactradius-go.com/display-ad/7443-2118306" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2118306/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### Closing Thoughts

Spark AR is an amazing website for LUTs and color grading. Whether you're a new student or a seasoned pro, Spark AR Studio has all the features and capabilities you need to become a good video editor. You can download free LUTs from Spark AR and apply them to your videos. The article guides on how to use LUTs in Spark AR and how to download free LUTs. So, Spark AR is one of the best online websites for LUTs I have tried.

[Free Download](https://tools.techidaily.com/wondershare/filmora/download/)For Win 7 or later(64-bit)

[Free Download](https://tools.techidaily.com/wondershare/filmora/download/)For macOS 10.14 or later

[Free Download](https://tools.techidaily.com/wondershare/filmora/download/)For macOS 10.14 or later

<ins class="adsbygoogle"
     style="display:block"
     data-ad-format="autorelaxed"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="1223367746"></ins>

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
<li><a href="https://youtube-zero.techidaily.com/024-approved-everything-you-need-to-know-about-the-youtube-shorts-fund/"><u>[New] 2024 Approved Everything You Need to Know About the YouTube Shorts Fund</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/new-2024-approved-maximizing-viewing-tweeting-in-high-definition-hd/"><u>[New] 2024 Approved Maximizing Viewing Tweeting in High Definition (HD)</u></a></li>
<li><a href="https://extra-hints.techidaily.com/new-8-best-photo-grid-online-makers-to-polish-your-pictures/"><u>[New] 8 Best Photo Grid Online Makers to Polish Your Pictures</u></a></li>
<li><a href="https://extra-hints.techidaily.com/new-closing-credits-collection-free-to-subscription-choices/"><u>[New] Closing Credits Collection Free to Subscription Choices</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/new-in-2024-capture-kings-warzone/"><u>[New] In 2024, Capture Kings Warzone</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/new-in-2024-dive-deep-into-obs-advanced-techniques-for-game-capture/"><u>[New] In 2024, Dive Deep Into OBS Advanced Techniques for Game Capture</u></a></li>
<li><a href="https://some-techniques.techidaily.com/new-innovative-approaches-applying-luts-in-photoshop-cc-post-processing/"><u>[New] Innovative Approaches Applying LUTs in Photoshop CC Post-Processing</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/new-x-audiomaster-personal-computing/"><u>[New] X-AudioMaster Personal Computing</u></a></li>
<li><a href="https://video-capture.techidaily.com/updated-2024-approved-the-entry-level-guide-to-superior-gaming-editing-systems/"><u>[Updated] 2024 Approved The Entry Level Guide to Superior Gaming Editing Systems</u></a></li>
<li><a href="https://extra-hints.techidaily.com/updated-brush-up-your-skills-the-definitive-list-of-top-10-drawing-apps-for-android/"><u>[Updated] Brush Up Your Skills The Definitive List of Top 10 Drawing Apps for Android</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-diy-gif-making-transforming-youtube-videos-into-animated-forms-for-2024/"><u>[Updated] DIY GIF Making Transforming YouTube Videos Into Animated Forms for 2024</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-the-ultimate-guide-to-rapidly-eliminating-youtube-feedback/"><u>[Updated] The Ultimate Guide to Rapidly Eliminating YouTube Feedback</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-win11s-ultimate-screen-recording-kit/"><u>[Updated] Win11's Ultimate Screen Recording Kit</u></a></li>
<li><a href="https://extra-hints.techidaily.com/2024-approved-architects-of-unique-virtual-environments/"><u>2024 Approved Architects of Unique Virtual Environments</u></a></li>
<li><a href="https://extra-hints.techidaily.com/2024-approved-color-theory-and-how-to-use-it/"><u>2024 Approved Color Theory And How To Use It</u></a></li>
<li><a href="https://some-approaches.techidaily.com/2024-approved-the-apple-m1-breakdown-a-glimpse-into-the-future/"><u>2024 Approved The Apple M1 Breakdown A Glimpse Into the Future</u></a></li>
<li><a href="https://extra-hints.techidaily.com/astronomy-photographers-website-selection-for-2024/"><u>Astronomy Photographers' Website Selection for 2024</u></a></li>
<li><a href="https://extra-hints.techidaily.com/become-a-vr-trailblazer-with-your-mobile-device/"><u>Become a VR Trailblazer with Your Mobile Device</u></a></li>
<li><a href="https://extra-hints.techidaily.com/best-14-text-animation-examples/"><u>Best 14 Text Animation Examples</u></a></li>
<li><a href="https://extra-hints.techidaily.com/brushstrokes-of-color-expert-shift-strategies-for-2024/"><u>Brushstrokes of Color Expert Shift Strategies for 2024</u></a></li>
<li><a href="https://extra-hints.techidaily.com/digital-imagery-standards-rgb-and-its-successor-srgb/"><u>Digital Imagery Standards Rgb & Its Successor, Srgb</u></a></li>
<li><a href="https://extra-hints.techidaily.com/dynamic-zoom-control-system/"><u>Dynamic Zoom Control System</u></a></li>
<li><a href="https://extra-hints.techidaily.com/elevate-your-editing-game-with-speed-control-skills/"><u>Elevate Your Editing Game with Speed Control Skills</u></a></li>
<li><a href="https://extra-hints.techidaily.com/embracing-total-perspectives-in-filmmaking/"><u>Embracing Total Perspectives in Filmmaking</u></a></li>
<li><a href="https://extra-hints.techidaily.com/explore-the-art-of-iphone-photo-collage-assembly/"><u>Explore the Art of iPhone Photo Collage Assembly</u></a></li>
<li><a href="https://win-able.techidaily.com/fix-guide-how-to-regain-lost-connectivity-to-blizzard-entertainment-network/"><u>Fix Guide: How to Regain Lost Connectivity to Blizzard Entertainment Network</u></a></li>
<li><a href="https://extra-hints.techidaily.com/from-good-to-great-elevate-your-tiktok-edits/"><u>From Good to Great Elevate Your TikTok Edits</u></a></li>
<li><a href="https://win11.techidaily.com/guide-setting-up-or-removing-wi-fi-cost-tracking-in-win11/"><u>Guide: Setting Up or Removing Wi-Fi Cost Tracking in Win11</u></a></li>
<li><a href="https://extra-hints.techidaily.com/hero5-black-meets-yi-4k-the-ultimate-update-for-action-camera-fans/"><u>Hero5 Black Meets Yi 4K - The Ultimate Update for Action Camera Fans</u></a></li>
<li><a href="https://extra-hints.techidaily.com/ideal-narratives-distributed-among-8-movie-segments/"><u>Ideal Narratives Distributed Among 8 Movie Segments</u></a></li>
<li><a href="https://extra-hints.techidaily.com/in-2024-beam-me-up-optimal-webcam-choices-for-podcasts/"><u>In 2024, Beam Me Up Optimal Webcam Choices for Podcasts</u></a></li>
<li><a href="https://extra-hints.techidaily.com/in-2024-best-of-both-worlds-free-paid-film-apps-for-iphones/"><u>In 2024, Best of Both Worlds Free, Paid Film Apps for iPhones</u></a></li>
<li><a href="https://extra-hints.techidaily.com/in-2024-control-screen-size-with-swift-iphone-adjustments/"><u>In 2024, Control Screen Size with Swift iPhone Adjustments</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-how-to-access-your-iphone-12-pro-when-you-forget-the-passcode-drfone-by-drfone-ios/"><u>In 2024, How to Access Your iPhone 12 Pro When You Forget the Passcode? | Dr.fone</u></a></li>
<li><a href="https://some-guidance.techidaily.com/in-2024-unexpected-video-pitch-flipped-images-on-instagram/"><u>In 2024, Unexpected Video Pitch Flipped Images on Instagram</u></a></li>
<li><a href="https://activate-lock.techidaily.com/in-2024-unlocking-an-icloud-locked-ipad-and-apple-iphone-6s-by-drfone-ios/"><u>In 2024, Unlocking an iCloud Locked iPad and Apple iPhone 6s</u></a></li>
<li><a href="https://hardware-help.techidaily.com/instantly-upgrade-to-wireless-freedom-secure-zexmtes-bluetooth-driver-for-your-win1178-system-download/"><u>Instantly Upgrade to Wireless Freedom: Secure Zexmte's Bluetooth Driver for Your Win11/7/8 System (Download)</u></a></li>
<li><a href="https://games-able.techidaily.com/lessons-in-tech-pick-correct-oled-screen/"><u>Lessons in Tech: Pick Correct OLED Screen</u></a></li>
<li><a href="https://extra-hints.techidaily.com/mastering-easy-underwater-film-making-top-7-hacks/"><u>Mastering Easy Underwater Film-Making Top 7 Hacks</u></a></li>
<li><a href="https://extra-hints.techidaily.com/mastering-iphone-photography-focus-on-shadows/"><u>Mastering iPhone Photography Focus on Shadows</u></a></li>
<li><a href="https://extra-hints.techidaily.com/naming-excellence-the-top-10-ai-powered-title-makers/"><u>Naming Excellence The Top 10 AI-Powered Title Makers</u></a></li>
<li><a href="https://extra-hints.techidaily.com/navigating-through-the-best-pc-vr-headset-lineup-of-2023/"><u>Navigating Through the Best PC VR Headset Lineup of 2023</u></a></li>
<li><a href="https://extra-hints.techidaily.com/premier-pro-templates-of-the-year-free-version/"><u>Premier Pro Templates of the Year - Free Version</u></a></li>
<li><a href="https://extra-hints.techidaily.com/premium-pick-ios-sound-artisans-guidebook/"><u>Premium Pick IOS Sound Artisans Guidebook</u></a></li>
<li><a href="https://extra-hints.techidaily.com/sportswomens-scorecard-poker-analysis/"><u>SPORTSWOMEN'S SCORECARD Poker Analysis</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-guide-overcoming-the-pc-reset-failure-on-windows-10/"><u>Step-by-Step Guide: Overcoming the PC Reset Failure on Windows 10</u></a></li>
<li><a href="https://extra-hints.techidaily.com/steps-for-macos-sierra-rollback-to-os-x-el-capitan/"><u>Steps for MacOS Sierra Rollback to OS X El Capitan</u></a></li>
<li><a href="https://extra-hints.techidaily.com/steps-to-secure-clear-image-collections/"><u>Steps to Secure, Clear Image Collections</u></a></li>
<li><a href="https://extra-hints.techidaily.com/streamlining-conversational-data-with-azure-speech-to-text/"><u>Streamlining Conversational Data with Azure Speech to Text</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/top-4-sim-location-trackers-to-easily-find-your-lost-oneplus-nord-ce-3-lite-5g-device-by-drfone-android/"><u>Top 4 SIM Location Trackers To Easily Find Your Lost OnePlus Nord CE 3 Lite 5G Device</u></a></li>
<li><a href="https://extra-hints.techidaily.com/top-iphone-hacks-for-capturing-stunning-skyline-shots/"><u>Top iPhone Hacks for Capturing Stunning Skyline Shots</u></a></li>
<li><a href="https://technical-tips.techidaily.com/transforming-kindle-azw3-books-for-universal-access-tips-for-reading-on-any-device/"><u>Transforming Kindle AZW3 Books for Universal Access: Tips for Reading on Any Device</u></a></li>
<li><a href="https://extra-hints.techidaily.com/transforming-traditional-markets-with-virtual-engineering/"><u>Transforming Traditional Markets with Virtual Engineering</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-insecure-connection-issues-on-firefox-platform/"><u>Troubleshooting Insecure Connection Issues on Firefox Platform</u></a></li>
<li><a href="https://extra-hints.techidaily.com/ultimate-list-of-10-best-zero-cost-srt-conversion-software/"><u>Ultimate List of 10 Best Zero-Cost Srt Conversion Software</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/unlocking-apple-iphone-14-passcode-without-a-computer-by-drfone-ios/"><u>Unlocking Apple iPhone 14 Passcode without a Computer</u></a></li>
<li><a href="https://extra-hints.techidaily.com/vanguard-ventures-newcomers-to-the-panzoid-world/"><u>Vanguard Ventures Newcomers to the Panzoid World</u></a></li>
</ul></div>
