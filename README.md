
# pf-elements
A Polymer 2.0 based collection of reusable web components 

[![Join the chat at https://gitter.im/pf-elements/Lobby](https://badges.gitter.im/pf-elements/Lobby.svg)](https://gitter.im/pf-elements/Lobby?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

[![Published on webcomponents.org](https://img.shields.io/badge/webcomponents.org-published-blue.svg)](https://www.webcomponents.org/element/owner/my-element)

## Demo
[Click here for Demo](https://pfelements.github.io/pf-parallax-video)


## Install the Polymer-CLI

First, make sure you have the [Polymer CLI](https://www.npmjs.com/package/polymer-cli) installed. Then run `polymer serve` to serve your application locally.

# PF Parallax Video

APolymer 2.0 based custom-element to display video with parallax effect and overlays.

| Element Name | Latest Version (Bower) | Npm version  | Build Status |
|--------------|------------------------|--------------|--------------|
| [pf-parallax-video](https://github.com/PFElements/pf-parallax-video) | [![GitHub version](https://badge.fury.io/gh/PFElements%2Fpf-parallax-video)](https://badge.fury.io/gh/PFElements%2Fpf-parallax-video) | [![npm version](https://badge.fury.io/js/pf-parallax-video.svg)](https://www.npmjs.com/package/pf-parallax-video) |[![Build Status](https://travis-ci.org/PFElements/pf-parallax-video.svg?branch=master)](https://travis-ci.org/PFElements/pf-parallax-video) | 

## Learn more

See the list of elements, demos, and documentation by browsing this collection on webcomponents.org:

### [Take me to webcomponents.org ›](https://www.webcomponents.org/element/PFElements/pf-parallax-video)

---
#Usage

`<pf-parallax-video webmsrc="path of webm video" videoposter="path of poster for video"></pf-parallax-video>` 


Custom property                         | Description                               | Default
----------------------------------------|-------------------------------------------|-------------------------
`--pf-parallax-video-height`            |  Height of video div                      | 500px
`--on-pause-video-fade-color`           |  A transprent color when video is paused  | rgba(0,0,0,.85)
`--overlay-pattren-img`                 |  A pattren image on video                 | media/imgs/pattren.png
`--pause-button-img`                    |  Video Pause button image                 | url(media/imgs/ic_pause.png) left top no-repeat
`--play-button-img`                     |  Video Play button image                  | media/imgs/ic_play.png) left top no-repeat
`--heading-disply`                      |  'none' if you want to hide heading       | block
`--title-heading-bg`                    |  Background color of heading              | rgba(0,0,0,.5)
`--title-text-color`                    |  Heading text color                       | #fff


## Viewing Your Application

```
$ polymer serve
```

## Building Your Application

```
$ polymer build
```

This will create a `build/` folder with `bundled/` and `unbundled/` sub-folders
containing a bundled (Vulcanized) and unbundled builds, both run through HTML,
CSS, and JS optimizers.

You can serve the built versions by giving `polymer serve` a folder to serve
from:

```
$ polymer serve build/bundled
```

## Running Tests

```
$ polymer test
```

Your application is already set up to be tested via [web-component-tester](https://github.com/Polymer/web-component-tester). Run `polymer test` to run your application's test suite locally.

## Contributing

Comments, questions, suggestions, issues, and pull requests are all welcome.

### Get in touch with the team

Joing us at [![Join the chat at https://gitter.im/pf-elements/Lobby](https://badges.gitter.im/pf-elements/Lobby.svg)](https://gitter.im/pf-elements/Lobby?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

- [Twitter](<a href="https://twitter.com/polymerjs" class="twitter-follow-button" data-show-count="false">Follow @polymerjs</a>)
- [Facebook] (https://www.facebook.com/polymerjs)

### Some ways to help:

- **Test the elements and provide feedback**: We would love to hear your feedback on anything related to the elements, like features, API and design. The best way to start is by trying them out. And to get a quick response, either drop a question/comment on the chat or open an issue in GitHub.
- **Report bugs**: File issues for the elements in their respective GitHub projects.
- **Send pull requests**: If you want to contribute code, check out the development instructions below.

We encourage you to read the [contribution instructions by GitHub](https://guides.github.com/activities/contributing-to-open-source/#contributing) also.

## License

MIT License
