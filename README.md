# BButton [![Build Status](https://secure.travis-ci.org/jessesquires/BButton.svg)](http://travis-ci.org/jessesquires/BButton) [![Version Status](https://cocoapod-badges.herokuapp.com/v/BButton/badge.png)][docsLink] [![license MIT](http://b.repl.ca/v1/license-MIT-blue.png)][mitLink]

[Twitter Bootstrap](http://getbootstrap.com) buttons for iOS.

`BButton` is a subclass of `UIButton` that is styled like the Twitter Bootstrap buttons, and is drawn entirely with `CoreGraphics`. Buttons can be styled as Bootstrap [version 2](http://getbootstrap.com/2.3.2/) or [version 3](http://getbootstrap.com).

![BButton Screenshot 1][img1] &nbsp;&nbsp;&nbsp;&nbsp; ![BButton Screenshot 2][img2]

## Requirements

* iOS 6.0+ 
* ARC

## Installation

````
pod 'BButton'
````
Otherwise, drag the `BButton/` folder to your project and add the `Fonts provided by application` key to `Info.plist` and include `FontAwesome.ttf`

![plist][img3]

## Getting Started

1. Create programmatically via one of the `init` methods
2. Create via Storyboards
  * Drag a `UIButton` to your view
  * Set its class to `BButton`
3. Be a badass [programming-motherfucker](http://programming-motherfucker.com) and read the fucking documentation. (Yes, there's documentation! [Seriously](http://www.nrcc.org/wp-content/uploads/2013/05/Moonwalk.gif)!)
4. See the included demo project: `BButtonDemo.xcodeproj`
5. See `FontAwesomeIcons.html` for list of icons

## Documentation

Documentation is [available here][docsLink] via [CocoaDocs](http://cocoadocs.org). Thanks [@CocoaDocs](https://twitter.com/CocoaDocs)!

## Customization

* Set corner radius for all buttons via `UIAppearance`

````objective-c
[[BButton appearance] setButtonCornerRadius:[NSNumber numberWithFloat:0.0f]];
````

![BButton Screenshot 3][img4] &nbsp;&nbsp;&nbsp;&nbsp; ![BButton Screenshot 4][img5]

## How To Contribute

Please follow these sweet [contribution guidelines](https://github.com/jessesquires/HowToContribute).

## Credits

Created by [@mattlawer](https://twitter.com/mattlawer) (Original project here: [@mattlawer / BButton](https://github.com/mattlawer/BButton)).

Forked, refactored, updated, maintained by [@jesse_squires](https://twitter.com/jesse_squires), a [programming-motherfucker](http://programming-motherfucker.com).

Many thanks to [the contributors](https://github.com/jessesquires/BButton/graphs/contributors) of this project.

## Apps Using This Control

* [Gitty for GitHub](https://itunes.apple.com/us/app/gitty-for-github/id645696309?mt=8)
* [Hemoglobe](http://bit.ly/hemoglobeapp)
* [Audiotrip](https://itunes.apple.com/us/app/audiotrip/id569634193?mt=8)
* [iExplorer for DeviantART](https://itunes.apple.com/us/app/iexplorer-for-deviantart/id657212778?mt=8)
* [Travel Delay NYC](https://itunes.apple.com/us/app/train-delay-nyc-subway-status/id384027573?mt=8)
* [Libraries for Developers](https://itunes.apple.com/us/app/libraries-for-developers/id653427112?mt=8)
* [CPU Monitor](https://itunes.apple.com/us/app/cpumonitor/id680137811?mt=8)
* [OpenWatch](https://itunes.apple.com/us/app/openwatch-free-video-streaming/id642680756?mt=8)
* [VSNotes](https://itunes.apple.com/us/app/vsnotes/id695433001?mt=8)
* [Crew Scout](https://itunes.apple.com/us/app/crew-scout/id721124938?mt=8)

## License

`BButton` is released under an [MIT License][mitLink]. See `LICENSE.txt` for details.

>Copyright &copy; 2012, Mathieu Bolard, Jesse Squires. All rights reserved.

## [FontAwesome](https://github.com/FortAwesome/Font-Awesome) License

> * The Font Awesome font is licensed under the [SIL Open Font License](http://scripts.sil.org/OFL)
> * Font Awesome CSS, LESS, and SASS files are licensed under the [MIT > License](http://opensource.org/licenses/mit-license.html)
> * The Font Awesome pictograms are licensed under the [CC BY 3.0 License](http://creativecommons.org/licenses/by/3.0)
> * Attribution is no longer required in Font Awesome 3.0, but much appreciated:
	* *"Font Awesome by Dave Gandy - http://fortawesome.github.com/Font-Awesome"*

[docsLink]:http://cocoadocs.org/docsets/BButton/3.2.3
[mitLink]:http://opensource.org/licenses/MIT

[img1]:https://raw.github.com/jessesquires/BButton/master/Screenshots/screenshot-0.png
[img2]:https://raw.github.com/jessesquires/BButton/master/Screenshots/screenshot-2.png
[img3]:https://raw.github.com/jessesquires/BButton/master/Screenshots/plist.png
[img4]:https://raw.github.com/jessesquires/BButton/master/Screenshots/screenshot-4.png
[img5]:https://raw.github.com/jessesquires/BButton/master/Screenshots/screenshot-5.png
