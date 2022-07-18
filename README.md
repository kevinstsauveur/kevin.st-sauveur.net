# Website
This is the repository used to build and publish Kevin's [website](https://kevin.st-sauveur.ca).

## Quick start

This website is built with [Hugo](https://gohugo.io/) and the [Papermod](https://github.com/adityatelange/hugo-PaperMod/) theme.

Steps needed to have this working locally:
- Follow the [Install Hugo](https://gohugo.io/getting-started/installing/) instructions
- Clone this repository
- Run `git submodule update --init --recursive`
- Run `hugo server`

# Organization

The site is organized by section.
```
# URL structure
https://kevin.st-sauveur.ca/{ section }/{ page name }

# Example
https://kevin.st-sauveur.ca/posts/hello-world/
```

## Home page

- Home: [kevin.st-sauveur.ca](https://kevin.st-sauveur.ca)
- About: [https://kevin.st-sauveur.ca/about/](https://kevin.st-sauveur.ca/about/)
- Posts: [https://kevin.st-sauveur.ca/posts/](https://kevin.st-sauveur.ca/posts/)

## Sections

Each section delimit a new functionality to the website. 

- Home
- About
- Archive
- Posts
- Search
- Tags

## Pages

Docs are written as markdown files with extension `.md`.

# Images

Images are stored at [`/static/images`](https://github.com/kevinstsauveur/kevin.st-sauveur.ca/tree/main/static/img).

## Image optimization and compression

To reduce loading time, use the [WebP](https://developers.google.com/speed/webp) format to optimize and compress JPG/PNG/GIF image.

Command used:
- For every still profile image: `cwebp input.png -q 80 -pass 10 -m 6 -hint picture -o output.webp`
- For every still picture image: `cwebp input.png -q 80 -pass 10 -m 6 -hint photo -o output.webp`