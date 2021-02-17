# LKFeedbackGen

Will let you to handle iOS device feedback mechanism easily by automatically invoke Hapics/Taptic signals based on single call.


## Installation

### Swift Package Manager

**File / Swift Packages / Add Package Dependency...** and enter package repository URL: ```https://github.com/lalkrishna/LKFeedbackGenerator``` and follow the instructions.

### Manually
Clone the repo and Drag and drop to your project (it will be added as a package)
OR
You can just copy the file: Sources/LKFeedbackGen/[LKFeedbackGen.swift](https://github.com/lalkrishna/LKFeedbackGeneratorr/blob/main/Sources/LKFeedbackGen/LKFeedbackGen.swift "LKFeedbackGen.swift")


## Usage

**1.** Import LKFeedbackGen in proper place.
```swift
import LKFeedbackGen
```

**2.** Call feedback
```swift
LKFeedbackGen.signal(HapticSignal)
```

**HapticSignal**
```swift
case selection, light, medium, heavy, success, warn, error, cancelled
```

example:
```swift
LKFeedbackGen.signal(.selection)
```


## Features

- [x] Easy to use
- [x] Simple Swift syntax
- [x] Lightweight readable codebase

## ❤️ Contributing
This is an open source project, so feel free to contribute. How?
- Open an [issue](https://github.com/lalkrishna/LKFeedbackGenerator/issues/new).
- Send feedback via [email](mailto:lalkrishna@live.com).
- Propose your own fixes, suggestions and open a pull request with the changes.

## Author

Lal Krishna
[Twitter](http://www.twitter.com/itzme_lal)
