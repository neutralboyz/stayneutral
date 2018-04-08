# Portfolio starter

The projet **portfolio-hugo-starter** is thought as a starter theme to
create a visual portfolio.

## Installation - create a new site, and put it online

Follow these steps if you want to create a new portfolio site

1. Before all, in order to host the code and content of your site, you
will need a Github account. [Create Github
account](https://github.com/join?source=header-home) (or log in yours
if you already have one).

2. The easiest way to get running with your new portfolio, is to use
Netlify to host and deploy every changes made to your content. [Create a new
site](https://app.netlify.com/start/deploy?repository=https://github.com/internet4000/portfolio-hugo-starter).


> The steps on the link above will lead you through setting up Netlify
> as the host of your new website. Each time you will edit the content
> of your site, Netlify will use the newest version of it to generate
> the latest version of your site.

In the `config.toml` file you can set the title of your website (and
more).

TODO: work on this customization, so the `site.Title` can be edited
from the `netlify-cms` interface (or what makes best sense).

## Overview

The architecture of the website is like the following

``` bash
/portfolio-hugo-starter/README.md <- the current document
/portfolio-hugo-starter/content <- where all user content is
/portfolio-hugo-starter/themes <- the layout of the site
/portfolio-hugo-starter/config.tom <- configuration
/portfolio-hugo-starter/netlify.toml <- configuration
/portfolio-hugo-starter/.git <- configuration
/portfolio-hugo-starter/.gitignore <- configuration
/portfolio-hugo-starter/.gitmodules  <- configuration
```

Inside the `/content` folder resides the user generated contents. All
edits you make to the content of your site through the admin interface
is stored inside this folder.

Inside the `/themes` folder is the layout structure of your site.

> You should not change anything (unless you know what your're
> doing, and you know how to use `git`) inside the `/content` folder
> and in the files markes as  _configuration_ above.

Theme templates and styles can be changed from their defaults, without
updates from the base theme to break your changes (see the
development section).

# Development

You will only need the informations in this section if want to change
the code of this software. Feel free to participate!

### Install the project environment

It is required to have the following softwares on your development
environment:

- [Git](https://help.github.com/articles/set-up-git/) - Github's
  tutorial on how to install Git.
- [Hugo](https://gohugo.io/getting-started/installing/) - installation
  steps for the static site generator used for this project.

You can then install the project by cloning it:

`git clone --recurse-submodules git@github.com:internet4000/portfolio-hugo-starter.git`

This command also clones the git submodules, namely the
 `portfolio-hugo-theme`. Its location is
 `/portfolio-hugo-starter/themes`.

If you did not clone the repository with the submodules like above,
inside the root of the project's folder you can use this command `git
submodule update --init --recursive` to set them up.

### portfolio-hugo-theme

The safest way to customize your site without the base theme (see section about
`portfolio-hugo-theme`) breaking your changes is to "eject" the
`portfolio-hugo-theme`. the consequense is that your site won't be
affected by the **always green** update system (therefore not getting
future updates).

`portfolio-hugo-starter` uses [portfolio-hugo-theme](
 https://github.com/internet4000/portfolio-hugo-theme) as theme. It is
 installed inside the `/themes` folder and referenced inside
 `/config.toml`). This theme provides most configuration, structure
 and styles to make the portfolio-starter work. The theme is also used
 to provide updates and bug fixes to the starter.
 
Read [Hugo's theme customization documentation](https://gohugo.io/themes/customizing/), to best learn how to customize the
code and appearence of your site.
 

## Note for later:

> the following command will effectively set a website’s title on
Unix-like systems: `$ env HUGO_TITLE="Some Title" hugo`
