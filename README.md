# WP SVN Deploy

Deploys plugins to WordPress's SVN repository.

Automatically creates a tag in Git and SVN based on the plugin's readme.txt file.

*this tool does not presently support the assets directory*

## Installation

Download and add it to your PATH

## Usage

```bash

wpsvn-deploy
```

### Options

```bash
 -n = Plugin slug name ex. page-links-to. DEFAULT: use working directory(pwd)
 -u = REQUIRED. WP SVN username
 -f = Plugin mainfile. DEFAULT: {plugin slug}.php
 -p = SVN repo path. DEFAULT: http://plugins.svn.wordpress.org/{plugin slug}
 -d = Git directory. DEFAULT: use working directory(pwd).
```

## Changelog

2013-07-13 1.0 Initial release

## License

http://opensource.org/licenses/MIT