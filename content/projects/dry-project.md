---
title: Create and edit content
slug: create-edit-content
image: /medias/uploads/tumblr_nmi2y50vtq1twkjb3o1_1280.jpg
---
* The content manager is the hidden part of the website that allows you to create new content, or edit the existing one.

To learn how to make this happen, or are unsure of what all this means, continue reading this page (and remember that you can find assistance at any time on the [community support chat](https://riot.im/app/#/room/#support-themes:matrix.org)).

Let's start

# Login

If you now want to log into your site, you have done two important parts in the setup of your site:

1. you did [create a new portfolio](https://app.netlify.com/start/deploy?repository=https://github.com/internet4000/portfolio-hugo-starter).
2. you have created a Github account, which you use to store the whole content and code of your new portfolio site (for reference, the original code and demo content in hosted on this [Github repository](https://github.com/internet4000/portfolio-hugo-starter)).
3. you have created a [Netlify account](https://www.netlify.com/), that is used to host your site, setup custom domains, and who can log in.

If you have already completed these steps, you can move on to the next section, to learn how to login your website, and manage your content.

## Go to the /admin page

To use the content manager of your site, go to its [/admin page](/admin), and log in with your credentials. If you don't know how to login, or don't have yet any credentials, learn how to create your first user account in the next section: **activate authentication.**.

Otherwise if you are now logged in, start editing the content of your site; start by:
* add a new `project` content type to your site, edit and save it. Visit your website home page and see if looks like you want.
* go back to your admin panel and edit existing content, you can delete exisitng entries and start putting your personal content
* change the `title` of your site, for this go to the `config` content type and edit the `config.toml` file.


# Activate authentication

> Note that you *only have to do the following steps once*, before being ablet to login into your CMS (the admin panel). If you can already login, jump to the `content` section of this document.

To be able to securely login to your administrative panel, you must now complete the following actions:

1. Go to your website's project on [Netlify.com](https://netlify.com). Go on the **Identity** page, and click `Enable identity`.
2. Now that identity is enabled, click on `Settings and usage` to go to the identity service settings page, and scroll to the section `Git Gateway`. Finally click on `Enable Git Gateway`
3. Go to your website's [/admin page](/admin), and log in using your Github account.

Alternatively, through Netlify's interface, you can also invite new users to collaborate on your site

# Content

On the content management are available 3 categories of content (content types):

* **projects** are the core content type of your portfolio. You can create new `project`s and they will appear on the homepage of your site.
* **pages** are an other content type, like a `about` or `contact` page. You can have much as you want, and select if they should appear in your site menu or not.
* **configs** stands for configuration. Edit the files under the `configs` content type to find more ways to customize you site, for example, how to change your site title!
* **documentations**. This is a special type of content for your site, where is stored all there is to know about how to edit and manage your site. It is built into your site, so every time there is something you don't know, go there to get answers. 

# How to continue further

If you are done reading this page, you can fully interact and customize your new site. What you can now do is:

* Explore what can be done with your site in the documentation that comes with it.
* Join the [community support chat](https://riot.im/app/#/room/#support-themes:matrix.org)), to discover new ways to improve your site.
