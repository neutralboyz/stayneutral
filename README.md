# General overview

## Introduction

The projet **portfolio-hugo-starter** is thought as a starter theme to
create a visual portfolio website.

## Concepts

Inside the `/content` folder resides the user generated contents.

Theme templates can also be overidden. If this is the case, you should
be sure to "eject" the `portfolio-hugo-theme` from its **always
green** update system. (TODO: explain how).

In the `config.toml` file you can set the title of your website (and more).

## Installation

TODO: what is the process for a user without a Github and Netlify
account to start using this theme and beneficiate from the update
pipeline?

## portfolio-hugo-theme

`portfolio-hugo-starter` uses [portfolio-hugo-theme](
 https://github.com/internet4000/portfolio-hugo-theme) as theme. It is
 installed inside the `/themes` folder and referenced inside
 `/config.toml`). This theme provides most configuration, structure
 and styles to make the portfolio-starter work. The theme is also used
 to provide updates and bug fixes to the starter.

# Development

Contributions are welcome.

## Install the project environment

It is required to have the following softwares on your development
environment:

- Git
- [Hugo](https://gohugo.io/)'s cli

You can then install the project by cloning it:

`git clone --recurse-submodules git@github.com:internet4000/portfolio-hugo-starter.git`


This command also clones the git submodules, namely the
 `portfolio-hugo-theme`. Its location is
 `/portfolio-hugo-starter/themes`.

