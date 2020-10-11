## Amp Url Cache Translator


## URL Format

When possible, the Google AMP Cache will create a subdomain for each AMP document's domain by first converting it from [IDN (punycode)](https://en.wikipedia.org/wiki/Punycode) to UTF-8. The caches replaces every `-` (dash) with `--` (2 dashes) and replace every `.` (dot) with `-` (dash). For example, `pub.com` will map to `pub-com.cdn.ampproject.org`.

You can use this URL calculator to convert an URL into an AMP cache version:

<div>
<amp-iframe title="AMP Cache tool" height="104" layout="fixed-height" sandbox="allow-scripts" src="/static/samples/files/amp-url-converter.html?url=https://amp.dev/index.amp.html">
  <div placeholder></div>
</amp-iframe>
</div>

