# 2.1 - Activity 3 - Boilerplate

Time to start dealing with even MORE code!

> ----
> **Lesson 2.1 - These activities MUST be completed locally.** Learn how to
> install a free and open source in the [instructions at the start of this
> course](../../).


----------------


### Key Terms

- **boilerplate** - Code that goes at the top of every file, the standard
  "starting arrangement" for coding in a particular programming language.

    -  In some cases, it does nothing, so it's just "convention" (basically a
       way to officially say, "Hey, I'm an HTML file!", so other developers
       understand your code better)
    -  In other cases, it is important, for example to access more advanced
       features, or to fix inconsistencies in margins across different browsers


----------------


Boilerplate Buffet
---------------------


*What boilerplate HTML tags are there?*

### Boilerplate tags

- **doctype** - A special tag-like text that goes at the beginning of every
  "proper" or valid HTML file

- **html**, **head**, **body** - A set of special tags that don't do anything
  by themselves, but instead form a sort of "outline" that structures every
  "proper" or valid HTML file, as a way to keep your HTML code more
  conveniently "sorted" or arranged

### Head tags

- **title** tag - Lets you change the title in the tab or
  browser window

- **meta** - Used in a few different boilerplate statements for configuring the
  HTML document

- **link** tag - Lets you combine a separate CSS file into an
  HTML file so multiple HTML files can share the same CSS file



----------------------------------



Challenge 1: Understanding boilerplate
----------------------------------

Let's look at this hodge-podge of new tags to begin to understand HTML
boilerplate. Note that Challenge 1 and Challenge 2 both reference the same
files.

* Objective: Get practice identifying boilerplate in an HTML file.

1. Navigate to the `ch1ch2` directory. Open either the [index.html](./ch1ch2/index.html) or
[photos.html](./ch1ch2/photos.html) file in your text editor and
[browser](../act3/ch1ch2/index.html)

4. Examine the existing code & observe the results in your browser
    - It has many of the "boilerplate" code that forms the standard structure
      for "proper" HTML documents. This includes the `<!DOCTYPE html>` at the
      top, the `<html>`, `<head>`, `<body>`, and `<meta>`
    - It has a `<title>` tag which changes the window or tab title

3. Now, open the `art.html` file in your text editor and browser.

4. Examine the existing code & observe the results in your browser
    - Unlike `photos.html` and `index.html`, this one is missing boilerplate
    - _(Continued in Challenge 2...)_

-----------------


Challenge 2: Copying in boilerplate
----------------------------------

Now that we know what it looks like, let's practice adding in boilerplate to
avoid bugs in how our HTML pages are shown.  Note that Challenge 1 and
Challenge 2 both reference the same files.

* Objective: Get practice fixing missing boilerplate by copying it and pasting
  it into another HTML file.

1. Click between the pages and see if you can spot the visual differences
between the pages.
    - The title shows the default of "art.html", instead of something
      friendlier
    - Possibly: Due to lacking the `<!DOCTYPE html>` and other boilerplate, the
      text might "move over" just a little bit compared to other page (less
      default margin)
    - Possibly: Due to `art.html` not having the `<meta charset="utf8" />`
      boilerplate, the emojis might be broken on  art

2. Fix these issues by copying the boilerplate from `index.html` into
`art.html`
    - Hint: Use Copy and Paste for this! Never type by hand what you can copy
      and paste, as that reduces mistakes and speeds up coding.
    - Hint: Notice where the top and bottom of the boilerplate is, and copy it
      over to the equivalent spot in the other file

3. Finally, fix the lack of `<title>` by changing the `<title>` of `art.html`
to say: "Art projects"
    - To confirm success: Each page should be identically styled



----------------------------------



Challenge 3: Adding in a stylesheet
------------------------------------

Let's practice including a CSS file (called a "stylesheet"), and making changes
to that file.

* Objective: Get practice adding in a link tag to include a CSS file.

1. Navigate to the `ch3ch4` directory. Open either the [index.html](./ch3ch4/index.html) or
[photos.html](./ch3ch4/photos.html) file in your text editor and
[browser](../act3/ch3ch4/index.html), and also open
[`mystyles.css`](../act3/ch3ch4/mystyles.css) in just your text editor.

2. Examine the HTML and CSS files.
    - HTML: Notice how it now has a `<link>` tag that references this separate
      CSS file.
    - CSS: Notice how you don't need to write `<style>` at all, and that the
      styles here apply to the HTML page. It's much more managable this way!

3. Now, open the troublesome `art.html` file in your text editor and browser.
Observe how it is not displaying the styling.
    - Why doesn't it have styling?
        - It is missing the `<link>` tag

4. Make code modifications to the `art.html` file to solve the problem
    - Copy over the `<link>` tag `index.html` to the `art.html` file.
    - Hint: Notice where it is in the index.html. Move it to the equivalent
      spot in art.html (e.g. before the `</head>` closing tag)
    - To confirm success: Try making changes to the CSS file, refresh your
      browser (possibly, try "force refresh") and confirm that the change was
      applied to all r


------------




Challenge 4: Adding a stylesheet on top
----------------------------------

Finally, we'll practice putting it all together with adding a stylesheet "on
top of" another stylesheet. This is very useful for adding further
customizations to other people's code, or ones that only apply to some pages.
Furthermore, it lets you split up your CSS files.

* Objective: Learn how to add an "extra layer" of customizing CSS on top of an
  existing stylesheet.


1. Navigate to the `ch3ch4` directory. Open one of the HTML files again in your
editor and browser.

2. In your text editor, create a new brand new CSS file called `extrastyle.css`
    - This will be the file where we will put our "extra" styles
    - Put it next to the 

3. Create a new link in the HTML file, looking
    - This will be the file where we will put our "extra" styles


- **Note:** It could be called anything or put in any directory, but then it
  would be referenced differnetly, e.g. if it were put into a directory called
  `some/directory/path`, the result would be something like `<link
  rel="stylsheet" src="/some/other/directory/extrastyle.css">`


