# Website for SISSA Inkwell

This repository contains source files for the SISSA Inkwell website.

## About the website

This website uses [Jekyll](https://jekyllrb.com/) for layouts and template
features. To edit this website locally on your computer and see results in
real-time, you need to install Jekyll. Setting up Jekyll involves

- installing Ruby, RubyGems, GCC and Make,
- configuring RubyGems installation directory (a user directory is
  recommended),
- installing Jekyll and Bundler as Gems.

Refer to Jekyll Docs for detailed and up to date [installation
instructions](https://jekyllrb.com/docs/installation/) for different operating
systems.

With Jekyll installed you are ready to make edits to the website. Start
by cloning the Git repository:

```
$ git clone https://github.com/11de784a/InkwellWebsite
```

Change into the cloned directory:
```
$ cd InkwellWebsite
```

Build the site and serve it locally on [http://localhost:4000](http://localhost:4000):
```
$ bundle exec jekyll serve
```

Any changes to source files will prompt a rebuild, and you can see the new
version by refreshing the page.
