autoscale: true

![inline](logo.png)

11:00 am - 11:15 am: Introduction
11:15 am - 11:45 am: Daisuke Nagata will present "iOS Machine Learning."
11:45 am - 12:15 pm: Nick Janssen will present "Laska: A visual editor to create user interfaces for apps"
12:15 pm - 1:00pm: Discussion

---

# Tokyo iOS Meetup
## February 2018

---

# Greet someone near you.

---

# ...

---

# HomePod

---

# iOS 11 Adoption Reaches 65%
- (Compared to 75% for iOS 10 at the same time last year)

---

# Swift 4.1

- Synthesized conformance to `Equatable`

```swift
struct Person: Equatable {
  static func == (lhs: Person, rhs: Person) -> Bool {
    return lhs.firstName == rhs.firstName &&
           lhs.lastName == rhs.lastName &&
           lhs.birthDate == rhs.birthDate &&
           ...
  }
}

struct Person: Equatable {}
```

Taken from SE-0185

---

# Swift 4.1

- Conditional conformances

```swift
extension Array: Equatable where Element: Equatable {
  static func ==(lhs: Array<Element>, rhs: Array<Element>) -> Bool { ... }
}
```

Taken from SE-0143

---

# Other Topics?

---

# try Swift! Tokyo 2018

- March 1st and 2nd
- Workshops on March 3rd
- __Needs volunteers__:  https://docs.google.com/forms/d/e/1FAIpQLScWLgP7l3e3qWS85HNa4FdCGyV7bBBS3smZ4MnbpxYo59M8ww/viewform

https://www.tryswift.co/events/2018/tokyo/en

![](RikoCircle1000.png)

---

# Upcoming

March 4th

- Presentations (2)
- Post try! Swift meetup, we prioritize people from out of town

April 14th

- Presentations (2)

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
