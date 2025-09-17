## Introduction

The bBox FileMaker plug-in is a toolbox of functions freely available to all developers. Use it with your macOS or Linux (Ubuntu) based FileMaker solutions to call programs, scripts, code libraries, and OS functions that are not available within FileMaker:

* AppleScript
* cURL HTTP (for SOAP or REST calls)
* DuckDB (SQLite for older versions)
* JavaScript (NodeJS and JavaScriptCore)
* JQ
* GraphicsMagick
* Python
* Ruby
* Shell scripts (sh, Bash, Zsh)
* XPath

Offering dozens of powerful functions, bBox extends the reach of FileMaker’s existing commands. This makes it easier to get your projects done, and without the need for ugly workarounds to provide functionality that should be simple.

Some common uses are:

* integration with Python-based libraries
* Parse XML or JSON
* AppleScripts that easily return results to FileMaker
* accessing WSDL (SOAP) services
* ad-hoc searches for layout elements using XML in clipboard
* output formatted PDF or Excel files
* shell access to manipulate file system
* parsing text with regular expressions
* transforming images with SIPS or ImageMagick
* customized SMTP email

***

## [FileMaker Function List](https://www.beezwax.net/bbox-functions)

Many functions are also available as script steps. However, the function based versions often have fewer restrictions on parameters.

***

## [Installation & Requirements](https://github.com/beezwax/bbox-documentation/wiki/Installation)

Information on pre-requisites for installation, and how to install.

***

## [Error Handling & Troubleshooting](https://github.com/beezwax/bbox-documentation/wiki/Errors)

Information on getting and handling errors in bBox or trouble-shooting issues.

***

## [bBox Modes](https://github.com/beezwax/bbox-documentation/wiki/Mode-Parameters)

Many functions and script steps accept a mode parameter to adjust features or behaviors.

***

## [bBox Parameters](https://github.com/beezwax/bbox-documentation/wiki/Parameters)

Various parameter types and how they are handled.
 
***

## [Native Python, JavaScript, & DuckDB Functions](https://github.com/beezwax/bbox-documentation/wiki/Native-Python,-JavaScript,-and-DuckDB-Functions)

When using the `bBox_JavaScript`, `bBox_PythonExecute`, or `bBoxPythoneEval` functions, bBox can add in a custom `fm` class to the environment for improved integration with FileMaker. DuckDB supports an `fmevaluate` function too.

***

## [Sessions and Thread Saftey](https://github.com/beezwax/bbox-documentation/wiki/Sessions-&-Thread-Safety)

Some functionality require a persistent state or context, or have limitations on when they are called. 

***
 
## Function Documentation by Version

* [Documentation (version 0.97+)](https://www.beezwax.net/bbox-functions)
* [Documentation (version 0.88)](https://www.beezwax.net/bbox-0-88-functions)
* [Documentation (version 0.86)](https://www.beezwax.net/bbox-0-86-functions)

## Examples

The bBox Plug-in Demo file has 200 examples of the various functions, and is included with the bBox disk image.


## Product Information

* [Installation](https://www.beezwax.net/bbox-wiki-installation)
* [https://www.beezwax.net/products/bbox](http://www.beezwax.net/products/bbox)
* [https://www.beezwax.net/download/bbox](http://www.beezwax.net/download/bbox)

## Related Blog Posts

* [bBox FileMaker plug-in: Easily add AppleScript, Shell, Grep, and more to your FileMaker projects](https://blog.beezwax.net/bbox-filemaker-plug-in-easily-add-applescript-shell-grep-and-more-to-your-filemaker-projects)
* [Using Cocoa’s PDFDocument class from FileMaker](https://blog.beezwax.net/using-cocoas-pdfdocument-class-from-filemaker/)
* [XML Parsing with FileMaker and bBox](https://blog.beezwax.net/xml-parsing-with-filemaker-and-bbox/)
* [Curl HTTP Post from FileMaker](https://blog.beezwax.net/curl-http-post-from-filemaker)
* [Version 0.63 of bBox Now Available](https://blog.beezwax.net/version-0-63-of-bbox-now-available/)
* [Version 0.71 of bBox Now Available](https://blog.beezwax.net/version-0-71-of-bbox-now-available/)
* [Installing xhtml2pdf on OS X](https://blog.beezwax.net/installing-xhtml2pdf-on-os-x/)
* [Version 0.80 of bBox Now Available](https://blog.beezwax.net/bbox-0-80-now-available/)
* [Run PHP code with FileMaker & bBox](https://blog.beezwax.net/run-php-code-from-filemaker-bbox/)
* [JavaScript-driven PDF Reports in FileMaker using AngularJS (and bBox)](https://blog.beezwax.net/javascript-driven-pdf-reports-in-filemaker-using-angularjs/)
* [Version 0.82 of bBox Now Available](https://blog.beezwax.net/version-0-82-of-bbox-now-available/)
* [Version 0.83 of bBox Now Available](https://blog.beezwax.net/2249)
* [Version 0.84 of bBox for FileMaker Now Available](https://blog.beezwax.net/version-0-84-of-bbox-for-filemaker-now-available/)
* [Version 0.86 of bBox for FileMaker Now Available](https://blog.beezwax.net/version-0-86-of-bbox-for-filemaker-now-available/)
* [Version 0.90 of bBox for FileMaker Now Available](https://blog.beezwax.net/bbox-for-filemaker-v0-90-now-available)
* [Version 0.93 of bBox for FileMaker Now Available](https://blog.beezwax.net/bbox-for-filemaker-v0-93-now-available)
* [bBox for FileMaker v0.95 Now Available](https://blog.beezwax.net/bbox-for-filemaker-v0-95-now-available)
* [bBox for FileMaker v0.96 Now Available](https://blog.beezwax.net/bbox-for-filemaker-v0-96-now-available)
* [Working with JSON data in FileMaker](https://blog.beezwax.net/working-with-json-data-in-filemaker)
* [bBox for FileMaker v0.98 with M1, GraphicsMagick & Sips](https://blog.beezwax.net/bbox-for-filemaker-v0-98-with-m1-graphicsmagick-sips)
* [bBox v0.99 Integrates Claris FileMaker with JavaScript, Python 3 and Supports M1 Apple Silicon](https://blog.beezwax.net/bbox-for-filemaker-v099-javascript-python3-m1)
* [Leveraging pandas with Python to Analyze FileMaker Data Sets](https://blog.beezwax.net/leveraging-pandas-with-python-to-analyze-filemaker-data-sets/)
* [bzPython-FM performs Python for your FileMaker apps](https://blog.beezwax.net/bzpython-python-for-your-filemaker-apps/)
* [bBox 1.04 for FileMaker Now Available](https://blog.beezwax.net/bbox-1-04-for-filemaker/)
* [bBox 1.05 for FileMaker Now Available](https://blog.beezwax.net/bbox-1-05-for-filemaker-now-available/)
* [bBox 1.06 for FileMaker Now Available](https://blog.beezwax.net/?p=14405)
* [Using OData, Syslog or DuckDB to handle FileMaker Schema Change Notifications (via Plug-in API)](https://blog.beezwax.net/using-odata-syslog-or-duckdb-to-handle-filemaker-schema-change-notifications-via-plug-in-api/)

### Current Version

As of July 19, 2025 the current version is 1.06 for macOS and Ubuntu.
