---
title: How to preview a post?

---
In the case your website is live and you want to preview changes before your visitors see it.

The way to go is to have 2 versions of your site (i.e. preprod and prod), it means 2 forks of the same repository so you can do pull requests to make your changes live. You may want to create an organisation to hold the main repository:

* the organization will have the main repo and it is what your visitors see
* your personal account will have a fork of this same repo and that is what you edit and preview

Here is a real life example:

* my site is cto-bro.com
* it is served [from this repo (internet-de-france/cto-bro.com)](https://github.com/internet-de-france/cto-bro.com)
* when I want to edit the content, I do in on [this repo (lexoyo/cto-bro.com)](https://github.com/lexoyo/cto-bro.com) with stastic installed on it
* so my preview is available on `https://lexoyo.me/cto-bro.com/fr` (I have a custom domain on all my personal github pages) 