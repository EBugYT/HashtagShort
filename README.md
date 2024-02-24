# HashtagShort - URL shortener written in plain JS
## Usage
### URL format
If you will put this in root you will use
```
yourwebsite.com/#shortcode
```

If you place it in a folder, like sh for example you will use
```
yourwebsite.com/sh#shortcode
```
### Setting shortcodes and redirect urls
For this you use the data.xml file. When you clone this repo it will look like this:
```xml
<?xml version="1.0" encoding="UTF-8"?>
<datalist>
    <url>
        <shortcode>google</shortcode>
        <rurl>//google.com</rurl>
    </url>
</datalist>
```
Add more urls with this format and change shortcode and redirect url (rurl).