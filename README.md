# Lernisto Zen

Lernisto Zen is a minimal Hugo theme with [Skeleton](https://github.com/dhg/Skeleton/) and has ~100 lines of custom CSS.

![screenshot](/images/screenshot.png)

## Installation & Usage

Clone this repository to your Hugo theme directory.

	$ git clone https://github.com/lernisto/lernisto-zen.git themes/lernisto-zen
	$ hugo server --theme=lernisto-zen --buildDrafts --watch

## Configuration

In this theme you can add variables to your site config file. The following is the example config:

	baseurl = "http://lernisto.com/"
	languageCode = "en"
	title = "lernisto.com"
	author = "Lernisto"
	copyright = "Me. All rights reserved."

	[params]
	  logo      = "/images/logo.jpg"
	  twitter   = "https://twitter.com/lernisto"
	  github    = "https://github.com/lernisto/"
	  email     = "invalid@example.com"

`copyright` may contain safe HTML, such as a link to a license.

### Hide pages from the homepage list

To exclude a page from the list on the homepage (e.g. `content/about.md`), set the following property in the page's frontmatter:

	hidefromhome = true

## License

MIT License

## Author

Originally by [OCHIISHI Koichiro](https://github.com/rakuishi)

Modified by [Terrel Shumway](https://github.com/lernisto)
