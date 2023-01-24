# google-translator-with-css
Learn how to integrate google translator without showing the powered by google logo using css

#HTML CODE
place it were you want the language dropdown to show
```html
<div id="google_translate_element"></div>
```

#JAVASCRIPT CODE
place it were you want the language dropdown to show
```javascript
<script type="text/javascript">
function googleTranslateElementInit() {
  new google.translate.TranslateElement({pageLanguage: 'en'}, 'google_translate_element');
}
</script>

<script type="text/javascript" src="//translate.google.com/translate_a/element.js?cb=googleTranslateElementInit"></script>
```

# CSS CODE
```CSS
<style>
/*google translate Dropdown */
#google_translate_element select {
  background: transparent !important;

  border: none;
  font-size: 14px;
}
.goog-te-gadget .goog-te-combo {
  margin-top: 19px !important;
}
/*google translate link | logo */
.goog-logo-link {
  display: none !important;
}
.goog-te-gadget {
  color: transparent !important;
}

/* google translate banner-frame */

.goog-te-banner-frame {
  display: none !important;
}

#goog-gt-tt,
.goog-te-balloon-frame {
  display: none !important;
}
.goog-text-highlight {
  background: none !important;
  box-shadow: none !important;
}
body {
  top: 0 !important;
}

</style>
```

## Google Translator CDN
Don't forget call or add the Google Translator CDN to your page
[Google Translator CDN](https://translate.google.com/translate_a/element.js?cb=googleTranslateElementInit).

## Visit our  [website @ codexpress.info](https://codexpress.info) 
For more tutorials pls follow me on  [twitter @ marshallunduemi](https://twitter.com/marshallunduemi). 
