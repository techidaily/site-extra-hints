---
title: "A Beginner's Tutorial on Using LUTs in AR"
date: 2024-05-24T00:49:33.168Z
updated: 2024-05-25T00:49:33.169Z
tags: 
  - screen-recording
  - ai video
  - ai audio
  - ai auto
categories: 
  - ai
  - screen
description: "This Article Describes A Beginner's Tutorial on Using LUTs in AR"
excerpt: "This Article Describes A Beginner's Tutorial on Using LUTs in AR"
keywords: "AR LUT Basics,Beginners Guide to LUTs,Using LUTs in AR,LUTs for AR Devices,Introduction to AR LUTs,Learning AR LUT Techniques,Essential AR LUT Tutorial"
thumbnail: https://www.lifewire.com/thmb/QyMelMGWGiu7q4X5VJipLbZv_Uw=/400x300/filters:no_upscale():max_bytes(150000):strip_icc()/netflix-dvd-5fbba31e4b0b46f29cb1d3a17a1a5b28.jpg
---

## A Beginner's Tutorial on Using LUTs in AR

Color LUTs (Lookup Textures) are tables of RGB color values. In Spark AR, you can use color LUTs to quickly create color gradation effects throughout the scene. Go through the article and create your color LUT effect.

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

**The color LUT patch graph**

The patch graph that renders the color gradation effect looks like this:

