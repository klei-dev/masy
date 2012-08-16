Making a simple CMS/blogging platform
======================================

**This is my first post in what is going to be the blog of a new CMS/blogging platform, which I'm going to develop.**
I'm going to write here throughout the developing process.

## Goals with the platform

"Why yet another blogging platform?", you might ask. The main reason for this is that it's fun to develop, to build something on your own and to make it fit all of my needs.

### Simple to manage and maintain

One goal with the platform is that it should be really simple to manage, like adding and writing blog posts and static pages. Therefor [markdown](http://daringfireball.net/projects/markdown/) ([GFM](http://github.github.com/github-flavored-markdown/) in particular) is used as the syntax for all content, because it's easy to write and read.
Customizing the layout and graphical appearance should be easy as well, which will be accomplished with templates and configuration files.

### Easy to use for non-developers

You don't have to be a developer to use this new CMS/blogging platform. As mentioned before, the main language for content will be **markdown**, as fpr templating [Twig](http://twig.sensiolabs.org/) will be used as the templating engine and configuration files will be in [json](http://en.wikipedia.org/wiki/JSON)-format.

### Easy to customize and extend for developers

The platform will be built with extensibility in mind, i.e. it will be easy to extend with modules, either your own or modules made by others.

#### Built with PHP and open sourced

The platform, and the modules, will be built with PHP 5.3+ and distributed via [Github](http://github.com) and [Composer](http://getcomposer.org).
