#List of useful Xcode Plugin
A curated list of Xcode plugins and themes.


### Content

- [XCode](#xcode)
	- [Plugins](#plugins)
    - [Editing & Formating](#editing-&-formating)
    - [Apple TV](#apple-tv)
    - [Authentication](#authentication)
    - [Analytics](#analytics)
    - [Bridging](#bridging)
    - [Cache](#cache)
    - [Code Quality](#code-quality)
        - [Linter](#linter)
    - [Color](#color)
    - [Command Line](#command-line)
    - [Concurrency](#concurrency)
    - [Core Data](#core-data)
    - [Charts](#charts)
    - [Database](#database)
    - [Data Structures / Algorithms](#data-structures--algorithms)
    - [Date & Time](#date--time)
    - [EventBus](#eventbus)
    - [Files](#files)
    - [Functional Programming](#functional-programming)
    - [Games](#games)
    - [Gesture](#gesture)
    - [Graphics](#graphics)
    - [Hardware](#hardware)
        - [Bluetooth](#bluetooth)
        - [Camera](#camera)
        - [Force Touch](#force-touch)
        - [iBeacon](#ibeacon)
        - [Location](#location)
        - [Other Hardware](#other-hardware)
    - [JSON](#json)
    - [Layout](#layout)
    - [Localization](#localization)
    - [Logging](#logging)
    - [Maps](#maps)
    - [Math](#math)
    - [Media](#media)
        - [Audio](#audio)
        - [GIF](#gif)
        - [Image](#image)
        - [Media Processing](#media-processing)
        - [PDF](#pdf)
        - [Video](#video)
    - [Messaging](#messaging)
    - [Machine Learning](#machine-learning)
    - [Networking](#networking)
    - [Push Notifications](#push-notifications)
        - [Push Notification Providers](#push-notification-providers)
    - [Passbook](#passbook)
    - [Permissions](#permissions)
    - [Payments](#payments)
    - [Products](#products)
    - [Reactive Programming](#reactive-programming)
    - [Reflection](#reflection)
    - [Regex](#regex)
    - [Security](#security)
        - [Encryption](#encryption)
    - [Text](#text)
        - [Font](#font)
    - [URL Scheme](#url-scheme)
    - [UI](#ui)
        - [Activity Indicator](#activity-indicator)
        - [Alert View](#alerts)
        - [Button](#button)
        - [Calendar](#calendar)
        - [Form](#form)
        - [Keyboard](#keyboard)
        - [Label](#label)
        - [Menu](#menu)
        - [Modal Transition](#modal-transition)
        - [Navigation Bar](#navigation-bar)
        - [Popup](#popup)
        - [Pull to Refresh](#pull-to-refresh)
        - [Rating Stars](#rating-stars)
        - [Slider](#slider)
        - [Stepper](#stepper)
        - [Switch](#switch)
        - [Tab Bar](#tab-bar)
        - [Table View / Collection View](#table-view--collection-view)
        - [Tag](#tag)
        - [TextField & TextView](#textfield--textview)
    - [Utility](#utility)
    - [VR](#vr)
    - [Walkthrough / Intro / Tutorial](#walkthrough--intro--tutorial)
    - [Websocket](#websocket)
    - [XML / HTML / CSV](#xml--html--csv)
- [Project setup](#project-setup)
- [Server](#server)
- [Dependency / Package Manager](#dependency--package-manager)
- [Testing](#testing)
    - [TDD / BDD](#tdd--bdd)
    - [A/B Testing](#ab-testing)
    - [UI Testing](#ui-testing)
    - [Other Testing](#other-testing)
- [Tools](#tools)
- [Rapid Development](#rapid-development)
  - [Injection](#injection)
- [Deployment / Distribution](#deployment--distribution)
- [App Store](#app-store)
- [SDK](#sdk)
    - [Official](#official)
    - [Unofficial](#unofficial)
- [Xcode](#xcode)
    - [Plugins](#plugins)
    - [Themes](#themes)
    - [Other Xcode](#other-xcode)
- [Reference](#reference)
- [Style Guides](#style-guides)
- [Good Websites](#good-websites)
    - [News, Blogs and more](#news-blogs-and-more)
    - [UIKit references](#uikit-references)
    - [Forums and discuss lists](#forums-and-discuss-lists)
    - [Tutorials and Keynotes](#tutorials-and-keynotes)
    - [Prototyping](#prototyping)
    - [Newsletters](#newsletters)
    - [Medium](#medium)
- [Twitter](#twitter)
- [Facebook Groups](#facebook-groups)
- [Podcasts](#podcasts)
- [Books](#books)
- [Other Awesome Lists](#other-awesome-lists)
- [Contributing](#contributing)

# Xcode 
## Plugins
### Editing & Formating 
* [XAlign](https://github.com/qfish/XAlign) - An amazing Xcode plugin to align regular code. It can align anything by using custom alignment patterns.
* [BBUncrustifyPlugin-Xcode](https://github.com/benoitsan/BBUncrustifyPlugin-Xcode) - Xcode plugin to format source code using ClangFormat or Uncrustify.
* [MLAutoReplace](https://github.com/molon/MLAutoReplace) - Xcode plugin, Re-Intent, make you write code more quickly.
* [Peckham](https://github.com/markohlebar/Peckham) - Add #import-s from anywhere in the code.
* [VVDocumenter-Xcode](https://github.com/onevcat/VVDocumenter-Xcode) - Xcode plug-in which helps you write Javadoc style documents easier. 
* [CleanHeaders-Xcode](https://github.com/insanoid/CleanHeaders-Xcode) - A simple iSort like header sorting and duplicate removal plugin for Xcode, makes your headers look more organized.
* [CleanClosureXcode](https://github.com/BalestraPatrick/CleanClosureXcode) - An Xcode Source Editor extension to clean the closure syntax. :large_orange_diamond:
* [xTextHandler](https://github.com/cyanzhong/xTextHandler) - Xcode 8 Source Editor Extension Toolset
* [AutoIndentWithSave](https://github.com/ThilinaHewagama/AutoIndentWithSave) Xcode plugin which indent the source code when save
* [Refactorator](https://github.com/johnno1962/Refactorator) - SourceKit Xcode Plugin that Refactors Swift :large_orange_diamond:
* [Swimat](https://github.com/Jintin/Swimat) - An Xcode formatter plug-in to format your swift code.
* [HOStringSense-for-Xcode](https://github.com/holtwick/HOStringSense-for-Xcode) - Plugin for Xcode to make perfect editing regular expressions, multi line texts, inline HTML and many more use cases. Also provides quick feedback on string length.

### Image & Color
* [KSImageNamed-Xcode](https://github.com/ksuther/KSImageNamed-Xcode) - Xcode plug-in that provides autocomplete for imageNamed: calls.
* [ColorSense-for-Xcode](https://github.com/omz/ColorSense-for-Xcode) - Plugin for Xcode to make working with colors more visual.
* [RTImageAssets](https://github.com/rickytan/RTImageAssets) - A Xcode plugin to automatically generate all the App icons needed.

### Localization 
* [Rephrase](https://www.rephrase.io) - Localise from Xcode. 

### Testing & Debugging
* [BBUFullIssueNavigator](https://github.com/neonichu/BBUFullIssueNavigator) - Xcode plugin for showing all issue content in the issue navigator. 
* [KPRunEverywhereXcodePlugin](https://github.com/kitschpatrol/KPRunEverywhereXcodePlugin) - An Xcode plugin to build and run an app across multiple iOS devices with one click. 
* [QuickJump](https://github.com/wiruzx/QuickJump) - Quick code navigation for Xcode.
* [XcodeWay](https://github.com/onmyway133/XcodeWay) - An Xcode plugin that makes navigating to many places easier (available via Alcatraz).
* [MCLog](https://github.com/yuhua-chen/MCLog) - Xcode plugin for filtering the console area.
* [CopyIssue](https://github.com/hanton/CopyIssue-Xcode-Plugin) - Makes Copy Xcode Issue Description Easy.
* [JumpMarks](https://github.com/merrickp/JumpMarks) - Navigate your code files with numbered bookmarks.
* [XCSnippetr](https://github.com/dzenbot/XCSnippetr) - An Xcode Plugin to upload code snippets directly into Slack and Gist.
* [Luft](https://github.com/k0nserv/luft) - The Xcode Plugin that helps you write lighter view controllers
* [PreciseCoverage](https://github.com/zats/PreciseCoverage) - Make Xcode code coverage more informative
* [VWInstantRun](https://github.com/wangshengjia/VWInstantRun) - An Xcode plugin let you build & run your selected lines of code in Xcode without running the whole project, you'll have the output instantly in your Xcode console. :large_orange_diamond:

### Utility 
* [FuzzyAutocompletePlugin](https://github.com/FuzzyAutocomplete/FuzzyAutocompletePlugin) - A Xcode 5+ plugin that adds more flexible autocompletion rather than just prefix-matching.
* [SCXcodeMiniMap](https://github.com/stefanceriu/SCXcodeMiniMap) - SCXcodeMiniMap is a plugin that adds a source editor MiniMap to Xcode.
* [SCXcodeSwitchExpander](https://github.com/stefanceriu/SCXcodeSwitchExpander) - SCXcodeSwitchExpander is a small Xcode plugin that expands switch statements by inserting missing cases. 
* [RealmPlugin](https://realm.io/docs/objc/0.81.0/#xcode-plugin)- Xcode plugin to generate new Realm models. 
* [XToDo](https://github.com/trawor/XToDo) - Dialog with list of all TODO, FIXME, ??? and !!! in the project. 

### Version Control
* [Show in Github](https://github.com/larsxschneider/ShowInGitHub) - Xcode plugin to open the GitHub page of the commit of the currently selected line in the editor window.
* [CocoaPods Xcode Plugin](https://github.com/kattrali/cocoapods-xcode-plugin) - Dependency management helper for your CocoaPods, right in Xcode.
* [GitDiff](https://github.com/johnno1962/GitDiff) - Highlights deltas against git repo in Xcode.
* [Reveal-In-GitHub](https://github.com/lzwjava/Reveal-In-Github) - Xcode plugin to let you jump to GitHub History, Blame, PRs, Issues, Notifications of any GitHub repo with one shortcut.
* [xSendIssue](https://github.com/hungri-yeti/xSendIssue) - Plugin for Xcode to submit github issues directly from within Xcode.
* [Gradle Xcode plugin](https://openbakery.org/gradle.html) - Build iOS or Mac OS X Projects using Gradle.
* [Gradle](https://github.com/openbakery/gradle-xcodePlugin) - makes it easier to build Xcode projects by specifying the build settings in a single configuration file :large_orange_diamond:

### Miscellaneous
* [Backlight-for-XCode](https://github.com/limejelly/Backlight-for-XCode) - Highlights the current editing line in Xcode
* [BBUDebuggerTuckAway](https://github.com/neonichu/BBUDebuggerTuckAway) - Xcode plugin for auto-hiding the debugger once you start typing in the source code editor. 
* [AdjustFontSize](https://github.com/zats/AdjustFontSize-Xcode-Plugin) - Instant font size adjustment with `⌘ +` / `⌘ -`. 
* [XCActionBar](https://github.com/pdcgomes/XCActionBar) - "Alfred for Xcode" plugin. 
* [AutoHighlightSymbol](https://github.com/chiahsien/AutoHighlightSymbol) - A Xcode plugin to add highlight to the instances of selected symbol.
* [Fastlane-Plugin](https://github.com/RishabhTayal/Fastlane-Plugin) - The awesome Fastlane tools brought into your Xcode.
* [You-Can-Do-It](https://github.com/orta/You-Can-Do-It) - Is learning a new language getting you down? Worry not, this Xcode plugin will keep you motivated.
* [TTPasteHistory](https://github.com/tutumagi/TTPasteHistory) - A Xcode plugin. Recording you copy-and-paste history easily to write the code
* [SYXcodeIconVersion](https://github.com/dvkch/SYXcodeIconVersion) - This Xcode plugin shows Xcode app version in the Dock and App Switcher icon :large_orange_diamond:


## Themes
* [WWDC2016 Xcode Color Scheme](https://github.com/cargath/WWDC2016-Xcode-Color-Scheme) - A color scheme for Xcode based on the WWDC 2016 invitation.
* [Xcode themes list](https://github.com/hdoria/xcode-themes) - Color themes for Xcode.
* [Dracula Theme](https://github.com/zenorocha/dracula-theme) - A dark theme for Xcode.
* [Solarized-Dark-for-Xcode](https://github.com/ArtSabintsev/Solarized-Dark-for-Xcode/) - Solarized Dark Theme for Xcode 5.
 