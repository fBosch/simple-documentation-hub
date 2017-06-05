# Documentation Hub
[![Build Status](https://travis-ci.org/fBosch/simple-documentation-hub.svg?branch=master)](https://travis-ci.org/fBosch/simple-documentation-hub)

The template follows a very simple convention of defining categories that correspond to sections in the navigation. Here are the default ones (they are listed in the `_config.yml`):

- `doc` - Documentation
- `ref` - Reference
- `tut` - Tutorial
- `dev` - Developers
- `post` - Posts

Start by [creating a new post](http://jekyllrb.com/docs/posts/) one of the categories listed in `_config.yml`. It will appear in the navigation on the left once recompiled. Or use the supplied script to make creating pages easier:

```bash
ruby bin/jekyll-page "Some Page Title" ref
```
