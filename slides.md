autoscale: true

![inline](logo.png)

11:00 am - 11:15 am: Introduction
11:15 am - 1:00 pm: WWDC Discussion

---

# Tokyo iOS Meetup
## June 2018

---

# Greet someone near you.

---

# ...

---

# Report from the Field

---

# WWDC Analysis

---

# Goals

- Understand the trends in our industry
- Become aware of what tools exist so that we can have creating new ideas about software develop

---

# Privacy and Security

---

# Privacy and Security
## Thinking As Users

- Are you using a password manager?
- What recommendations do you make about managing your passwords?

---

# Privacy and Security
## Thinking As Developers

- Are you involved in a project that has user accounts? If so, how to you protect your user data?

---

# Privacy and Security
## Problems with Passwords

- Users are hard to remember so users will reuse passwords between sites (or write them down)
- Websites, even large websites, are routinely hacked and those passwords are exposed (e.g. Yahoo!, LinkedIn)
- https://haveibeenpwned.com

---

# Privacy and Security

- Automatic Strong Passwords
- Autofill Credential Provider Extensions
- Security Code Autofill (Message will automatically detect and fill-in your security code) for Two-Factor Authentication
- `AuthenticationServices`

---

# Privacy and Security
## Analysis

![title](Screen%20Shot%202018-06-12%20at%2011.17.50.png)

- Apple is clearly positioning themselves as the platform for privacy and security to differentiate themselves from other tech companies (e.g. Google and Facebook)

---

# Tooling Improvements

---

# Tooling Improvements
## Instruments

- Do you use Instruments?
- What are some of your favorite tools inside of Instruments?

---

# Tooling Improvements
## Instruments

- os\_log / os_signpost - Similar to a print statement, but with the ability to integrate with Instruments
- Ability to create custom tools with Instruments

---

# Tooling Improvments
## Source Editing

- Besides XCode, what code editors do you use?
- What are some feature of those editors that you would like to see in XCode?

---

# Tooling Improvments
## Source Editing

- Speed improvements
- Improvement to SourceKit
- Improvements to Code Completion
- Improvement to Code Navigation (including a callers option)
- Source control change bar (shows what has been modified since the last version)
- Code folding with a ribbon
- Multi-cursor editing
- More support for git, include conflict resolution and support for rebase
- Integration with GitLab and BitBucket

---

# Tooling Improvements
## Refactoring

- Improvements to Swift refactoring
- New Build system introduced last year is now the default

---

# Tooling Improvements
## LLDB

- Does anyone have any favorite tricks for LLDB?

---

# Tooling Improvements
## LLDB

- Better access to variables
- Improvements to downloading debugger symbols
- Ability to see reports for energy issues

---

# Tooling Improvements
## Testing

- Improved Code Coverage (released in the spring)
- Randomize the order of tests
- Execute tests in parallel

---

![title](Screen%20Shot%202018-06-12%20at%2012.10.26.png)

---

# Tooling Improvements
## Swift Playgrounds

- New REPL-like interaction that do not require restarting the session

---

# Tooling Improvements
## Analysis

- Apple spent a lot of time discussing tooling improvements.
- One theme of the presentations is that everything is faster.  macOS is faster. iOS is faster. The developer tools are faster.
- There are fewer major releases this year because Apple is focusing on internal improvements.

---

# Swift

---

# Swift
## Swift 4.2

- Better performance
- Smaller Code Size
- Hashable improvements

---

# Swift
## Swift 5

- Swift will be part of the OS
- ABI stability

---

# Metal

- A11 Bionic chip (e.g. Apple also makes their own GPU hardware)
- OpenGL and OpenCL frameworks are being deprecated
- Metal Shader Profiler
- Metal System Trace
- Metal Shader Debugger
- Machine Learning acceleration (including a collaberation with TensorFlow)
- Ray Tracing acceleration
- GPU-driven command encoding

---

# Machine Learning

---

# Machine Learning

- Is anyone involved in a machine learning project?
- What frameworks are your using?

---

# Machine Learning
## Vision

- Face detection
- Facial landmarks
- People segmentation

---

# Machine Learning
## Natural Language

- Detect what language a sentence is
- Tokenize a sentence
- Determine a sentence's language parts
- Named Object Recognition

