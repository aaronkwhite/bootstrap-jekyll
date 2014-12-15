# Bootstrap-Jekyll

A Bare Bones [Bootstrap][1] & [Jekyll][2] site starting point that doesn't assume anything.

### Version
Current - 1.2.1

## About
This repo was created as a starting point to use [Bootstrap][1] & [Jekyll][2] to create static websites. Most [Bootstrap][1] & [Jekyll][2] scaffolds assume too much, spend less time undoing configurations geared towards building a blog and start building sites faster.

### Get Started
Clone the repo and start building your site:

```
 git clone git@github.com:aaronkwhite/bootstrap-jekyll.git project-name
```

The core components are located in the *source* directory, so you can better organize your content and stucture.

This repo is using [Bootstrap][1] [Less][3] & Font-Awesome [Less][3], located in the root directory. You'll need to setup [Compass][4] or use [Codekit][5] to compile the [Less][3] into the `source/assets/stylesheets` directory.

To test your site locally just run:

```
jekyll serve
```

*Note:* Make sure you update your git remote before you try to push any changes.

### Dependencies
 - Jekyll
 - Bootstrap (current version 3.2.0)
 - LESS Compiler


## Contributing
If you would like to contribute to this repo, hit me up on twitter [@aaronkwhite](http://twitter.com/aaronkwhite) and then we can talk pull requests.

## License

[MIT](http://opensource.org/licenses/MIT)




[1]: http://getbootstrap.com
[2]: http://jekyllrb.com
[3]: http://lesscss.org
[4]: http://compass-style.org
[5]: https://incident57.com/codekit
