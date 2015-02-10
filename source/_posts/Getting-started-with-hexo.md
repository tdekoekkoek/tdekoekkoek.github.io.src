title: Getting started with hexo
tags:
  - hexo
  - blogging
  - angularjs
date: 2015-02-04 14:47:22
---

Yes I'm rebuilding my blog from scratch yet again.  My previous blog was done in Ghost and I didn't keep it live.  I have now decided to relaunch my blog on github pages.

## Static Site Generators

I first tried out some static site generators like DocPad and Jekyl some time ago, but I ended up creating my blog in Ghost.  Since that time I've decided to revisit static sites for a number of reasons:

* My Ghost Blog needs to be replaced
* I like the idea of hosting my blog on [github pages](http://github.io)
* I like having full control of my markup so that I can host [Angular](https://angularjs.org/) samples and applictions directly in my blog
* It's the latest thing all the cool kids are doing these days.

## Introducing Hexo

[Hexo](http://hexo.io) is a powerful static blog generator.  I tried a number of other static site generators and either it was difficult to get blogging going without a lot of extra work or they required Ruby.  I was really looking for a Javascript only solution.  So I gave Hexo a try.  I've found it not only quite powerful, but well documented and extremely easy to set up.  There are also a number of [themes](http://hexo.io/themes) available.

So far I'm quite happy with my choice.  Hexo uses Markdown or Html for editing content and uses [EJS](http://www.embeddedjs.com/) and [Swig](http://paularmstrong.github.io/swig/) for templating.  However you really don't need to know anything about EJS or Swig to use Hexo.

## Getting Started

Installing hexo is dead simple.  You just need to make sure you have Node and npm already set up.  If you're not familiar with node, head on over to <http://nodejs.org/> to learn about it and to install it.  Borrowing from the Hello World documents, you can get started with Hexo as follows:

### Installation

``` bash
$ npm install -g hexo
```

More info: [Getting Started](http://hexo.io/docs/index.html)

### Create a new post

``` bash
$ hexo new "My New Post"
```

More info: [Writing](http://hexo.io/docs/writing.html)

### Run server

``` bash
$ hexo server
```

More info: [Server](http://hexo.io/docs/server.html)

### Generate static files

``` bash
$ hexo generate
```

More info: [Generating](http://hexo.io/docs/generating.html)

### Deploy to remote sites

``` bash
$ hexo deploy
```

More info: [Deployment](http://hexo.io/docs/deployment.html)

## Markdown

Once you're up and running with Hexo you'll want to get a simple markdown editor.  Right now I'm just typing in [Brackets](http://brackets.io/) (a very cool editor by the way), but I'll probably look into some online Markdown editors or perhaps a windows program or maybe just create a simple Angular app with [ShowDown](https://github.com/showdownjs/showdown).  We'll explore that another time.