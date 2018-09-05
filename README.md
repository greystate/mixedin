# MixedIn

This is a set of [{less}](http://lesscss.org) mixins and helpers that I seem to use on every project, so made sense to put them in a place that&#8217;s easy to get to.

The [docs](docs/mixins.html) are generated from the source with [Docco](http://ashkenas.com/docco/)

## "Installation"

So what I usually need, is just to get a copy of this file into whichever project I&#8217;m currently working on, *without* any history etc. from *this* repository. Instead of downloading the raw file, here's a handy tip using GitHub&#8217;s built-in support for SVN(!):

```plain
cd /path/to/current/project
svn export https://github.com/greystate/mixedin/trunk/src/less/mixins.less less/mixins.less
```

