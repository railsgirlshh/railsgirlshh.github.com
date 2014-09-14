# Rails Girls Guides

This repository is providing german translations for some of the [Rails Girls Guides](http://guides.railsgirls.com). You can view the german translations on http://railsgirlshh.github.io.

These translations were started by [Rails Girls Hamburg](http://railsgirls.com/hamburg).

We aim to keep this translation as close to the original as possible. If you have suggestions to improve the guides or want to contribute a new guide, please do so by providing a pull request to the [original guides](https://github.com/railsgirls/railsgirls.github.com). 

If you would like to help with the german translation, we're happy to receive your pull requests (see below). You can email to railsgirlshh@gmail.com or contact [@railsgirlshh](https://twitter.com/railsgirlshh) on twitter if you have questions.

## Quick start

Clone this repo and install & run [jekyll](https://github.com/mojombo/jekyll)

### Installing jekyll

```
$ cd railsgirlshh.github.com
```

```
$ bundle install
```

### Pygments and Code Highlighting

The guides use the [pygments](http://pygments.org/) library to do syntax highlighting. If you don't have it installed you won't be able to see the highlight sections like the following:

```
{% highlight %}
{% endhighlight %}
```

If you aren't editing the code blocks, you can safely ignore this. If you want pygments, you can follow the [install instructions](https://github.com/mojombo/jekyll/wiki/Install) in the "Pygments" section.

### Run jekyll

```
$ bundle exec jekyll serve --watch
```

### Having trouble?

You might find some useful hints in this jekyll issue if it's not working as expected: [Issue 503](https://github.com/mojombo/jekyll/issues/503)

### Branches
* branch `master` is deployed to http://railsgirlshh.github.io
* branch `upstream` is kept in sync with the `master` branch of the [original guides](https://github.com/railsgirls/railsgirls.github.com)

#### Import and translate updates from the original guides
* update the `upstream` branch to the latest version of the original guides
* merge `upstream` into `master`
* solve merge conflicts by providing the proper german translation

## Pull Requests
* if you want to submit several unrelated changes, please create different pull requests (e.g. one for fixing typos in the installation guide and another one for translating the additional guide xyz).
* fork this repository and branch from `master`
* before sending the pull request, we kindly ask you to squash your commits and rebase your feature branch to the top of `master`

You can email to railsgirlshh@gmail.com or contact [@railsgirlshh](https://twitter.com/railsgirlshh) on twitter if you have questions or need help with preparing the pull request.

## Website & Blog

Official website and blog for Rails Girls movement can be found at http://railsgirls.com

## Credits for the original guides

* Karri Saarinen / [@karrisaarinen](https://twitter.com/karrisaarinen) / [github](http://github.com/ksaa)
* Linda Liukas / [@lindaliukas](https://twitter.com/lindaliukas) / [github](http://github.com/lindaliukas)
* Vesa Vänskä / [@vesan](https://twitter.com/vesan) / [github](http://github.com/vesan)
* Terence Lee / [@hone02](https://twitter.com/hone02) / [github](http://github.com/hone)

..and all the other coaches and people making Rails Girls awesome. Please add yourself!
