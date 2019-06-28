# @titanium/barcode

![https://www.npmjs.com/package/@titanium/barcode](https://img.shields.io/npm/v/@titanium/barcode.png)


> Barcode Module for Titanium built on top of the ZXing library (Android) and AVFoundation (iOS).

- [📝 Description](#-Description)
- [🚀 Getting Started](#-Getting-Started)
	- [Using barcode scanner](#Using-barcode-scanner)
- [✨Features](#Features)
- [📚Learn More](#Learn-More)
- [📣 Feedback](#-Feedback)
- [©️ Legal](#️-Legal)


## 📝 Description

This is a repackaging of the compiled iOS and Android modules for [Ti.ImageFactory](https://github.com/appcelerator-modules/ti.barcode) to allow for installation via npm.

## 🚀 Getting Started

1. Install `@titanium/barcode` in root of project

```
npm install @titanium/barcode
```

### Using barcode scanner

```
const barcode = require('ti.barcode');

barcode.allowRotation = true;
barcode.displayedMessage = ' ';
barcode.allowMenu = false;
barcode.allowInstructions = false;
barcode.useLED = true;

barcode.addEventListener('success', function(e) {
    console.info('Success called with barcode: ' + e.result);
});

barcode.capture({
	animate: true,
	overlay: overlay,
	showCancel: false,
	showRectangle: false,
	keepOpen: true,
});
```

## ✨Features

iOS: `ti.barcode 2.0.4`
Android: `ti.barcode 4.0.2`


## 📚Learn More

- [Ti.Barcode GitHub Repo](https://github.com/appcelerator-modules/ti.barcode)

## 📣 Feedback

Have an idea or a comment?  [Join in the conversation here](https://github.com/brentonhouse/titanium-barcode/issues)! 

## ©️ Legal

Modules are licensed under Apache 2.0 from https://github.com/appcelerator-modules/ti.barcode

Alloy is developed by Appcelerator and the community and is Copyright © 2012-Present by Appcelerator, Inc. All Rights Reserved.

Alloy is made available under the Apache Public License, version 2. See their license file for more information.

Appcelerator is a registered trademark of Appcelerator, Inc. Titanium is a registered trademark of Appcelerator, Inc. Please see the LEGAL information about using trademarks, privacy policy, terms of usage and other legal information at http://www.appcelerator.com/legal.