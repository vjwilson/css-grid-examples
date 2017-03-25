# css-grid-examples

These are examples for an introductory talk about CSS Grid. I was still learning grid layout as I prepared them, so don’t assume that these are the best, or most efficient, ways to implement any of these layouts. They are learning tools only.

## Getting Started

You can [download a ZIP file](http://stackoverflow.com/a/6466993) of this repository, or [clone](https://help.github.com/articles/cloning-a-repository/) it with Git.

```shell
git clone git@github.com:vjwilson/css-grid-examples.git
cd css-grid-examples
```

(If you’d like to keep your own copy of the examples in your GitHub account, be sure to [fork](https://help.github.com/articles/fork-a-repo/) the repository first.)

You can open the `index.html` file in each folder any way you normally would to preview an HTML file.

For example, on a Mac you could just type in the terminal,

```shell
open 01-cards-flexbox/index.html
```
Substitute a different folder name for `01-cards-flexbox` to open one of the other examples.

## Playing with the Styles

To keep these examples simple, I have placed the styles in the `<head>` of each HTML file, so that you can see the style and the markup it is styling very easily. You should never do this for a production site, but because CSS Grid is so new and complex, I wanted to keep these examples as simple as possible.

I recommend you start by changing some simple things, and then as you get more comfortable with the syntax, make more drastic changes.

One of the simplest changes to make is to change the size of a grid gap. Try changing this:

```css
    grid-row-gap: 10px;
```

to this:

```css
    grid-row-gap: 40px;
```
