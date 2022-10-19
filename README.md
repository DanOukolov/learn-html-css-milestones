# HTML and CSS Milestones

Below is a list of tasks. By mid-semester, everyone should...

1. Understand what the task is asking
1. Be able to do the task
1. Make it clear through your actions you understand what's happening

**FOR THE LOVE OF MONKEYS**, read the [Instructions](#instructions) first.







## Contents

- [Instructions](#Instructions)
- [Demonstrations](#Demonstrations)
- [Resources](#Resources)
- [Development Environment](#Development-Environment)
- [HTML Fundamentals](#HTML-Fundamentals)
- [CSS Fundamentals](#CSS-Fundamentals)
- [CSS Frameworks](#CSS-Frameworks)
- [Publishing](#Publishing)
- [Grading](#Grading)





## Instructions

1. Fork this repository
1. Complete and check off each of the tasks below, creating files and adding content where prompted with ✏️ or  **??**
1. After you finish, celebrate your HTML and CSS proficiency! 🙌



#### Notes...

- **RTM** - Sometimes I give the command you need and sometimes you have to read the documentation to find it.
- **Details** - Following the instructions. Use the filename suggestions and avoid putting everything in one giant file. It will make it hard for you to figure out what's going on.
- **Sources** - If you copy code from somewhere else, include the URL in a `<!-- comment -->` to reference it later.




## Demonstrations

The best demonstrations *show* and *tell*. Every possible way someone can interact with your code will be useful. Meaning...

1. When viewed in a browser, the page includes snippets of HTML
1. When viewed in a browser, there is text describing the snippets
1. When viewed in a code editor or via View Source, the HTML reflects what is being described




## Resources

Here are some popular tutorials/guides. You should **still look for other ones that you might like better**!

1. Shay Howe's *[Learn to Code HTML & CSS](https://learn.shayhowe.com/)*
1. Oliver James' *[HTML & CSS Is Hard (But Doesn't Have To Be)](https://www.internetingishard.com/html-and-css/)*
1. Jessica Hische and Russ Maschmeyer's *[Don't Fear The Internet](http://www.dontfeartheinternet.com/)*

Here are some more reference-like resources. These might be slightly technical, but they're accurate and comprehensive. Learning to read technical reference material is its own (very valuable) skill.

- w3schools [HTML](https://www.w3schools.com/html/) and [CSS](https://www.w3schools.com/css/)
- MDN's [HTML: Hypertext Markup Language](https://developer.mozilla.org/en-US/docs/Web/HTML)
- MDN's [CSS: Cascading Stylesheets](https://developer.mozilla.org/en-US/docs/Web/CSS)
- [HTMLReference.io](https://htmlreference.io/)
- [CSSReference.io](https://cssreference.io/)






## Development Environment

### Command Line

You should be able to...

- [x] Open this repo on the command line (Bash or Terminal) from within Github Desktop
- [x] Use `cd tests` to navigate to the tests directory
- [x] Use `ls` to list the contents of a directory
- [x] Use `mkdir empty-directory` to create an empty directory
- [x] Use `cd empty-directory`
- [x] Use `touch empty-file.html` to create an empty file
- [x] Use `cd ../` to navigate back up to the root directory of the repo
- [x] Use `Atom .` to open the current directory in your code editor


### Editing and Viewing

- [x] ✏️ Create a new (empty) HTML file named `basic-image.html` and edit it in Atom
- [x] ✏️ Write some HTML in `basic-image.html`
- [x] Open `basic-image.html` in your browser and test it locally
- [x] Use "Inspect Element" to open the developer tools and view the HTML and CSS for areas on your web page
- [x] ✏️ Add an image to the project `assets/img/` directory and display it on the webpage using the `<img>` tag







## HTML Fundamentals

### Basic Structure

Let's make sure we have the basic structure of an HTML page down. Don't worry too much about the content, here.

✏️ You should be able to create a file called `basic-structure.html` that contains the following, structured correctly:

- [x] ✏️ A `DOCTYPE` declaration
- [x] ✏️ A `<html>` tag, containing...
  - [x] ✏️ A `<head>` tag, containing...
    - [x] ✏️ A `<title>` tag with a title of your choosing
  - [x] ✏️ A `<body>` tag containing...
    - [x] ✏️ One top-level `<h1>` header
    - [x] ✏️ A few paragraphs of text in `<p>` tags
    - [x] ✏️ A second-level `<h2>` tag
    - [x] ✏️ A few more paragraphs of text in `<p>` tags


### The Anatomy of an HTML Tag

✏️ You should be able to create a properly structured HTML document named `basic-snippet.html` that talks about the following snippet:

```html
<p>
  Want to search the web?
  Try <a href="https://google.com" id="the-best-link" class="banana"  target="_blank">Google</a>!
</p>
```

In `basic-snippet.html`, you should be able to:

- [x] ✏️ Name the tags in the snippet
- [x] ✏️ Link to 2-3 online references that describe each tag, give examples, etc.
- [x] ✏️ Describe the relationship between the tags in terms of nesting ("X is a child of Y")
- [x] ✏️ Explain the relationship between `<p>` and `</p>`
- [x] ✏️ List some of the attribute names on the `<a>` tag
- [x] ✏️ For each attribute on the `<a>` tag, name its value
- [x] ✏️ For each attribute/value pair on the `<a>` tag, describe its purpose and effect


### Basic Tags

Using a single-column layout, create a page called `basic-tags.html` that contains the following sections. There should be a single `<h1>` tag for the entire page and a single `<h2>` tag for each section.

Each section should be contained in its own `<section>` tag. Do not use any CSS to style the appearance of the page. Focus just on the HTML. We will create a styled copy later that we can compare side-by-side with the unstyled copy.

You should be able to create sections that demonstrate...

- [x] The following block-level text containers:
  - [x] ✏️ The paragraph `<p>` tag
  - [x] ✏️ The blockquote `<blockquote>` tag
  - [x] ✏️ The pre-formatted text `<pre>` tag
- [x] Inline text styling using the following tags:
  - [x] ✏️ `<em>` and `<i>`
  - [x] ✏️ `<strong>` and `<b>`
  - [x] ✏️ `<code>`
- [x] ✏️ The `<a>` tag
- [x] ✏️ The `<img>` tag
- [x] ✏️ The different header tags `<h1>`, `<h2>`, `<h3>`, etc.

### Lists

Building on `basic-tags.html`, you should be able to do the following:

- [x] ✏️ Create multiple unordered lists using the `<ul>` and `<li>` tags
- [x] ✏️ Create multiple ordered lists using the `<ol>` and `<li>` tags
- [x] ✏️ Include other HTML inside the list item (`<li>`) tags, e.g., paragraphs, images, links, etc.
- [x] ✏️ Nest lists within each other

### Tables

Building on `basic-tags.html`, you should be able to create tables of varying sizes:

- [x] ✏️ Create a 3x3 table using the `<table>`, `<tr>`, and `<td>` tags
- [x] ✏️ Add headings using the `<th>` tag
- [x] ✏️ Create two more tables of different dimensions

### Multimedia

✏️ Create a page named `basic-multimedia.html` in which you:

- [x] ✏️ Use the `<video>` tag to embed one or more [video clips](https://file-examples.com/index.php/sample-video-files/)
- [x] ✏️ Use the `<audio>` tag to embed one or more [audio clips](https://file-examples.com/index.php/sample-audio-files/)






## CSS

### Common CSS Properties

✏️ You should be able to create a page called `basic-css.html` that demonstrates the following CSS properties by using a `<style>` tag to include the CSS:

- `color`
- `text-align`
- `text-transformation`
- `line-height`
- `letter-spacing`
- `font-family`
- `font-size`
- `font-style`
- `font-weight`
- `background-color`
- `background-image`
- `list-style-type`
- `width` and `height` (using an `<img>` tag)
- `margin`
- `padding`
- `border`

### Identifying CSS

In `basic-css.html`, you should be able to demonstrate the following html inside the body to use the above CSS:

- [x] Selectors...
  - [x] ✏️ Type / tag selectors
  - [x] ✏️ Class selectors
  - [x] ✏️ ID selectors
- [x] Combinators...
  - [x] ✏️ Descendant combinator
  - [x] ✏️ Child combinator

### Styling A Page

✏️ You should be able to create a copy of `basic-tags.html` called `basic-tags-styles.html` and do the following:

1. ✏️ Give each section its own distinct `id`
1. ✏️ Use a class selector to change the color of some (but not all) of the text on the page. You will need to add `class` attributes to various elements.
1. ✏️ Change the text color of the `<h2>` header in the first section using an id selector, tag selector, and child combinator
1. ✏️ Add borders to some (but not all) of the sections. Consider giving the sections you want to have borders the same `class` attribute and then using a class selector.






## CSS Frameworks

✏️ You should be able to create a new file called `index.html` and do the following:

- [x] Implement a CSS framework like [Bootstrap](https://getbootstrap.com/)
  - [x] ✏️ Find and add the Bootstrap starter template to `index.html`
  - [x] ✏️ Add a "full width" section using `.container-fluid` inside the top of `<body></body>` element

  ```html
	<div class="container-fluid">
		<div class="row">
			Add any horizontally-oriented image here
		</div>
	</div>
  ```

  - [x] ✏️ Add a new "regular width" section using `.container` underneath the full width section

  ```html
  <div class="container">
	  <div class="row">

	  </div>
  </div>
  ```

  - [x] ✏️ To the regular width section, add HTML and [Bootstrap's built-in CSS classes](https://getbootstrap.com/docs) to display a one column layout (mobile) and a three column layout (in large displays and above).
  - [x] ✏️ In the first column in the above section, add a link to each of the above html files.
  - [x] ✏️ In the second column in the above section, add a selection of [form elements](https://getbootstrap.com/docs) that use Bootstrap classes.
  - [x] ✏️ In the third column in the above section, copy your favorite quote from any of the readings thus far in this class.



## Publishing

You should be able to...


### Publish HTML/CSS to the web

- [x] Use [Github Pages](https://docs.github.com/en/github/working-with-github-pages) to publish this project to the web
- [x] Validate your [HTML](https://validator.w3.org/) and [CSS](https://jigsaw.w3.org/css-validator/)
- [x] ✏️ Replace this: [github.com/DanOukolov/learn-html-css-milestones](https://github.com/DanOukolov/learn-html-css-milestones) with your Github.com/repository url.
- [x] ✏️ Replace this: [DanOukolov.github.io/learn-html-css-milestones](https://danoukolov.github.io/learn-html-css-milestones/) with your repo's Github Page url.






<details>
<summary>Rubric</summary>

See Moodle

</details>






## Credits

This assignment was adapted from [milestones-html](https://github.com/jfarmer/milestones-html), created by [Jesse Farmer](https://github.com/jfarmer) for the DIG 245 Liberal Arts in Silicon Valley curriculum.
