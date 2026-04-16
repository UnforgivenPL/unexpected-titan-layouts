# Unexpected Titan Layouts
Custom layouts for Unexpected Keyboard that work well with Titan2's physical keyboard.

# Disclaimer
This repository and the files within are **not** endorsed by Unihertz (the producer of [Titan 2](https://www.unihertz.com/products/titan-2?variant=46647193043183)) or by Julow (the maintainer of wonderful [Unexpected Keyboard](https://github.com/Julow/Unexpected-Keyboard/tree/master)).

All trademarks are used for informational purposes only and are the property of their respective owners.

The layouts in this repository are provided "as is", without any warranty, liability or fitness for purpose. Use them at your own risk.

# Prerequisites

1. A phone with a physical keyboard.
1. [Unexpected Keyboard](https://f-droid.org/packages/juloo.keyboard2/) installed. If you use Android and if you care about open source, please use [F-Droid](https://www.f-droid.org) and let people know about how a company that used to **do no evil** is [closing the Adroid ecosystem](https://keepandroidopen.org).
1. Unexpected Keyboard enabled as input source. Ideally, it is the only input source on your phone.
1. In the phone's physical keyboard settings the option to always show on-screen keyboard is **turned on**.

# Usage

1. Open any layout xml file in this repository (check the `layouts` directory) using your phone's browser.
1. Copy its contents to clipboard.
1. Open Unexpected Keyboard's settings.
1. Add a custom layout and into the editor paste the contents of the clipboard.
1. Repeat steps 1.-4. until you have enough layouts for all your use cases.

# How does it work?

Titan 2 is a great phone with a great keyboard, but the support for input languages is very limited. However, it allows showing on-screen keyboards at the bottom of the screen.

Unexpected Keyboard allows custom layouts, i.e. layouts with less or more keys than usual. In this case the keyboard only shows characters that are **not** available directly on the physical keyboard. This means that there is an additional row of virtual keys directly above the keyboard, very easy to reach and easy to operate.

# Contributing

Feel free to make PRs to this repository with your custom layouts. You can use [this excellent editor by lixquid](https://unexpected-keyboard-layout-editor.lixquid.com).

Some guidelines:
* all layouts have 10 keys, 9 of which contain letters;
* the leftmost key allows cycling through layouts, accessing config and the clipboard (this must be the same in all layouts);
* lowercase version of a letter is in the centre, uppercase version is at the top;
* bottom row of sub-keys contains various characters and utilities and ideally should be the same for all layouts (but it is not required).
