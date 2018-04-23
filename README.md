SupportSSO.org
=================

[![Build Status](https://travis-ci.org/theias/supportsso.svg)](https://travis-ci.org/theias/supportsso)
[![License](https://img.shields.io/badge/license-mit-blue.svg?style=flat)](/LICENSE)
[![Twitter](https://img.shields.io/badge/Twitter-@SupportSSO-blue.svg)](https://twitter.com/supportsso)

A list of popular sites and whether or not they can support SSO as a Service Provider (SP) or Identity Provider (IdP).
Based on the very-handy [twofactorauth.org](https://github.com/2factorauth/twofactorauth).

## The Goal

The goal is to build a website ([SupportSSO.org](https://supportsso.org)) with a comprehensive list of sites that support
Single Sign On, as well as the methods that they provide.

Our hope is to aid institutions who are deciding between alternative services based on their ability to integrate with
the institution's Single Sign On policy.  This can also serve as an indicator for the effort a site has put into security in general.

## Contributing

If you'd like to contribute, read the entire guidelines here in
[CONTRIBUTING.md][contrib].

## Running Locally

SupportSSO.org is built upon [Jekyll](https://jekyllrb.com/), using the [github-pages](https://github.com/github/pages-gem) gem.
In order to run the site locally, it is necessary to install bundler, install all dependencies, and then use Jekyll to serve
the site. If the `gem` command is not available to you, it is necessary to install Ruby with RubyGems.
Once Ruby and RubyGems are installed and available from the command line, SupportSSO can be setup using the following commands.

```
gem install bundler
cd ~/twofactorauth
bundle install
bundle exec jekyll serve
```

The SupportSSO website should then be accessible from `http://localhost:4000`.

Another option is to run Jekyll inside a Docker container.  Please read the [Jekyll Docker Documentation](https://github.com/envygeeks/jekyll-docker/blob/master/README.md) on how to do this.

## License

This code is distributed under the MIT license. For more info, read the
[LICENSE][license] file distributed with the source code.

[contrib]: /CONTRIBUTING.md
[license]: /LICENSE
