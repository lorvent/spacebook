---
title: Errata and To-do
date: 2020-11-20
permalink: /errata/index.html
eleventyNavigation:
  order: 95 
  key: Errata and To-dos
---
This is a small page to track known errors, to-dos, and other small things I wish worked differently. Pull requests are welcome 😇

## Errata 

* [ ] **package-lock.json** Like similar starter projects I've seen, this one did not ship with a lock file. But midway through development, a new release of a PurgeCSS dependency started breaking builds. The project is currently locked to a working version in package-lock.json. I'd like to soon update and/or re-remove package-lock.json. In the meantime, update modules at your own risk!
* [ ] **Pretty code** As it turns out I've come to rely on Prettier to format all of my code. There is not a Prettier plugin for Nunjuck templates, and some code is in need of, well, prettying up. 
* [ ]  **FOUC** I've got it working pretty smoothly now, but there is still sometimes a small Flash of Unstyled Content (FOUC) that appears when a site is encrypted (usually on first page load only) that I'd like to fix.  
* [ ] **Mobile footer** On Android mobile (and maybe iPhone?) the fixed footer does not stay "fixed" until you first get to the bottom of the page. This may be a default but I'd prefer a fixed footer on all screens.

## To-dos

* [ ] **Eleventy Images** I'd like to integrate this plugin for more advanced image handling (currently the burden is on you to serve the best/smallest image you can)
* [ ] **Streamlined starter content** Currently when you install spacebook, you get ALL of the content as it currently exists on spacebook.app. It only takes a hot minute to delete all of these pages, but it may be better to ship with a smaller set of starter content.
* [ ] **Alpine.js** An earlier version of spacebook used some Alpine.js code for various interactions. The current version does not use ANY but since it adds such a minimal performance impact it is still in the codebase in hopes of adding some additional sugar.
* [ ] **Blog and/or similar** Spacebook originally included advanced blog functionality but it was stripped out in favor of first getting the basics exactly right. It may be nice to re-introduce as an optional feature.
* [ ] **Netlify Functions and other data** Spacebook is all set up to run Netlify functions (AWS Lambda) or to pull in data from other sources such as an API, Google Sheets, or an Airtable. Would like to provide some demos :)
* [ ] **Sitemap.xml** For public spacebooks, I'd like to have a working example of a sitemap.xml file.

