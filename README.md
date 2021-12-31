# Hyundai Spring 2016 Quarterly Coupon Mailer
These are emails for Hyundai's Spring 2016 QCM (Quarterly Coupon Mailer).  Included is the standard eblast (in English and Spanish) and one for  luxury car (premium) owners. Using "variable data" provided by Hyundai, these emails are customized coupon offers to entice customers to visit their local dealership.


## Links to Templates
[Standard (En)][src1] * [Standard (Span)][src2] * [Premium][src3]

  [src1]: https://webdevjoshb.github.io/Hyundai-Spring-2016-QCM/standard-english.html
  [src2]: https://webdevjoshb.github.io/Hyundai-Spring-2016-QCM/standard-spanish.html
  [src3]: https://webdevjoshb.github.io/Hyundai-Spring-2016-QCM/premium.html


## Responsive Layouts 
To view responsive layouts, there are three options: 
1. Manually resize the width of the browser
2. Use the browser's native DevTools to simulate other screensizes and devices.
3. View screenshots of each template at various screen widths.


### 1. Manually resize the browser's width 
Brief instructions to follow.


### 2. DevTools 
To open DevTools on all browsers, press `F12` or `Control+Shift+I` (Windows, Linux) or `⌘+Option+I` (macOS). Note that simulations give an approximation of the mobile/device user experience from a laptop or desktop using a web browser; it is not an exact replication.

Instructions:
[Chrome Devtools][Chrome] * [Firefox DevTools][Firefox] * [Microsoft Edge DevTools][Edge] * [Safari DevTools][Safari]

  [Chrome]: https://developer.chrome.com/docs/devtools/device-mode/#viewport
  [Firefox]: https://developer.mozilla.org/en-US/docs/Tools/Responsive_Design_Mode
  [Edge]: https://docs.microsoft.com/en-us/microsoft-edge/devtools-guide-chromium/device-mode/#simulate-a-mobile-viewport
  [Safari]: https://support.apple.com/guide/safari-developer/simulate-responsive-web-content-apple-devices-dev84bd42758/11.0/mac/10.13


### 3. Screenshots 
For perhaps quicker access, the following are screenshots of each template at various screen widths. Note: 

| Standard (En)         | Standard (Span)       | Premium             | 
|-----------------------|-----------------------|---------------------|
| [320px][en320]        | [320px][sp320]        | [320px][pre320]     |
| [480px][en480]        | [480px][sp480]        | [480px][pre480]     |
| [600px][en600]        | [600px][sp600]        | [600px][pre600]     |
| [768px][en768]        | [768px][sp768]        | [768px][pre768]     |
| [1024px][en1024]      | [1024px][sp1024]      | [1024px][pre1024]   |

  [en320]: https://webdevjoshb.github.io/Hyundai-Spring-2016-QCM/screenshots/standard/320px.png
  [en480]: https://webdevjoshb.github.io/Hyundai-Spring-2016-QCM/screenshots/standard/480px.png
  [en600]: https://webdevjoshb.github.io/Hyundai-Spring-2016-QCM/screenshots/standard/600px.png
  [en768]: https://webdevjoshb.github.io/Hyundai-Spring-2016-QCM/screenshots/standard/768px.png
  [en1024]: https://webdevjoshb.github.io/Hyundai-Spring-2016-QCM/screenshots/standard/1024px.png
  [sp320]: https://webdevjoshb.github.io/Hyundai-Spring-2016-QCM/screenshots/spanish/320px.png
  [sp480]: https://webdevjoshb.github.io/Hyundai-Spring-2016-QCM/screenshots/spanish/480px.png
  [sp600]: https://webdevjoshb.github.io/Hyundai-Spring-2016-QCM/screenshots/spanish/600px.png
  [sp768]: https://webdevjoshb.github.io/Hyundai-Spring-2016-QCM/screenshots/spanish/768px.png
  [sp1024]: https://webdevjoshb.github.io/Hyundai-Spring-2016-QCM/screenshots/spanish/1024px.png
  [pre320]: https://webdevjoshb.github.io/Hyundai-Spring-2016-QCM/screenshots/premium/320px.png
  [pre480]: https://webdevjoshb.github.io/Hyundai-Spring-2016-QCM/screenshots/premium/480px.png
  [pre600]: https://webdevjoshb.github.io/Hyundai-Spring-2016-QCM/screenshots/premium/600px.png
  [pre768]: https://webdevjoshb.github.io/Hyundai-Spring-2016-QCM/screenshots/premium/768px.png
  [pre1024]: https://webdevjoshb.github.io/Hyundai-Spring-2016-QCM/screenshots/premium/1024px.png


## To Do ##
Stream-of-conscious ideas.

* Refine intro details.
  * Why code redundancies (internal and inline CSS, user agent/device code compatibility, progressive enhancement, etc.)
  * QA and Testing (Litmus, etc.)
  * Spanish translation
* Provide ways to view responsive layouts
  _Can't assume everyone knows how to use DevTools_
  * Explore possible ways to do this. Options/Thoughts:
    * Find/embed an out-of-the-box solution that already does this
    * Create custom page resizer to simulate various mobile device viewports/layouts
    * Provide instructions to open Device Toolbar in various browsers
    * Make screencast to quickly demo how to use Device Toolbar
  * Cleaner screenshot interface
* Discuss features
  * Background images (if used)
  * Web fonts and fallbacks (if used)
  * Art direction, image resolutions at various breakpoints (if applicable)
  * Toggling panels when viewing on Apple devices
* Detail any challenges and their solutions
  * File size
  * Background images, gradients
  * Responsive images, art direction
  * Variable data and layout problems
    * URL lengths
  * Responsive design layouts
  * Gmail-specific issues
    * File size truncation
    * Layouts not full-width
    * Gmail Apps for Non-Google Accounts (GANGA)
* Any improvements I would make ("If I had more time", What I'd do now versus when originally coded, etc.)
  * Design
    * Content "above the fold"
      * Call to Action (CTA)
      * Banner heights spaning entire viewport
  * Responsive (hard-coded breakpoints versus flexible width)
    * Image optimization
    * Art direction, resolution, etc.
  * Email length (novel length content...scroll and scroll and scroll...)
* Anything else?