---
title: How to edit the home page?

---
So you have installed Stastic on an existing website, or you created a new one, and now you are willing to edit the home page?

If what you see is close to the following image, or more generally what you change in a page does not affect the live content on your website, continue reading.


![Editing the home page in Stastic](https://www.stastic.net//assets/2019-08-04-773303.png)

The cause of a page not taking into account what you provide in Stastic editor as its content is probably that some themes have "hard coded" pages. To understand this you need to know that Stastic is built on top of Github pages, which uses [Jekyll](https://jekyllrb.com/) to build your website, i.e. put your content into a theme's HTML layouts. Read more about [how Jekyll layouts work](https://jekyllrb.com/docs/step-by-step/04-layouts/).

When you create a page in Stastic, you can set the layout of this page (see the drop down list at the bottom while editing a page?). Some layouts light simply ignore the content of your page and simply display HTML content. This is often done for home pages which might have a more complex design than just one text content. Note that sometimes, these "hard coded pages" take some settings of your website into accout.

> Very often, to edit the title displayed on your home page, change the title in the settings of your website. See the section "[Stastic UI, the general settings]" to learn more about this.

If a page you need to edit is a "hard coded page" and has no way to change it throug page content nor general settings, then you have several things to try in order to change its content:

1. Try to change the content of the page from the page list, then try to change the settings in the "General settings" page in Stastic
2. Go to this page from the page list, and change it's "layout meta data" which is the drop down list at the bottom, bellow the text content.
3. Edit the HTML layout. For this you will probably need to see the source code of your theme (checkout in the list of themes on [Stastic installer here](https://stastic.net/#/themes) there is a "Source" button for each theme). You might need professional support for this, checkout the section "[Professional support and custom developments]".
