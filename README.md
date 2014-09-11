AQSIBInstantiator
=================

Instantiate views from conventional named Nib, Storyboard.

```objc
SomeView *someView = [SomeView loadFromNib]; // Will load from `SomeView.xib`
```

```objc
SomeViewController *someViewController = [SomeViewController loadFromMainStoryboard]; // Will load from `Main.storyboard` with identifier: `SomeViewController`.
```

```objc
SomeViewController *someViewController = [SomeViewController loadFromStoryboard]; // Will load from `SomeViewController.storyboard` with identifier: `SomeViewController`.
```
