---
title: Why is Static so slow when it comes to creating and writing files to Github?

---
Stastic is a website editor which lets you edit your files on Github, which is a fantastic service, as explained in the sections "[Who owns my data]" and "[Where is my website hosted?]".

When you use Stastic installer to install Stastic on an existing website or to create a new website, when you use Stastic editor to edit content on your website, all these operation are made on files which are located on Github servers. The read and write operations are fast, but every time you do this, Github pages trigger a "build", to update your website. This is what is slow.

While a build is in progress, Stastic displays a "wheel" to let you know that you can continue to work while your site is updated with the new content.