---

![title](Screen%20Shot%202018-06-12%20at%2012.19.10.png)

---

# Machine Learning
## Core ML 2

- Batch API
- Quantization (makes a model smaller)
- Support for Custom Models or Shapes

---

# Machine Learning
## Create ML

- Supports Features like Natural Language and Image Classification
- Algorithms (e.g. Support Vector Machines, Logisitic Regression)
- Data Processing
- Transfer Learning allows us to use a model that is bundled with the OS

---

# Machine Learning

- A lot of progress in machine learning seems to be about achieving the same results that were possible in the past, only faster.

---

# Network Framework

- Apple is creating a new network framework. Useful if you are doing UDP, TCP, and other lower-level networking.

---

# macOS Mojave

---

# macOS Mojave
# Features

- Dark Mode
- Desktop Stacks
- Quick Actions

---

# macOS
# Important Changes

- Last macOS to support 32-bit apps meaning that QuickTime, Java 1.6, and Carbon HLTB are deprecated
- Security (System Integrity Protection, protection against code injection, app notary service)

---

# macOS
## UIKit Coming to macOS

- Expected in 2019
- Underlying Frameworks are being rationalized
- Will be used in Home, Stocks, News, and Photos apps

---

# iOS 12

---

# iOS 12

- Photos app has new searching and sharing capabilities
- Stocks and Voice Messages are coming to iPad
- Animoji, Memoji in FaceTime
- Group FaceTime

---

# iOS 12
## Regarding Animoji / FaceTime

- This article suggests that people may be ignoring the popularity of Apple's Messages app with US Teens
- https://hackernoon.com/lets-face-reality-us-teens-may-engage-with-imessage-more-than-any-other-social-platform-f0c66cf6fc22

---

# iOS 12
## Focus

- Do Not Disturb
- Grouped Messages
- Activity Report

---

# iOS 12
## Regarding Focus

- There has been a great deal of focus on smart phone addiction in the media and the software industry.
	- https://www.nytimes.com/2018/01/17/well/family/is-your-child-a-phone-addict.html
	- https://medium.com/thrive-global/how-technology-hijacks-peoples-minds-from-a-magician-and-google-s-design-ethicist-56d62ef5edf3

---

# iOS 12
## Regarding Focus

- Do you use your smartphone more than you would like?
- Would you like the ability to limit you or your children's use of apps?

---

# iOS 12
## Siri

- Includes prediction (integrates with `NSUserActivity`)
- Use Shortcuts to have voice interaction with Siri in your app
- Includes interaction with HomePod
- Shortcuts can also work on the Watch

---

# iOS 12
## Siri

- How would you compare announcements related to Siri with other voice assistants? (e.g. Google Assistant or Amazon Alexa)

---

# Augmented Reality

- The USDZ file format for AR content

---

# Augmented Reality
## ARKit 2

- Improved face tracking (including gaze and tongue)
- Environment texturing
- Image detection and tracking (objects can stick to other objects in the real world)
- 3D Object Detection
- Persistent experiences (save and share information about a space)
- Shared experiences

---

# Apple Watch

---

# Apple Watch

- Who has an Apple watch?
- What types of things are you using it for?
- Are you developing apps for it?

---

# Apple Watch

- Workout Detection
- Walkie-talkie
- Background Audio

---

# Apple Watch

- Interactive Notifications
- Audio Background Mode
- Enhanced Workout Session

---

# MapKit JS

- Embed Apple Maps inside of your website

---

# MusicKit JS

- Play Apple Music songs inside of your JavaScript app

---


# Other Topics?

---

# Upcoming

June 16th

- WWDC Theme

July 21st

- Presentations (3)

August

- Presentations (1)

---

# Is anyone looking to hire?

---

# Is anyone looking for work?

---

![inline 100%](CyberAgent_logo.png)

---

# Connect

- Twitter: @tokyoiosmeetup
- Facebook: Tokyo iOS Meetup
- YouTube: https://www.youtube.com/channel/UCqToSMJJrfsVjeQ9ATyu74Q
- Slack: https://tokyo-ios-meetup-slack-signup.herokuapp.com
- Github: tokyo-ios-meetup
