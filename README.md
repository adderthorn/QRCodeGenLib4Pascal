# QRCodeGenLib4Pascal [![License](http://img.shields.io/badge/license-MIT-green.svg)](https://github.com/Xor-el/QRCodeGenLib4Pascal/blob/master/LICENSE)
QRCodeGenLib4Pascal is a Delphi/FPC Port of [Fast-QR-Code-generator](https://github.com/nayuki/Fast-QR-Code-generator/) written by [Nayuki](https://github.com/nayuki). It provides an easy to use interface for generating QR Codes.

**Build Status**
[![Build Status](https://travis-ci.org/Xor-el/QRCodeGenLib4Pascal.svg?branch=master)](https://travis-ci.org/Xor-el/QRCodeGenLib4Pascal)

Features
--------

Core features:

* Supports encoding all 40 versions (sizes) and all 4 error correction levels, as per the QR Code Model 2 standard
* Output formats: Raw modules/pixels of the QR symbol, SVG XML string/file, `ImageObject`(`bmp`, `jpg` and `png`).
* Encodes numeric and special-alphanumeric text in less space than general text
* Open source code under the permissive MIT License

Manual parameters:

* User can specify minimum and maximum version numbers allowed, then library will automatically choose smallest version in the range that fits the data
* User can specify mask pattern manually, otherwise library will automatically evaluate all 8 masks and select the optimal one
* User can specify absolute error correction level, or allow the library to boost it if it doesn't increase the version number
* User can create a list of data segments manually and add ECI segments

**Supported Compilers**
 
    FreePascal 3.0.0 and Above.
    
    Delphi XE3 and Above.

**Installing the Library.**

**Method One:**

 Use the Provided Packages in the "Packages" Folder.

**Method Two:**

 Add the Library Path and Sub Path to your Project Search Path.

**Demos**

 Check out the `QRCodeGenLib.Demo` folder.

**License**

This "Software" is Licensed Under  **`MIT License (MIT)`** .

#### Tip Jar
* :dollar: **Bitcoin**: `1MhFfW7tDuEHQSgie65uJcAfJgCNchGeKf`
* :euro: **Ethereum**: `0x6c1DC21aeC49A822A4f1E3bf07c623C2C1978a98`
* :pound: **Pascalcoin**: `345367-40`
