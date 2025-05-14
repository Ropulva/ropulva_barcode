# Ropulva Barcode

C++_ZXing library is a high-performance Flutter plugin for scanning and generating QR codes and barcodes

---

## Install

ropulva_barcode:
    path: ./ropulva_barcode

git clone --recurse-submodules https://github.com/Ropulva/ropulva_barcode.git

---

## Demo Screenshots

<p align="center">
  <img alt="Scanner Screen" src="https://user-images.githubusercontent.com/11523360/222677044-a15841a7-e617-44bb-b3a0-66b2d5b57dce.png" width="240">
  <img alt="Creator Screen" src="https://user-images.githubusercontent.com/11523360/222677058-60a676fd-c229-4b51-8780-f40155cb5db6.png" width="240">
</p>
<p align="center">
  <i>Left: Barcode Scanner, Right: QR Code Creator</i>
</p>

---

## Features

- Scan QR codes and barcodes from the camera stream (on mobile platforms only), image file, or URL.
- Scan multiple barcodes at once from the camera stream (on mobile platforms only), image file, or URL.
- Generate QR codes with customizable content and size.
- Return the position points of the scanned barcode.
- Customizable scanner frame size and color, and the ability to enable or disable features like torch and pinch to zoom.

---

## Supported Formats

| Linear product | Linear industrial | Matrix             |
|----------------|-------------------|--------------------|
| UPC-A          | Code 39           | QR Code            |
| UPC-E          | Code 93           | Micro QR Code      |
| EAN-8          | Code 128          | rMQR Code          |
| EAN-13         | Codabar           | Aztec              |
| DataBar        | DataBar Expanded  | DataMatrix         |
|                | ITF               | PDF417             |
|                |                   | MaxiCode (partial) |

---

## Supported Platforms

| Platform   | Status               | Notes                                     |
|------------|----------------------|-------------------------------------------|
| Android    | ✅ Fully Supported   | Minimum API level 21                      |
| iOS        | ✅ Fully Supported   | Minimum iOS 11.0                          |
| MacOS      | ⚠️ Beta              | Without Camera support                    |
| Linux      | ⚠️ Beta              | Without Camera support                    |
| Windows    | ⚠️ Beta              | Without Camera support                    |
| Web        | ❌ Not Supported     | Dart FFI is not available on the web      |

> Note: Flutter ZXing relies on the Dart FFI feature, making it unsupported on the web. Camera-based scanning is only available on mobile platforms.