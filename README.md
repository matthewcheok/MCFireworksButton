MCFireworksButton
=====================

Drop-in button control with with particle effects similar to the Like button in Facebook Paper.


##Screenshot
![Screenshot](https://raw.github.com/matthewcheok/MCFireworksButton/master/screenshot.gif "Example of MCFireworksButton")

## Installation

Add the following to your [CocoaPods](http://cocoapods.org/) Podfile

    pod 'MCFireworksButton'

or clone as a git submodule,

or just copy files in the ```MCFireworksButton``` folder into your project.

## Using MCFireworksButton

Simply call methods `-animate` to begin the particle effect.

    [self.likeButton animate];

Some basic bounce animations are included for convenience.

    [self.likeButton popInsideWithDuration:0.4];

or

    [self.likeButton popOutsideWithDuration:0.5];

## Configuration

You can specify the particle texture and scales to be used in the particle effect:

    self.likeButton.particleImage = [UIImage imageNamed:@"Sparkle"];
    self.likeButton.particleScale = 0.05;
    self.likeButton.particleScaleRange = 0.02;

Alternatively you can use `MCFireworksView` directly if you don't need UIButton functionality.

## License

MCNumberLabel is under the MIT license.
