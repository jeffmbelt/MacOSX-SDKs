# MacOSX-SDKs

A collection of those pesky SDK folders.  Compiled from various releases of Xcode.

# Extrat Using Homebrew

``` bash
$ brew install xz
$ xz -d to-extract.xz
```

Extract these archives to '/Applications/Xcode.app/Contents/Developer/Platforms/MacOSX.platform/Developer/SDKs/'

# Important

Modern versions of Xcode (7.3+) need you to edit the `MinimumSDKVersion` in this file to use older SDKs:

`/Applications/Xcode.app/Contents/Developer/Platforms/MacOSX.platform/Info.plist`
# Note

Please ensure you have read and understood first the [Xcode license terms](https://www.apple.com/legal/sla/docs/xcode.pdf).
