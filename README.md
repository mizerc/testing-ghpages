# testing-ghpages

## No need to have jekyll to publish to gh-pages

To opt out of jekyll's build process you just add an empty file named .nojekyll to the root of your repo. GitHub pages will see that and just serve your HTML, CSS, and JS without processing it.

You can also just put HTML, CSS, and JS in the repo and it'll work.

Just make sure your main page is in a file named "index.html" and you've selected the correct source branch in your repo settings. It'll still be built by Jekyll if you don't have a .nojekyll file, but Jekyll works with plain html, css, and js so it's not something to worry about. 