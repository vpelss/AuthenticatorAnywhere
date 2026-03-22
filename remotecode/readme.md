# About

Chrome extentions have set CORS to not allow remote code execution. So we need local copies

Sources:

- https://cdnjs.cloudflare.com/ajax/libs/scrypt-js/3.0.1/scrypt.js
- https://cdn.jsdelivr.net/gh/davidshimjs/qrcodejs@gh-pages/qrcode.min.js
- https://unpkg.com/html5-qrcode@2.3.8/html5-qrcode.min.js


CSS:

- https://cdn.simplecss.org/simple.css

  // EXTERNAL USED CODE
//svg images from https://fonts.google.com/

// scrypt from https://www.jsdelivr.com/package/npm/scrypt-js
// https://github.com/ricmoo/scrypt-js/

// qr code creator
// USING : https://davidshimjs.github.io/qrcodejs : 34 kb requires div
// https://cdnjs.com/libraries/qrcode/1.4.4 : 340 kb requires canvas

// scan qr code from camera
// USING : https://github.com/mebjas/html5-qrcode
// https://unpkg.com/html5-qrcode@2.3.8/html5-qrcode.min.js
// 366 kb
// https://github.com/nimiq/qr-scanner
// https://nimiq.github.io/qr-scanner/qr-scanner.umd.min.js
// 60 kb
// https://developer.mozilla.org/en-US/docs/Web/API/Barcode_Detection_API
// ?? poor browser support

concatenate Uint8arrays : https://evanhahn.com/the-best-way-to-concatenate-uint8arrays/

template() :  // https://stackoverflow.com/questions/377961/efficient-javascript-string-replacement

beep() : // https://stackoverflow.com/a/29641185
