# \<Jarkko-Coffee\>

Chat para Arquitectura de software

## Install the Polymer-CLI

First, make sure you have the [Polymer CLI](https://www.npmjs.com/package/polymer-cli) installed. Then run `polymer serve` to serve your application locally.

## Viewing Your Application

```
$ polymer serve
```

## Building Your Application

```
$ polymer build
```

This will create a `build/` folder with `bundled/` and `unbundled/` sub-folders
containing a bundled (Vulcanized) and unbundled builds, both run through HTML,
CSS, and JS optimizers.

You can serve the built versions by giving `polymer serve` a folder to serve
from:

```
$ polymer serve build/bundled
```

## Running Tests

```
$ polymer test
```

Your application is already set up to be tested via [web-component-tester](https://github.com/Polymer/web-component-tester). Run `polymer test` to run your application's test suite locally.

## CORS Problems in chrome browser

For run in Chromium Browser in Lunix use this command from terminal for open browser
```
Chromium-browser --disable-web-security --user-data-dir
```

For Windows, run in command prompt the command
```
"C:\Program Files (x86)\Google\Chrome\Application\chrome.exe" --disable-web-security --user-data-dir
```

Using the URL for Chrome installation

For OSx, run this command
```
open -a Google\ Chrome --args --disable-web-security --user-data-dir
```