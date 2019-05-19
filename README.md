# QLColorCode

[![Build Status](https://travis-ci.org/anthonygelibert/QLColorCode.svg?branch=master)](https://travis-ci.org/anthonygelibert/QLColorCode)

**Original project:** <http://code.google.com/p/qlcolorcode/>  
**Github repository:** <https://github.com/anthonygelibert/QLColorCode>

# Added or Modified part in this branch.
**This code is tested on macOS Mojave(10.14.5, xcode 12.1) only. Because the purpose of this branch is to resolve weird icon thumbnail issue in macOS Mojave.**

- Resolve weird thumbnail icon appearance in macOS Mojave

    Code for generating preview and thumbnail presentation part,  I borrowed it from below repositories.  
    **QLSwift** <https://github.com/lexrus/QLSwift.git>  
    **QLStephen** <https://github.com/whomwah/qlstephen.git>


- Support Mojave Dark mode

    Setting the thumbnail color style when system dark mode is on  (default is `darkplus`):

        defaults write org.n8gray.QLColorCode darkTheme darkplus

    Setting the thumbnail color style when system darkmode is off  (default is `edit-xcode`):

        defaults write org.n8gray.QLColorCode lightTheme edit-xcode

- Remove unused framework references.

- Change preview window size

- Add support Crystal language (@crjaensch)
