---
title: 'Whatever I change, my website does not update'
tags:
  - preview
  - pages
  - collection
  - data
  - settings

---
So you are trying to edit the content of your website with Stastic, but the your website does not change whatever you add or remove or change? 

__Did you read the section "[Stastic UI, how to create pages](/docs/stastic-ui-how-to-create-pages)"? And what about the section "[Why is Static so slow when it comes to creating and writing files to Github?](/docs/why-is-static-so-slow-when-it-comes-to-creating-and-writing-files-to-github)"?__

There is probably a problem with your website content which causes an error when [Github pages](https://pages.github.com/) tries to build it. This prevents the website from updating any content - tip: change an existing content to see if it is your case. Also if this is the case you will receive an email from Github pages which says that there was a problem building your site. It may be in a post or page or in the settings. 

__Note: if only one page is not updating, please read the section "[How to edit the home page?](/docs/how-to-edit-the-home-page)"__

The "easy" way of fixing this is to undo what you did recently to find out what is wrong and when it starts to update again. You can use [Github commits views](https://help.github.com/en/articles/differences-between-commit-views) to see what was modified and when. 


A more professional way is to clone the website code on your local computer and run [Jekyll command lines](https://jekyllrb.com/docs/) to build the website and get a detailed error. Also you might want to read the section "[Professional support and custom developments](/docs/professional-support-and-custom-developments)" to pay for support. 
