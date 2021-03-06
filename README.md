![](art/header.png)

<p float="center">
 	<img src="art/gifs/01.gif" width=33%>
	<img src="art/gifs/02.gif" width=33%>
	<img src="art/gifs/03.gif" width=33%>
</p>

**BouncyLayout** is a collection view layout that makes your cells bounce.

## Features

- [X] Pure Swift 5.
- [X] Works with every `UICollectionView`.
- [X] Horizontal and vertical scrolling support.
- [X] Configurable bounce effect.
- [X] Supports cell size changes

## Setup
The only you thing you need to do is import `BouncyLayout`, create an instance and add it to your `UICollectionView`.
```swift
import BouncyLayout
```
```swift
let layout = BouncyLayout()
```
```swift
UICollectionView(frame: .zero, collectionViewLayout: layout)
```

##### Find the above displayed examples in the `example` folder.

## Installation

### CocoaPods

BouncyLayout is available through [CocoaPods](http://cocoapods.org). To install
it, simply add the following line to your Podfile:

```ruby
pod "BouncyLayout"
```

### Carthage

BouncyLayout is available through [Carthage](https://github.com/Carthage/Carthage). To install
it, simply add the following line to your Cartfile:

```
github "roberthein/BouncyLayout"
```

### Swift Package Manager

BouncyLayout is available through [Swift Package Manager](https://swift.org/package-manager/). To install
it, in Xcode 11.0 or later select `File` > `Swift Packages` > `Add Package Dependency...` and add BouncyLayout repository URL:
```
https://github.com/roberthein/BouncyLayout.git
```

## Suggestions or feedback?

Feel free to create a pull request, open an issue or find me [on Twitter](https://twitter.com/roberthein).
