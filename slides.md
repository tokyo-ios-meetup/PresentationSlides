autoscale: true

![inline](logo.png)

11:00 am - 11:10 am: Introduction

11:10 am - 12:50 pm: WWDC 2017 Highlights Discussion

12:50 - 1:00pm: Discussion

---

# June 2017 Tokyo iOS Meetup

---

# Greet someone near you.

---

# WWDC 2017
- Hardware
- Xcode
- Swift
- iOS 11

---

# **Hardware**

---

# HomePod

---

# MacBook Pro
^ Higher drive capacities, new Kaby Lake processors

---

# MacBook Air, MacBook
^ Air: Processor update, lowered price (entry level 13" model)
^ MacBook: Processor update, graphics update

---

# iMac / iMacPro

^ iMac: New GPUs, new Kaby Lake processors, 4K screen, more RAM.

^ The iMac Pro: Up to 18 cores, 128GB of RAM, AMD Radeon Vega GPUs, Thunderbolt 3 ports, 10Gb Ethernet, up to 4TB SSDs; starting at $4,999.

---

# 10.5” iPad Pro

---

# VR
- 3D content creation
- 360 degree video editing
- External GPU support for MacBookPro
- External GPU Developer Kit including discount on HTV Vive Display ($599)

^ Enabling VR Development
^ Metal2 helps with performance, plus new iMacs / GPUs
^ Optimization performance for GPU via Xcode developer tools
^ STEAM VR Beta for macOS

---

# **Xcode**

---

# New structure-based editor
- Fast scrolling
- Better find/replace
- Faster search
- Markdown support
- Improved 'FixIt'

^ Indexing while building to allow better performance

---

# Refactoring
- Global rename across Swift, Objective C, C, C++
- Converts method signatures
- Updates properties
- Fills in missing cases in switch statements
- Extract method functionality

---

# Moving files within Xcode

^ Now updates the folder in the file system as well!

---

# Wireless development & debugging
- USB, Wifi, or Ethernet

---

# Source control
- Github support
- View branches side-by-side
- File diffs
- "Open in Xcode" from github.com

---

# Xcode Server built-in

^ No longer need to install macOS Xcode Server

---

# Simulator Enhancements
- Multiple booted devices / multiple sessions
- Parallel device and simulator testing (command line)
- Capture screenshots
- Multiple apps with one UI test

^ UI Testing performance, new first match APIs

---

# New Playground templates
- Run in Xcode and in the Swift Playgrounds iPad app

---

# Text macros can be defined in a plist

^ Variables inside of a plist?

---

# New Build System
- More reliable
- Catches project configuration problems
- Improves build performance
- Currently optional (can be turned on in settings)
- Written in Swift

^ Building large mix-and-match Swift/Objective-C projects 40% faster

---

# Undefined Behavior Sanitizer

^ Detects program crashes, incompatibilities

---

# Main Thread Checker Sanitizer

^ Checks when UIKit is not called on the main thread
^ "... must be called from the main thread only"

---

# View Debugger
- View Controllers in View Debugger
- Support for SpriteKit scenes

---

# **Swift**

---

# String
- Range-replaceable bidirectional collections
- Slicing
- Multi-line literals
- Unicode 9
- Performance

---

# Codable Protocol
- Transformation of objects to/from JSON

```
let farm = Farm(name: "Old MacDonald's Farm",
                location: Location(latitude: 51.6216,
                                   longitude: 0.2692),
                animals: [.cow, .dog, .chicken])

let payload: Data = try JSONEncoder().encode(farm)
let farm = try JSONDecoder().decode(Farm.self, from: payload)
```

---

# Swift 3.2
- Build projects with no modifications
- Use almost all new Swift features
- Use new APIs from SDK
- No Swift-improvements to existing APIs

---

# Swift 4.0
- Use all the new language features
- Improved performance
- SDK improvements for Swift
- Some migration required

---

# Select Swift Language Version
- 3.2 vs 4.0 versions
- One compiler
- Two Swift language modes
- Mix-and-match 3.2 and 4.0 targets

---

# Swift Playgrounds
- v1.5 Integration with Parrot drone, UBTech Robot, Sphero ball, Wonder Workshop robot, Oskoog Music, Lego Robot (Available Now)
- v2.0 Author-hosted content, subscriptions (Fall 2017 Release)

^ 1.5: Line-by-line highlighting, Content update notifications, Add new Playground pages, Improved error messages, MapKit support

^ 2.0: Playground Feeds, Author-hosted content, Subscription model, Update notifications, 8 additional localizations

---

# **iOS 11**

---

# Drag and Drop
- "Easy to adopt"; automatic for text and web
- Multi-touch enabled
- Works system-wide, within an app, and across apps
- Add custom previews and animations
- Support added in various SDKs (UIView, UITableView, UICollectionView)

^ Examples organizing the home screen; drag and drop from one app into another

---

# Dynamic Type
- UIFontMetrics can help scale custom fonts
- Autolayout can adjust spacing when using the baseline anchor
- Better spacing support in UIStackView, NSLayoutAnchors
- PDF assets can scale smoothly
- Better accessibility - UIAccessibilityContentSizeCategoryImageAdjusting
- Extra-large title below navigation bar
- Unified search bar

---

# SiriKit
- Visual codes for exchanging payment and contact information
- Added Lists and Notes
- Canceling rides
- Transferring money
- Searching Accounts

^ New intents for Siri

---

# MusicKit
- Access to the Apple Music catalog
- StoreKit can retrieve client tokens and storefront identifiers
- Media Player can play stations
- Custom messages can be displayed in the Apple Music subscriber flow

---

# AirPlay 2
- Supported in AVFoundation
- New AVAudioSession support for long-form audio playback (e.g. podcasts)
- FairPlay streaming management

^ Related to Apple Music? Streaming Apple Music? DRM?

---

# App Password Autofill
- Added username and password properties to UITextContentType

---

# Keyboard extension
- Added new properties (selectedText, documentIdentifier, hasFullAccess, needsInputModeSwitchKey)
- New system permissions for app access

---

![](ARKit Demo.mp4)

---

# ARKit
- Motion tracking
- Camera scene tracking
  - Coordinates accurate to 5% so your objects feel natural in the scene
  - Accurate light estimation so you can adjust your objects to look natural
- Scene processing
- iPhone6s or later, iPadPro or later

^ 60fps using the gyro and accelerometer
^ Rendering Engine: Metal2 (lower level framework), SceneKit, or SpriteKit
^ Unity open-source plugin
^ Epic Unreal Engine developer preview

---

# Vision
- Detects faces, landmarks, rectangles, text, barcodes, image horizon
- Integrates with CoreML to run models on images
- Tracks objects in video
- Includes support for image registration

^ “Computer Vision”

---

# Core ML
- Easily integrate Machine Learning models in an app
- Feed Forward, Convolutional, Recurrent Neural Networks
- Tree ensembles, Support Vector Machines (SMVs), Generalized Linear Models
- Caffe, Keras, scikit learn, dlmc XGBOOST, turi, LIBSVM
- Workflow: Caffe → Core ML Converter → ML Model → Xcode → App using CoreML
- * Open Sourcing Core ML Converter
^ For importing

---

# Metal 2
- GPU Driven Rendering
- Cross-platform shader support (macOS, tvOS, iOS)
- Neutral Network support (added graph data structure, Convolutional Neural Networks, and Recurrent Neural Networks)
- Indirect Argument Buffers
- Program the positions of samples
- Uniform type
- New filters for image statistics, combining images, matrix decomposition

---

# ReplayKit
- Screen capture and back camera support

---

# Multipath TCP
- Use multiple interfaces (Wi-fi, Cellular) for a single data stream
- See: https://tools.ietf.org/html/rfc6824

^ Multipath = Going through wifi and cell in a single request? Supported now through NSUrlConnection?

---

# DNS Proxy
- A new Network App Extension

---

# Hotspot Configuration
- A new network extension to configure hotspots

^ Programmatically configure hotspots via API.

---

# Core Motion
- Find the heading of a device

---

# Core Bluetooth
- L2CAP Channels
- Session restoration to handle device resets or restarting

---

# Core NFC
- Ability to read Near Field Communication tags and data

---

# Apple Pay
- PKPaymentError
- PKPaymentRequest and PKContactField for contact information
- supported countries
- Payment is provisioned inside the app

^ Payment information can include the countries that you support

---

# In-App Purchases
- Up to 20 in-app purchases can be promoted
- New method in SKPaymentTransactionObserver for promoted in-app purchases

^ What is a promoted IAP?

---

# HomeKit
- Time-based conditions for triggers (e.g. sunrise, sunset)
- HMCharacteristicThresholdRangeEvent can be used to trigger an event based on, for example, current temperature
- HMPresenceEvent can trigger based on the presence or absence of a user
- HMEventTrigger can also enable multiple recurrences

---

# Barcode Support
- Barcode support with binary content in AVFoundation, Core Image, SiriKit
- CIBarcodeDescriptor added to CoreImage
- Camera barcode (QR Code) reader

^ What’s really new here? Support for generating / recognizing more types of barcodes? Siri? Payments? Linking information? Camera support also.

---

# Core Image
- A new type of CoreImage kernel for blending images
- init(functionName:fromMetalLibraryData:) for using Metal in a CIKernal
- CIRenderDestination allows different destinations for rendering (CVPixelBuffer, Open GL texture, Metal, memory, etc.)

---

# High Efficiency Video Coding and High Efficiency Image Format
- HEVC, HEIF
- New image and video formats are used on the device
- Support is added to ImageIO, AVFoundation, CoreImage, PhotoKit

---

# Depth Data in Images
- iPhone 7+
- AVFoundation added more support for depth information
- Streaming Depth API (video)

---

# Live Photos
- More adjustments are possible (e.g. loop and bounce)

---

# Live messages
- MSMessageLiveLayout
- Can show dynamic content, such as games

---

# MapKit
- mutedStandard emphasizes developer data
- More customizable annotation collisions

^ Emphasis between custom app data and standard Apple Maps data

---

# APFS

^ Apple File System
^ iOS, macOS, tvOS, and watchOS
^ Replaces HFS+ as the default file system for iOS 10.3 and later, and macOS 10.13 and later.

---

# Automatic Storage Management
- The system can automatically delete unneeded downloads

---

# Browse local and iCloud documents (or third-party storage services)
- UIDocumentBrowserViewController
- UIDocumentBrowserTransitionController
- FileProvider and FileProviderUI can be used for third-party services

^ Access to other app’s documents directory

---

# Available Storage API
- volumeAvailableCapacityForImportantUsageKey  
- volumeAvailableCapacityForOpportunisticUsageKey

^ Downloading - do I have enough room to store this or not?

---

# PDFKit, Export to PDF

---

# App Store Changes

- New iOS Product Page
- App subtitles (30 chars)
- Up to 3 app previews
- Promoting IAPs

^ IAP promotion in product page

---

# Phased release
- All user immediately, or
- 7 day delivery distribution
- 1%, 2%, 5%, 10%, 20%, 50%, 100%

---

# TestFlight
- Multiple build distribution
- Testing groups
- Groups for development cycle (alpha, beta, release candidate)
- More testers - 2,000 now; up to 10k later this year

---

# macOS High Sierra
- 64 bit support

^ MacOS 64-bit application requirements - High Sierra last MacOS release to support 32-bit apps without compromises
^ January 2018 All new app submissions
^ June 2018 All apps and app updates

---

# watchOS 4
- CoreML, SiriKit, HomeKit changes (same as iOS)

---

# Apple TV
- Amazon Prime Video
- Right-to-left language support
- TVML Web Inspector

^ Apple has finally agreed to bring Amazon Prime Video to its Apple TV streaming box.

---

# Call for Presentations

- Four-Slides / Four-Minutes Format

- SiriKit, Speech Recognition, etc. We would like to see demonstrations of some of the new Apple technologies. Code samples, what it looks like, etc.

---

# Video Team

- We are looking for one more person to help record the meetup.

---

# Other Topics?

---

# Is anyone looking to hire?

---

# Is anyone looking for work?

---

![inline 100%](voyage-group-logo.png)

# Thanks!

---

# Other Questions / Comments

---

# Connect

- Twitter: @tokyoiosmeetup
- Facebook: Tokyo iOS Meetup
- YouTube: https://www.youtube.com/channel/UCqToSMJJrfsVjeQ9ATyu74Q
- Slack: https://tokyo-ios-meetup-slack-signup.herokuapp.com

# Contribute

tokyo-ios-meetup (github)
