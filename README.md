# tiny
the mini npm module

Removes all spaces from a string.
Install

$ npm install @kazihar/tiny

# Usage

const tiny = require("@kazihar/tiny");

tiny("So much space!");
//=> "Somuchspace!"

tiny(1337);
//=> Uncaught TypeError: Tiny wants a string!
//    at tiny (<anonymous>:2:41)
//    at <anonymous>:1:1
