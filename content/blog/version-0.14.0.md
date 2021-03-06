+++
date = "2018-06-30"
title = "Fider 0.14 released with improved foundation and minor features"
categories = ["releases"]
description = "In this next Fider release, we've improved our foundation to support the continued growth"
author = "goenning"
+++

In this release we've focused on technical improvements, but we managed to deliver minor features as well. This is a necessary step towards building a product that can be further enhanced with new features. 

### #1: Filter ideas that I voted

We've included a new filter option: **My Votes**. This option will show all ideas that the current signed in user has already voted on. It is only available for signed in users

<figure>
  <img src="/images/blog/v0.14-filters.png" />
</figure>

### #2: Make comment optional when responding to an idea

Previously, when respoding to an idea, it was required to input a comment. With v0.14, this comment is now optional.

### #3: Experimental Support for CDN

We've introduced new settings that allow administrators to use a CDN to speed up delivery of static assets. This feature is still experimental and will be documented on next release.

### Breaking Changes on Fider 0.14

This version doesn't introduce any breaking change.

### Other Changes on Fider 0.14

- enhancement: output logs to other systems ([#330](https://github.com/getfider/fider/issues/330))
- enhancement: Replace current database migrator with custom ([#401](https://github.com/getfider/fider/issues/401))
- tooling: Update Go, Node and NPM packages ([#422](https://github.com/getfider/fider/issues/422))
- refactoring: General React refactoring ([#423](https://github.com/getfider/fider/issues/423))
- fix: concurrency issue on dbx ([#424](https://github.com/getfider/fider/issues/424)) 
- enhancement: Remove support for TLS 1.0, TLS 1.1 and old ciphers ([#404](https://github.com/getfider/fider/issues/404))
- enhancement: Add Expire Date to all JWT Tokens ([#407](https://github.com/getfider/fider/issues/407)) 
- enhancement: Improve Performance on Home Page ([#403](https://github.com/getfider/fider/issues/403)) 
- enhancement: Markdown links should open in new tab ([#402](https://github.com/getfider/fider/issues/402)) 
- refactoring: Remove arrow functions from React components ([#192](https://github.com/getfider/fider/issues/192)) 
- refactoring: Enable tslint rule: jsx-no-lambda ([#181](https://github.com/getfider/fider/issues/181)) 

### What's next?

Help us shape the future of Fider. Visit our [feedback forum](https://feedback.fider.io/) and raise your voice. Tell us what to do next.