![color lut patch graph](https://images.wondershare.com/filmora/article-images/2022/08/how-to-use-luts-in-spark-ar-3.jpg)

**To create the effect:**

* Fix Scene Render Pass renders cameraTexture0 and all objects in the scene that are children of the device. This creates the output texture.
* ColorLUTShader looks up the RGBA values of this texture in the Tension color LUT array and converts them to a new green color. This will change the texture and create a gradient effect.
* Finally, the Screen Output patch renders the green color.

## Part 3\. Free LUTs resource for Spark AR

Here are the best free LUTs resources for Spark AR:

### 1\. [Frost Zombie (Technical Showcase)](https://we.tl/t-1uj4wJKluG)

Client filter pieces occasionally end up on the scrap heap. It was a poor Frost Zombie in this instance. Since this is one of my simpler filters, I felt it was okay to publish the build information. Four objects make up much of the scene: an EyeColor block, a custom canvas segmentation, a face mesh, and an emitter for the breath mist (my personal favorite). To show the layers used in generating the primary zombie texture, I also moved to Substance Painter. This is a demonstration of my methods rather than a step-by-step manual.

![frost zombie](https://images.wondershare.com/filmora/article-images/2022/08/how-to-use-luts-in-spark-ar-4.jpg)

### 2\. Fur

Here are the key building principles.

* Geometric layers, often known as shells, produce depth.
* Normals is used to create shells from a single mesh.
* Alpha decreases with each shell.
* Deeper shells are darker.
* Height is generated from a single grayscale channel.
* No fur is generated in the black areas of the height texture.

![fur](https://images.wondershare.com/filmora/article-images/2022/08/how-to-use-luts-in-spark-ar-5.jpg)

### 3\. Shockwave

Even while using large image sequences is frequently discouraged, you can still use them to make some extremely spectacular effects! I'll explain how the screen tap computation procedure relates to texture position in this walkthrough. If you want to apply this approach and texture sequence in your projects or give it a try.

![shockwave](https://images.wondershare.com/filmora/article-images/2022/08/how-to-use-luts-in-spark-ar-6.jpg)

### 4\. Transition Curves

There are 11 distinct animation curves included with Spark AR in the Transition patch. Here is a helpful visual aid because it might be challenging to distinguish between a quartic and a quintic when working on a project. With the SDF circle doubled (to sharpen the edge) and inserted into the Patch Pack's alpha channel, the circles are likewise straightforward rectangles. Since RGB values are three times one, the object is white.

![transition curves](https://images.wondershare.com/filmora/article-images/2022/08/how-to-use-luts-in-spark-ar-7.jpg)

### 5\. Realistic Smoke

By adding smoke to a scene, you can easily add a lot of detail and realism. Nothing revolutionary is happening here. The particle emitter creates flat planes of smoke texture that are forced upward. The force slowly shifts left and right as seen in the patch editor. The Fade particle script (created by Josh Beckwith) enlarges the particles and fades them out at the same time.

![realistic smoke](https://images.wondershare.com/filmora/article-images/2022/08/how-to-use-luts-in-spark-ar-8.jpg)

### 6\. Rainbow Glitter

Given how beautifully Glitter Rain was received, I believed it would be fitting to broaden the potential with an HDR setting. While Glitter Rain made use of two different colors, this technique makes use of an entirely colorless substance and gets its color information via HDR.

![rainbow glitter](https://images.wondershare.com/filmora/article-images/2022/08/how-to-use-luts-in-spark-ar-9.jpg)

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
<li><a href="https://extra-hints.techidaily.com/2024-approved-best-available-avi-player-with-cross-platform-support/"><u>2024 Approved  Best Available Avi Player with Cross-Platform Support</u></a></li>
<li><a href="https://extra-hints.techidaily.com/2024-approved-comprehensive-report-dji-inspire-1-reviewed/"><u>2024 Approved  Comprehensive Report  DJI Inspire 1 Reviewed</u></a></li>
<li><a href="https://extra-hints.techidaily.com/2024-approved-6-empowering-metaverse-instances-explained/"><u>2024 Approved  6 Empowering Metaverse Instances Explained</u></a></li>
<li><a href="https://extra-hints.techidaily.com/updated-capture-the-internets-attention-craft-with-kapwing/"><u>[Updated] Capture the Internet’s Attention – Craft with Kapwing</u></a></li>
<li><a href="https://extra-hints.techidaily.com/in-2024-acquiring-vivid-clipart-without-investment/"><u>In 2024, Acquiring Vivid Clipart Without Investment</u></a></li>
<li><a href="https://extra-hints.techidaily.com/quick-fix-guide-adding-a-flip-tone-to-your-pcs-vocal-array/"><u>Quick-Fix Guide  Adding a Flip Tone to Your PC's Vocal Array</u></a></li>
<li><a href="https://extra-hints.techidaily.com/quicklooker-windows-11s-speedy-photo-viewer/"><u>QuickLooker  Windows 11'S Speedy Photo Viewer</u></a></li>
<li><a href="https://extra-hints.techidaily.com/new-acquiring-high-clarity-imagery-without-limitations/"><u>[New] Acquiring High-Clarity Imagery without Limitations</u></a></li>
<li><a href="https://extra-hints.techidaily.com/securing-snapshots-innovative-approaches-to-face-pixilation/"><u>Securing Snapshots  Innovative Approaches to Face Pixilation</u></a></li>
<li><a href="https://extra-hints.techidaily.com/top-10-aerial-cameras-unleashing-creative-potential/"><u>Top 10 Aerial Cameras  Unleashing Creative Potential</u></a></li>
<li><a href="https://extra-hints.techidaily.com/nextv-networks-the-ultimate-streamers-global-guide/"><u>NexTV Networks  The Ultimate Streamer's Global Guide</u></a></li>
<li><a href="https://extra-hints.techidaily.com/how-to-make-amazing-slow-motion-video-on-android-easily/"><u>How to Make Amazing Slow Motion Video on Android Easily</u></a></li>
<li><a href="https://extra-hints.techidaily.com/blueprint-for-seamless-integration-of-instagram-and-tiktok/"><u>Blueprint for Seamless Integration of Instagram and TikTok</u></a></li>
<li><a href="https://extra-hints.techidaily.com/in-2024-capturing-velocity-hero-4-versus-ghost-s-racing/"><u>In 2024, Capturing Velocity  Hero 4 Versus Ghost-S Racing</u></a></li>
<li><a href="https://extra-hints.techidaily.com/deconstructing-user-sentiments-for-vllo/"><u>Deconstructing User Sentiments for VLLO</u></a></li>
<li><a href="https://extra-hints.techidaily.com/updated-crafting-perfect-images-with-ios-size-modification-skills/"><u>[Updated] Crafting Perfect Images with iOS Size Modification Skills</u></a></li>
<li><a href="https://extra-hints.techidaily.com/digital-painting-choosing-between-srgb-and-rgb/"><u>Digital Painting  Choosing Between Srgb & Rgb</u></a></li>
<li><a href="https://extra-hints.techidaily.com/in-2024-aerial-shooting-essentials/"><u>In 2024, Aerial Shooting Essentials</u></a></li>
<li><a href="https://extra-hints.techidaily.com/top-10-vectors-where-quality-thrives/"><u>Top 10 Vectors  Where Quality Thrives</u></a></li>
<li><a href="https://extra-hints.techidaily.com/updated-audiences-take-gopro-hero5-footage/"><u>[Updated] Audience's Take  GoPro Hero5 Footage</u></a></li>
<li><a href="https://extra-hints.techidaily.com/2024-approved-comprehensive-budget-strategies-for-podcasters/"><u>2024 Approved  Comprehensive Budget Strategies for Podcasters</u></a></li>
<li><a href="https://extra-hints.techidaily.com/in-2024-become-a-design-pro-expertise-in-bypassing-backgrounds-with-canva/"><u>In 2024, Become a Design Pro  Expertise in Bypassing Backgrounds with Canva</u></a></li>
<li><a href="https://extra-hints.techidaily.com/unlocking-the-full-potential-of-iphones-hdr-functions/"><u>Unlocking the Full Potential of iPhone's HDR Functions</u></a></li>
<li><a href="https://extra-hints.techidaily.com/funnyfilmmaker-quick-comic-creation/"><u>FunnyFilmMaker  Quick Comic Creation</u></a></li>
<li><a href="https://extra-hints.techidaily.com/dark-moments-decoded-for-iphone-users/"><u>Dark Moments Decoded for iPhone Users</u></a></li>
<li><a href="https://extra-hints.techidaily.com/elevate-editing-mastering-inshot-for-laptopspcs/"><u>Elevate Editing  Mastering Inshot for Laptops/PCs</u></a></li>
<li><a href="https://extra-hints.techidaily.com/documentary-storytelling-from-idea-to-screenplay/"><u>Documentary Storytelling  From Idea to Screenplay</u></a></li>
<li><a href="https://extra-hints.techidaily.com/achieving-proficiency-comprehensive-photoshop-hdr-tutorial-for-2024/"><u>Achieving Proficiency  Comprehensive Photoshop HDR Tutorial for 2024</u></a></li>
<li><a href="https://extra-hints.techidaily.com/beginners-basics-of-video-clarity-and-sharpness/"><u>Beginner's Basics of Video Clarity and Sharpness</u></a></li>
<li><a href="https://extra-hints.techidaily.com/beyond-gaming-vr-uses/"><u>Beyond Gaming  VR Uses</u></a></li>
<li><a href="https://extra-hints.techidaily.com/beijings-frigid-triumph-in-winter-sports-2022-for-2024/"><u>Beijing's Frigid Triumph in Winter Sports, 2022 for 2024</u></a></li>
<li><a href="https://extra-hints.techidaily.com/eluding-attention-with-strategic-cropping/"><u>Eluding Attention with Strategic Cropping</u></a></li>
<li><a href="https://extra-hints.techidaily.com/the-complete-scoop-on-vitas-video-editor-app-detailed-review-2024/"><u>The Complete Scoop on Vita’s Video Editor App, Detailed Review 2024</u></a></li>
<li><a href="https://extra-hints.techidaily.com/spotify-how-to-stop-seeing-podcast-recommendations/"><u>Spotify  How to Stop Seeing Podcast Recommendations</u></a></li>
<li><a href="https://extra-hints.techidaily.com/elevate-your-youtube-live-gameplay-even-when-numbers-are-low/"><u>Elevate Your Youtube Live Gameplay – Even when Numbers Are Low</u></a></li>
<li><a href="https://extra-hints.techidaily.com/essential-cameras-of-the-year-top-10-reviewed/"><u>Essential Cameras of the Year - Top 10 Reviewed</u></a></li>
<li><a href="https://extra-hints.techidaily.com/professional-take-on-the-lg-bp350-monitors-connectivity-features/"><u>Professional Take on the LG BP350 Monitor's Connectivity Features</u></a></li>
<li><a href="https://extra-hints.techidaily.com/tech-advancements-17-software-options-for-streamlined-photo-edits/"><u>Tech Advancements  17 Software Options for Streamlined Photo Edits</u></a></li>
<li><a href="https://extra-hints.techidaily.com/precision-copywriting-a-deep-dive-into-the-world-of-slug-lines/"><u>Precision Copywriting  A Deep Dive Into the World of Slug Lines</u></a></li>
<li><a href="https://extra-hints.techidaily.com/superior-sd-card-compatible-with-a7s-ii/"><u>Superior SD Card Compatible with A7S II</u></a></li>
<li><a href="https://extra-hints.techidaily.com/2024-approved-aeon-matrix-the-single-screen-superior-desk/"><u>2024 Approved  Aeon Matrix  The Single Screen, Superior Desk</u></a></li>
<li><a href="https://extra-hints.techidaily.com/a-practical-approach-to-zoom-meetings-for-2024/"><u>A Practical Approach to Zoom Meetings for 2024</u></a></li>
<li><a href="https://extra-hints.techidaily.com/achieving-seamless-sounds-logic-x-crossfade-guide/"><u>Achieving Seamless Sounds  Logic X Crossfade Guide</u></a></li>
<li><a href="https://extra-hints.techidaily.com/sony-a6400-why-is-my-video-playback-failed/"><u>Sony A6400  Why Is My Video Playback Failed?</u></a></li>
<li><a href="https://extra-hints.techidaily.com/unmatched-action-footage-top-7-best-camcorders/"><u>Unmatched Action Footage  Top 7 Best Camcorders</u></a></li>
<li><a href="https://extra-hints.techidaily.com/strategies-for-closing-down-a-forgotten-linkedin-profile/"><u>Strategies for Closing Down a Forgotten LinkedIn Profile</u></a></li>
<li><a href="https://screen-capture.techidaily.com/2024-approved-direct-methods-reverse-film-frames-on-vlc-platform/"><u>2024 Approved  Direct Methods  Reverse Film Frames on VLC Platform</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/the-magnificent-art-of-pokemon-go-streaming-on-honor-magic-5-drfone-by-drfone-virtual-android/"><u>The Magnificent Art of Pokemon Go Streaming On Honor Magic 5? | Dr.fone</u></a></li>
<li><a href="https://screen-capture.techidaily.com/best-ios-apps-to-play-your-favorite-psp-games-for-2024/"><u>Best iOS Apps to Play Your Favorite PSP Games for 2024</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/new-instantly-stream-youtube-content-on-facebook-auto-play-guide/"><u>[New] Instantly Stream YouTube Content on Facebook  Auto-Play Guide</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/new-in-2024-a-step-by-step-guide-to-including-vimeo-on-instagram/"><u>[New] In 2024, A Step-by-Step Guide to Including Vimeo on Instagram</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/how-to-get-and-use-pokemon-go-promo-codes-on-oppo-reno-11f-5g-drfone-by-drfone-virtual-android/"><u>How to Get and Use Pokemon Go Promo Codes On Oppo Reno 11F 5G | Dr.fone</u></a></li>
<li><a href="https://activate-lock.techidaily.com/ultimate-guide-on-iphone-14-plus-icloud-activation-lock-bypass-by-drfone-ios/"><u>Ultimate Guide on iPhone 14 Plus iCloud Activation Lock Bypass</u></a></li>
<li><a href="https://video-capture.techidaily.com/2024-approved-quick-tips-for-capturing-online-video-conversations/"><u>2024 Approved  Quick Tips for Capturing Online Video Conversations</u></a></li>
<li><a href="https://twitter-clips.techidaily.com/updated-2024-approved-vidvault-prodigies-mastering-the-download-of-tweeted-videos/"><u>[Updated] 2024 Approved  VidVault Prodigies  Mastering the Download of Tweeted Videos</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/new-avoid-facebook-video-cover-mistakes-learn-the-ideal-size-and-resolution-for-2024/"><u>New Avoid Facebook Video Cover Mistakes Learn the Ideal Size and Resolution for 2024</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/new-in-2024-elevate-your-video-game-best-free-online-video-enhancement-software/"><u>New In 2024, Elevate Your Video Game Best Free Online Video Enhancement Software</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/new-2024-approved-ultimate-strategic-guide-to-facebook-video-promotions/"><u>[New] 2024 Approved  Ultimate Strategic Guide to Facebook Video Promotions</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/why-your-transparent-gif-is-hard-to-remove-and-how-to-do-with-it/"><u>Why Your Transparent GIF Is Hard to Remove and How to Do With It</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/2024-approved-how-to-record-a-voice-over-for-a-video/"><u>2024 Approved  How To Record A Voice Over For A Video</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/new-in-2024-snap-into-the-loop-mastering-boomerangs-for-max-impact/"><u>[New] In 2024, Snap Into the Loop  Mastering Boomerangs for Max Impact</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/new-exploring-every-aspect-of-androids-recording-technology/"><u>[New] Exploring Every Aspect of Android's Recording Technology</u></a></li>
<li><a href="https://android-frp.techidaily.com/hassle-free-ways-to-remove-frp-lock-on-realme-gt-5-pro-phones-withwithout-a-pc-by-drfone-android/"><u>Hassle-Free Ways to Remove FRP Lock on Realme GT 5 Pro Phones with/without a PC</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-the-ultimate-guide-to-selecting-facebook-live-capturers/"><u>[Updated] The Ultimate Guide to Selecting Facebook Live Capturers</u></a></li>
<li><a href="https://animation-videos.techidaily.com/new-2024-approved-top-12-evil-cartoon-characters-of-all-time/"><u>New 2024 Approved Top 12 Evil Cartoon Characters of All Time</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/new-in-2024-uncomplicated-guide-to-mobile-device-live-captures/"><u>[New] In 2024, Uncomplicated Guide to Mobile Device Live Captures</u></a></li>
<li><a href="https://video-capture.techidaily.com/updated-in-2024-selecting-optimal-frame-rate-30fps-vs-60fps-for-quality-recording/"><u>[Updated] In 2024, Selecting Optimal Frame Rate  30Fps Vs. 60Fps for Quality Recording</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/how-to-reset-a-locked-nokia-xr21-phone-by-drfone-android/"><u>How to Reset a Locked Nokia XR21 Phone</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/2024-approved-top-12-free-animation-tools-for-windows-and-macos/"><u>2024 Approved Top 12 Free Animation Tools for Windows and macOS</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-still-using-pattern-locks-with-samsung-galaxy-m54-5g-tips-tricks-and-helpful-advice-by-drfone-android/"><u>In 2024, Still Using Pattern Locks with Samsung Galaxy M54 5G? Tips, Tricks and Helpful Advice</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/in-2024-best-bites-in-a-byte-tiktok-chefs/"><u>In 2024, Best Bites in a Byte  TikTok Chefs</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/new-12-impressive-ai-video-ideas-for-creating-engaging-video-content/"><u>New 12 Impressive AI Video Ideas for Creating Engaging Video Content</u></a></li>
</ul></div>

