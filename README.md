# history-by-date

A Chrome extension that lets you browse your history by date, instead of infinite scroll.

## Why?

I obsessively track every minute of my time. And I often refer to my Chrome browser history to get a sense of what I
was doing at certain times on certain days. If you've ever tried doing that, you'll find that it is a very broken
experience -- a laborious infinite scroll, and often the scroll resets randomly.

I used to use the [Better History](https://github.com/better-history) Chrome extension, but I learned it used to be
open-source, but was sold, and then made closed-source. Giving my Chrome history to a closed-source for-profit
extension made me nervous. And for good reason, because at one point, Better History was [hijacking your browser to
display ads](https://hotforsecurity.bitdefender.com/blog/better-history-chrome-extension-goes-rogue-hijacks-browsers-and-displays-ads-13674.html).

So I made this. An open-source extension for browsing your history by date.

## Features

* Navigate history by date
* Break usage down by continuous sessions (example: "I used Chrome for 2 hours in the morning, and 3 hours in evening")
* Calculates total hours spent online each day
* Filter out specific domains

## Tech

* Bootstrap
* Chrome extension: storage, history APIs
* MobX
* react
* react-hot-loader
* react-select

## Run in development

```
yarn run start
```

## Build

```
yarn run build
```

## Package into ZIP

```
./ext_publish.sh
```
