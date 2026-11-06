# 🎉 Party Planner: Your First Web Page

Welcome! This project is a tiny web page for planning a party. You can type a name for your event, pick a date and choose a theme colour. It's small, but it shows most of the ideas you need to start building web pages with HTML. 🧱

## 🦴 What is HTML?

HTML stands for HyperText Markup Language. It's the language every web page is built from. HTML doesn't do maths or make decisions. It just tells the browser what's on the page: this is a heading, this is a paragraph, this is a box you can type in.

You write HTML in a plain text file ending in `.html`, and a web browser like Chrome, Firefox or Safari turns it into a page you can see. ✨

## 🏷️ Tags and elements

HTML is made of tags. A tag is a word wrapped in angle brackets, like `<h1>`. Most tags come in pairs. There's an opening tag, then your content, then a closing tag with a slash:

```html
<h1>Party!</h1>
```

The whole thing together, from `<h1>` to `</h1>`, is called an element.

Some tags have nothing inside them, so they don't need a closing tag. A line break `<br>` and an input box `<input>` are two you'll see in this project.

## ⚙️ Attributes

Attributes add extra details to a tag. They sit inside the opening tag and look like `name="value"`. Here's one of the inputs from our page:

```html
<input type="text" placeholder="My Birthday" required>
```

The `type` says this box is for text. The `placeholder` shows a grey hint inside the box before you type. And `required` means the form won't send until this box is filled in.

## 🪆 Tags inside tags

Tags can live inside other tags, a bit like Russian dolls. This is called nesting. In our page, the labels and inputs all sit inside a `<form>`:

```html
<form>
    <label>Date:</label>
    <input type="date">
</form>
```

Just remember to close the inner tag before you close the outer one.

## 🏠 The shape of every page

Every HTML page follows the same basic layout:

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <!-- Info about the page goes here -->
</head>
<body>
    <!-- Everything you see goes here -->
</body>
</html>
```

The `<!DOCTYPE html>` line at the top tells the browser it's reading a modern web page. The `<html>` tag wraps everything. Inside it, the `<head>` holds behind-the-scenes info like the title on the browser tab, and the `<body>` holds everything people actually see.

Those `<!-- ... -->` bits are comments. They're notes for you, and the browser ignores them. 💬

## 🎈 How the party page works

Open [index.html](index.html) and you'll see all of this in action.

In the `<head>`, two `<meta>` tags make sure letters display properly and the page fits on phones, and the `<title>` puts "My Party" on the browser tab.

In the `<body>`, there's a big `<h1>` heading saying "Party!" and a smaller `<h2>` underneath. Then comes the `<form>`, which holds three inputs, each with a `<label>` so you know what to type. The cool part is that just by changing the `type` attribute, the same `<input>` tag becomes a text box, a date picker 📅 or a colour picker 🎨.

At the bottom there are two buttons. The submit button sends the form, and the reset button clears it. The `<br>` tags in between add some space so things don't bunch up.

## 🚀 Try it yourself

Find `index.html` in this folder and double-click it. It'll open in your browser. If you use VS Code, you can also right-click the file and choose "Open with Live Server" (if you have that extension installed), and the page will refresh every time you save.

Have a go at changing the heading text, adding a new input, or trying another `type` like `email` or `number`. Breaking things is a great way to learn! 🔧

## 📚 Key HTML tags

Here are the tags you'll use most often. Click any tag to read more about it on MDN Web Docs, a free and friendly guide to web code.

| | Tag | What it does |
| --- | --- | --- |
| 🏠 | [`<html>`](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/html) | Wraps the whole page |
| 🏠 | [`<head>`](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/head) | Holds info about the page |
| 🏠 | [`<title>`](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/title) | Sets the text on the browser tab |
| 🏠 | [`<meta>`](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/meta) | Adds extra settings for the page |
| 🏠 | [`<link>`](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/link) | Connects other files, like CSS |
| 🏠 | [`<script>`](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/script) | Adds JavaScript code |
| 🏠 | [`<body>`](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/body) | Holds everything you see |
| ✏️ | [`<h1>` to `<h6>`](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/Heading_Elements) | Headings, from biggest to smallest |
| ✏️ | [`<p>`](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/p) | A paragraph of text |
| ✏️ | [`<br>`](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/br) | A line break |
| ✏️ | [`<hr>`](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/hr) | A line across the page |
| ✏️ | [`<strong>`](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/strong) | Important text, shown in bold |
| ✏️ | [`<em>`](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/em) | Stressed text, shown in italics |
| ✏️ | [`<span>`](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/span) | Wraps a bit of text so you can style it |
| 🔗 | [`<a>`](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/a) | A link to another page |
| 🖼️ | [`<img>`](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/img) | Shows a picture |
| 🎬 | [`<video>`](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/video) | Plays a video |
| 🔊 | [`<audio>`](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/audio) | Plays sound |
| 📋 | [`<ul>`](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/ul) | A bullet-point list |
| 📋 | [`<ol>`](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/ol) | A numbered list |
| 📋 | [`<li>`](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/li) | One item in a list |
| 📊 | [`<table>`](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/table) | Makes a table |
| 📊 | [`<tr>`](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/tr) | A row in a table |
| 📊 | [`<th>`](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/th) | A heading cell |
| 📊 | [`<td>`](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/td) | A normal cell |
| 📝 | [`<form>`](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/form) | Groups inputs so they can be sent together |
| 📝 | [`<label>`](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/label) | Names an input |
| 📝 | [`<input>`](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/input) | A box or picker the user fills in |
| 📝 | [`<textarea>`](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/textarea) | A big box for longer text |
| 📝 | [`<select>`](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/select) | A drop-down menu |
| 📝 | [`<option>`](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/option) | One choice in a drop-down |
| 📝 | [`<button>`](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/button) | A button you can click |
| 📦 | [`<div>`](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/div) | A box for grouping things |
| 📦 | [`<header>`](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/header) | The top of a page or section |
| 📦 | [`<nav>`](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/nav) | A menu of links |
| 📦 | [`<main>`](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/main) | The main content of the page |
| 📦 | [`<section>`](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/section) | One part of the page |
| 📦 | [`<footer>`](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/footer) | The bottom of a page or section |

## 🧭 Keep learning

When you're ready for more, try the [MDN guide to your first website](https://developer.mozilla.org/en-US/docs/Learn_web_development/Getting_started/Your_first_website/Creating_the_content), look through the [full list of HTML elements](https://developer.mozilla.org/en-US/docs/Web/HTML/Element), or work through the [W3Schools HTML tutorial](https://www.w3schools.com/html/). Happy building! 🎊
