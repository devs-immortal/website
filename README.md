# Immortal Devs website

## How to run local server

For viewing new content run `hugo server` and visit the rendered version in your browser at http://localhost:1313/.

## How to contribute

If you want to make a change to the website, add a wiki page, fix a typo or whatever, simply clone this repo and make a pull request against it. When the PR is accepted, we will re-generate the website and upload the new version.

This website uses the Hugo static site generator. Its documentation can be found here: https://gohugo.io/documentation/

### How to add a news or blog article

If you have Hugo installed in a reachable path, simply run

```
hugo new content/wiki/mod/block.md
```

and it will create a template for a new page. Alternatively, copy an old page (if you don't have Hugo running) and modify it accordingly.