# Cookie Info Banner (DSGVO / GDPR)

A cookie info banner with DSGVO standard

## Options

|Option|Description|
|:-------------|:----------|
|data-font-size|Text size (Message and link)|
|data-font-family|Font family  (Message and link)|
|data-text-align|Position (text)|
|data-height|Banner height|
|data-fg|Banner text color|
|data-bg|Banner background color|
|data-link|Link text color|
|data-divlink|Button text color|
|data-divlinkbg|Button background color|
|data-position|Banner position (top or bottom)|
|data-message|Message text|
|data-linkmsg|Link text|
|data-moreinfo|Where the visitor can read more about cookies (default: https://wikipedia.org/wiki/HTTP_cookie)|
|data-close-text|The text/symbol for the close button|
|data-effect|Effect to use|
|data-cookie|Name for the cookie (Store the cookiebanner acceptance information)|
|data-expires|Cookie expiry date/time|
|data-cookie-path|Path to set for the cookie|
|data-mask|Creating a mask over the viewport (Clicking anywhere on the mask is considered as acceptance.)|
|data-mask-opacity|Opacity to use for the window mask|
|data-mask-background|Optional: Background style (apply to the mask)|
|data-zindex|z-index to set on the notice (If mask is used, the notice's z-index is automatically incremented by 1 so it appears above the mask)|
|data-accept-on-scroll|When is set true window scrolling is considered as acceptance.|
|data-tracking|Tracking pixel (Example: http://www.yourdomain.com/tracking.php?pixel)|

## Example

### Default

```javascript
<script type="text/javascript" id="cookieinfo" src="//cookieinfoscript.com/js/cookieinfo.min.js"></script>
```

### Custom

```javascript
<script type="text/javascript" id="cookieinfo" src="//cookieinfoscript.com/js/cookieinfo.min.js" data-cookie="my-cookie-banner" data-close-text="Got it!" ></script>
```