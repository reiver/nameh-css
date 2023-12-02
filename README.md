# nameh-css

**nameh-css** is _CSS style_ that helps make a web-page look and function like an **e-book**.
—
including dividing the text into _pages_, and making it so swiping right &amp; left (rather than scrolling down &amp; up) causes the user to go to the next page.

## Import

To import **nameh-css** into a web-page add code like the following inside the `<head>` section of the web-page:
```html
<link rel="stylesheet" href="/style/nameh-css/nameh.css" />
```

**NOTE THAT YOUR VALUE FOR THE `href` ATTRIBUTE COULD BE DIFFERENT IF YOU INSTALL `nameh-css` AT A DIFFERENT LOCATION.**

For example, if you install **nameh-css** at `"/fmt/modules/nameh-css"`, then the `<link>` code would be something like:
```html
<link rel="stylesheet" href="/fmt/modules/nameh-css/nameh.css" />
```

Etc.

## Installation

To install **nameh-css** you can either just put the `nameh.css` somewhere on your web-server.
Maybe at: "/style/nameh-css/nameh.css", or somewhere else.

Alternatively you can use a git submodule.
For example:

```
git submodule add https://sourcecode.social/reiver/nameh-css nameh-css
```

## Author

Package **nameh-css** was written by [Charles Iliya Krempeaux](http://changelog.ca)
