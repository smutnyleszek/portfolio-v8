---
title: HashTabber
thumbnail: hashtabber-thumbnail.svg
categories: [code, logo]
layout: post
language: en-us
permalink: /en-us/project/hashtabber
---

[HashTabber](http://hashtabber.smutnyleszek.com) is a simple `JavaScript` plugin for tabbed navigation with hash-driven links.

The plugin was featured i.a. on:

- [unheap.com](http://www.unheap.com/navigation/horizontal-tabbed/hashtabber/)
- [jquer.in](http://jquer.in/javascript-frameworks-for-developing-rich-applications/hashtabber/)
- [jquery-plugins.net](http://jquery-plugins.net/hashtabber-simple-hashchange-driven-tabbed-navigation)
- [jqueryscript.net](http://www.jqueryscript.net/blog/10-New-jQuery-Plugins-You-Have-To-See.html)
- [jplugins.net](http://www.jplugins.net/hashtabber/)
- [softpedia.com](http://webscripts.softpedia.com/script/Menus-Navigation/HashTabber-83059.html)
- [bestplugins.com](http://www.bestplugins.com/articles/jquery-plugins.html/)
- [jqueryplugins.net](http://jqueryplugins.net/hashtabber-simple-javascript-hashchange-tabbed-navigation)

In some free time I built a simple logo based on the shapes of "#" and "T" characters and the tabbed interface itself. Visually, I dressed it in jade green and some warmer grays.

[![logo][hashtabber-01]][hashtabber-01]

[![palette][hashtabber-02]][hashtabber-02]

*Modus operandi* of the script is more precise and technically-wise described [on the website of the project](http://hashtabber.smutnyleszek.com), but in short it can be described by the following diagram:

1. You activate the tab (a simple hash link)
2. Ther browser's address changes
3. The script waits for change of the address, from where it gets the name of the new tab
4. The script pairs the tab with its content
5. The script turns off the old tab with content and turns on the new one

This may sound banal, but thanks to the hash links, the page doesn't reload and you can change tabs from the outside. And the whole functionality is minimalistic, slick and ready for use with very low requirements.

[![diagram][hashtabber-03]][hashtabber-03]

The page didn't need practically nothing but some smooth typography -- I used *Source Sans Pro* from Paul Hunt, a slim modular scale and a few clever `media queries` for mobile devices.

[![website-1][hashtabber-04]][hashtabber-04]

[![website-2][hashtabber-05]][hashtabber-05]

[![website-3][hashtabber-06]][hashtabber-06]

[![website-4][hashtabber-07]][hashtabber-07]

In addition, the entire script is [availabe in the Public Domain](https://creativecommons.org/publicdomain/zero/1.0/), i.e. for free.

[hashtabber-01]: {{site.baseurl}}/assets/img/project/hashtabber/hashtabber-01-logo.png
[hashtabber-02]: {{site.baseurl}}/assets/img/project/hashtabber/hashtabber-02-palette.png
[hashtabber-03]: {{site.baseurl}}/assets/img/project/hashtabber/hashtabber-03-diagram.png
[hashtabber-04]: {{site.baseurl}}/assets/img/project/hashtabber/hashtabber-04-website-1.png
[hashtabber-05]: {{site.baseurl}}/assets/img/project/hashtabber/hashtabber-05-website-2.png
[hashtabber-06]: {{site.baseurl}}/assets/img/project/hashtabber/hashtabber-06-website-3.png
[hashtabber-07]: {{site.baseurl}}/assets/img/project/hashtabber/hashtabber-07-website-4.png
