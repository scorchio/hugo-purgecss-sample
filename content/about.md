---
title: "About"
layout: "page"
type: page
comments: false
---

This page demostrates the issue with PurgeCSS vs Luna. 

Below, you should see two dummy images that are coming form the `layouts/_default/page.html` theme override file. They have some Tailwind classes that are not used in `hugo-theme-luna`. If you check them in the inspector, it should be visible that the relevant CSS is missing: on the left image, the `md:mr-6` class doesn't have any effect, leaving the gap between the images minimal.
