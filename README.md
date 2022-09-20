# Website

This is the repository used to build and publish Kevin's [website](https://kevin.st-sauveur.net).

## Quick start

This website is built with [Hugo](https://gohugo.io/) and the [Papermod](https://github.com/adityatelange/hugo-PaperMod/) theme.

Steps needed to have this working locally:

-   Follow the [Install Hugo](https://gohugo.io/getting-started/installing/) instructions
-   Clone this repository
-   Run `git submodule update --init --recursive`
-   Run `hugo server`

# Organization

The site is organized by section.

```
# URL structure
https://kevin.st-sauveur.net/{ section }/{ page name }

# Example
https://kevin.st-sauveur.net/posts/hello-world/
```

## Home page

-   Home: [kevin.st-sauveur.net](https://kevin.st-sauveur.net)
-   About: [https://kevin.st-sauveur.net/about/](https://kevin.st-sauveur.net/about/)
-   Posts: [https://kevin.st-sauveur.net/posts/](https://kevin.st-sauveur.net/posts/)

## Sections

Each section delimit a new functionality to the website.

-   Home
-   About
-   Archive
-   Posts
-   Search
-   Tags

## Pages

Docs are written as markdown files with extension `.md`.

# Images

Images are stored in [`/static/images`](https://github.com/kevinstsauveur/kevin.st-sauveur.net/tree/main/static/img).

## Image optimization and compression

To reduce loading time, use the [AVIF](https://aomediacodec.github.io/av1-avif/) and [WebP](https://developers.google.com/speed/webp) format to optimize and compress JPG/PNG/GIF images.

Code has been added to handle AVIF and WebP. As a fallback, JPG will be used for non supported browsers.