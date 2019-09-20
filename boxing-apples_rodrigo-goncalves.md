Boxing Apples: packaging for Darwin
=================================================

* Speaker   : [Rodrigo Gonçalves](https://pixels.camp/pragmapilot)
* Available : **27 March in the afternoon** 
* Length    :  **60m**
* Language  : **English** 

Description
-----------

In this day and age of magical toolchains that abstract most of development steps do you know how your Darwin app is being packaged? Let's take a peek under the hood and see not just how it's done but let's also explore how we can manually prepare a packaged Darwin app written in Swift **without** using the Xcode or Swift Package Manager toolchains.  

Speaker Bio
-----------

13y of experience Software Engineer turned into Engineering Manager. Past lives in iOS, Android, Web, APIs and desktop systems. INFJ, people lover, perpetual learner and true believer in the human ability of growing and improving.

Links
-----

* Company: https://talkdesk.com 
* GitHub: https://github.com/pragmapilot 
* Photo: https://raw.githubusercontent.com/PixelsCamp/talks/master/img/rodrigo_goncalves.jpg 

Extra Information
-----------------

In this talk I intend to cover the packaging process of Darwin (iOS/macOS) apps. I will discuss how the Darwin OS expects an app to be packed, focusing on the structure. Compilation and linkage need to be adjusted for the proper targets and to take into account if external frameworks are used in the application. 

The challenge here is not to use the Xcode or Swift Package Manager but to build, throughout the presentation, a simple packaging system that resembles these toolchains in the basic functionality to explain how the package is done. While the core of the talk will focus on Mac app I will include a section describing how the solution can be adapted to iOS, thus explaining the difference between both targets

I am currently working on a small sample command-line Mac app that will be the basis for the explanation. This is still a work-in-process and the repo will be made publicly available before the talk or sooner when it is in a less transient state.