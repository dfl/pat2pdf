# pat2pdf

This script connects to the [USPTO](https://ppubs.uspto.gov/pubwebapp/static/pages/ppubsbasic.html) patent database and downloads the PDF.

# History

This script was originally a complicated method that fetched individual TIFF files, written by Oren Tirosh and Thomas Boege, and Paul William. Nowadays the PDF can be found directly on the USPTO site, so all the cool fancy scripting is no longer needed. David Lowenfels simplified it to grab the file directly.

# Compatibility

This scirpt should work on any Unix-like system (Linux, Mac OS X etc.) with the required command line tools and libraries installed.

# Usage

> pat2pdf &lt;Patent Number or Application Number&gt;

# Examples

Fetching a USTPO patent application:

> pat2pdf 20130049740

Fetching a USTPO patent:

> pat2pdf 8259522

Result is a file in the current directory named pat&lt;patnum&gt;.pdf

# License

This script is licensed under the GPL (version unspecified).
