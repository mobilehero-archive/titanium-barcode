
<a href="https://brenton.house/saying-goodbye-to-axway-amplify-titanium-31a44f3671de">
	<h1 align="center">
	🪦 RIP Axway Amplify Titanium (2010 - 2022)
	</h1>
</a>
<a href="https://brenton.house/saying-goodbye-to-axway-amplify-titanium-31a44f3671de">
	<p align="center">
		<img src="https://cdn.secure-api.org/images/RIP-Axway-Amplify-Titanium.png" alt="RIP Axway Amplify Titanium (2010 - 2022)" width="80%" />
	</p>
</a>
<a href="https://brenton.house/saying-goodbye-to-axway-amplify-titanium-31a44f3671de">
	<p align="center">
		🪦 &nbsp; RIP Axway Amplify Titanium (2010 - 2022)
	</p>
</a>
<p>&nbsp;</p>
<a href="https://brenton.house/saying-goodbye-to-axway-amplify-titanium-31a44f3671de">
	<h2 align="center">
		🛑 This project is no longer being maintained 🛑
	</h2>
</a>
<p>&nbsp;</p>
<hr>
<p>&nbsp;</p>
<p>&nbsp;</p>

# @titanium/barcode

[![@titanium/barcode](https://img.shields.io/npm/v/@titanium/barcode.png)](https://www.npmjs.com/package/@titanium/barcode)
[![Dependabot Status](https://api.dependabot.com/badges/status?host=github&repo=brentonhouse/titanium-barcode)](https://dependabot.com)


> Titanium native mobile barcode module built on top of the ZXing library (Android) and AVFoundation (iOS)

* [📝 Description](#-description)
* [🚀 Getting Started](#-getting-started)
	* [Using barcode scanner](#using-barcode-scanner)
* [✨Features](#features)
* [📚Learn More](#learn-more)
* [📣 Feedback](#-feedback)
* [©️ Legal](#️-legal)


## 📝 Description

This is a repackaging of the compiled iOS and Android modules for [ti.barcode](https://github.com/appcelerator-modules/ti.barcode) to allow for installation via npm.

## 🚀 Getting Started

1. Install `@titanium/barcode` in root of project

```
npm install @titanium/barcode
```

### Using barcode scanner

```javascript
const barcode = require('@titanium/barcode');

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