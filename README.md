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

1. Install Ruby with [Bundler](http://bundler.io). The minimum supported version of Ruby is 3.3.0.
2. Install dependencies from `Gemfile`:

  ```
  $ bundle install
  ```

3. Start jekyll:

  ```
  $ bundle exec jekyll serve
  ```

4. Open `http://localhost:4000` on your browser
