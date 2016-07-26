# MotionStreetView

Google Street View for iOS with device motion sensors control.
Adds an extension for `GMSStreetView` that makes the camera follow the device's orientation / rear camera face direction.

[![CI Status](http://img.shields.io/travis/ML/MotionStreetView.svg?style=flat)](https://travis-ci.org/ML/MotionStreetView)
[![Version](https://img.shields.io/cocoapods/v/MotionStreetView.svg?style=flat)](http://cocoapods.org/pods/MotionStreetView)
[![License](https://img.shields.io/cocoapods/l/MotionStreetView.svg?style=flat)](http://cocoapods.org/pods/MotionStreetView)
[![Platform](https://img.shields.io/cocoapods/p/MotionStreetView.svg?style=flat)](http://cocoapods.org/pods/MotionStreetView)

## Example

To run the example project, clone the repo, and run `pod install` from the Example directory first.

## Requirements

## Installation

MotionStreetView is available through [CocoaPods](http://cocoapods.org). To install
it, simply add the following line to your Podfile:

```ruby
pod "MotionStreetView"
```

## Usage
* Wherever your `GMSStreetView` is, call `startMotion()` to start camera motion update.
* To stop motion follow, call `stopMotion()`.

Example:
```
let myStreetView : GMSStreetView = GMSStreetView()
myStreetView.startMotion()

```
## Author

ML, 7mllm7@gmail.com

## License

MotionStreetView is available under the MIT license. See the LICENSE file for more info.
