Knowledge bank and hacks
================

Collections of HTML email knowledge bank and hacks that works and been tested on Litmus and my own devices.

## Outlook desktop

All Outlook desktop versions (Windows versions) and Lotus8 ignoring cellspacing value. No point to use them, better use nested table to create some space between elements.

After some more testing it seems that this is Internet Explorer issue. AOL, Gmail and Outlook.com ignoring cellspacing value only on Internet Explorer browser, but not Yahoo Mail.

## Outlook.com p margin

Outlook.com adding *margin-bottom:1.35em* to every paragraph tag. So we will force Outlook to change this by adding this rule to our style block:

```css
.ExternalClass p {Margin-bottom:0 !important;}
```
Note
Margin should be capitalize, otherwise it will not work.

##Remove blue links in iOS

Fix automatic styling of auto-generated blue-lnks on Apple devices such as iPhone

Copy paste this small piece of code below in your style tag, both above and inside your @media query and that's it!

```css
a[x-apple-data-detectors] {
    color: inherit !important;
    text-decoration: none !important;
    font-size: inherit !important;
    font-family: inherit !important;
    font-weight: inherit !important;
    line-height: inherit !important;
}
```

*Courtesy of [removebluelinks.com](http://removebluelinks.com)*

##Gmail App Zooming

Stop Gmail app from zooming text

```
    style="min-width:600px"
```

*Courtesy of [Chriss Wise](http://chriswi.se/)*

##Gmail App p margin

Stop Gmail App from adding margin-top and margin-bottom

```
    margin:0px;
```

##Gmail white line under image

To stop appear white line below image add `display:block` to image styles

##Windows Phone address blue colour

Any ideas?


