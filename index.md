## Amp Url Cache Translator


## URL Format

When possible, the Google AMP Cache will create a subdomain for each AMP document's domain by first converting it from [IDN (punycode)](https://en.wikipedia.org/wiki/Punycode) to UTF-8. The caches replaces every `-` (dash) with `--` (2 dashes) and replace every `.` (dot) with `-` (dash). For example, `pub.com` will map to `pub-com.cdn.ampproject.org`.

You can use this URL calculator to convert an URL into an AMP cache version:



<iframe  src="https://amp.dev/static/samples/files/amp-url-converter.html?url=https://amp.dev/index.amp.html" width: calc(100% - 1px);>
 
</iframe>

