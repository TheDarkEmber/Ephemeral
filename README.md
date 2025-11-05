# Ephemeral
Ephemeral is a browser engine/webview written entirely in TS/JS, HTML, and CSS. The HTML/CSS engine is custom, but it runs JavaScript using Sval (for web builds) or QuickJS for native builds.

## Features
By the first release, we hope to support:
* Supports ES2020+
* Can be embedded on any website
* Full support for cookies and local storage
* Experimental `<iframe>` support
* Specify custom and priveleged URL schemes
* Website freeze protection
* Experimental sync XHR support
* Custom URL schemes
What we WILL support in later versions:
* Support for custom global APIs and DOMless
* Framework for plugin/content script injection
* Support for headless Ephemeral (no renderer)
* IndexedDB and WebSQL support
* Web workers and service workers
* Adobe Flash (thanks to [Ruffle](https://ruffle.rs))
* Caching and offline support
What will NEVER be supported:
* ActiveX, WScript, or any IE-specific features
* Those useless Chrome-only APIs
* Electron support (add it urself with custom global APIs)