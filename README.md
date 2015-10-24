# felipedornelas.com

Source code for my personal website.

Powered by:

 - [Jekyll](http://jekyllrb.com), the engine behind GitHub Pages.
 - [Sass](http://sass-lang.com), a CSS pre-processor.
 - [Bourbon](http://bourbon.io), a Sass Mixin library.
 - [Neat](http://neat.bourbon.io), a responsive semantic grid framework for Sass and Bourbon.
 - [Formspree](http://formspree.io) for sending e-mails through the contact form.

Unfortunately, Jekyll messes the indentation and adds a lot of blank lines to the produced HTML/CSS content. I couldn't find a solution for this issue that is compatible with GitHub Pages.

Fonts being used (available at [Google Fonts](https://www.google.com/fonts)):

 - Oswald
 - Source Sans Pro
 - Source Code Pro
 
Icons being used:

 - [Socicon](http://www.socicon.com/)

## Setup

1. Install Ruby with [Bundler](http://bundler.io).

2. Install dependencies from `Gemfile`:

		$ bundler install

3. Start jekyll:

		$ jekyll serve --watch

4. Open `http://localhost:4000` on your browser

## Troubleshooting

If you get warnings like these:

```
/usr/local/Cellar/ruby/2.2.2/lib/ruby/2.2.0/json/version.rb:3: warning: already initialized constant JSON::VERSION
/usr/local/lib/ruby/gems/2.2.0/gems/json-1.8.3/lib/json/version.rb:3: warning: previous definition of VERSION was here
/usr/local/Cellar/ruby/2.2.2/lib/ruby/2.2.0/json/version.rb:4: warning: already initialized constant JSON::VERSION_ARRAY
/usr/local/lib/ruby/gems/2.2.0/gems/json-1.8.3/lib/json/version.rb:4: warning: previous definition of VERSION_ARRAY was here
...
```

Make sure you have only one version of the `json` gem installed. Having more than one version can lead to a conflict.