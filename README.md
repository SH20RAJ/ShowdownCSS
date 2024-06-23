# ShowdownCSS 🎨

[![License](https://img.shields.io/github/license/SH20RAJ/ShowdownCSS)](https://github.com/SH20RAJ/ShowdownCSS/blob/main/LICENSE)
[![GitHub stars](https://img.shields.io/github/stars/SH20RAJ/ShowdownCSS)](https://github.com/SH20RAJ/ShowdownCSS/stargazers)
[![GitHub issues](https://img.shields.io/github/issues/SH20RAJ/ShowdownCSS)](https://github.com/SH20RAJ/ShowdownCSS/issues)
[![Visitors](https://api.visitorbadge.io/api/visitors?path=https%3A%2F%2Fgithub.com%2FSH20RAJ%2FShowdownCSS&labelColor=%232ccce4&countColor=%23ff8a65&style=flat)](https://visitorbadge.io/status?path=https%3A%2F%2Fgithub.com%2FSH20RAJ%2FShowdownCSS)

Hey there! Welcome to ShowdownCSS, the CSS library made for styling Markdown content parsed by Showdown! 🚀 

Spice up your Markdown content! 🔥

## Features

- Styling for Markdown elements like headers, paragraphs, lists, code blocks, blockquotes, tables, links, and horizontal rules.
- Different themes available, with the default one provided.

## Installation

You can include ShowdownCSS in your project using a CDN:

```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/SH20RAJ/ShowdownCSS@main/showdown.css">
```

## Usage 🤓

1. First, make sure you have a Markdown file ready to go! 📄
2. Include ShowdownCSS in your HTML file:

    ```html
    <head>
      <link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/SH20RAJ/ShowdownCSS@main/showdown.css">
    </head>
    ```

3. Wrap your Markdown content in a div with the class `.showdowncontainer`:

    ```html
    <div class="showdowncontainer">
      <!-- Your Markdown content goes here! -->
    </div>
    ```

4. That's it! 🎉 Your Markdown content inside `.showdowncontainer` will now be styled beautifully by ShowdownCSS!

## Example 🌈

Here's a quick example of how to use ShowdownCSS:

> You can also use version specific cdn like `https://cdn.jsdelivr.net/gh/SH20RAJ/ShowdownCSS@d13e0cf619eaf668450c40fcf71afb9691f7e051/showdown.css` -> Create it from [jsDelivr](https://www.jsdelivr.com/github).

```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>ShowdownCSS Example</title>
  <link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/SH20RAJ/ShowdownCSS@main/showdown.css">
</head>
<body>

<div class="showdowncontainer">
  <h1>Hello, Markdown! 👋</h1>
  
  <p>This is **bold** and this is *italic*.</p>
  
  <ul>
    <li>Item 1</li>
    <li>Item 2</li>
    <li>Item 3</li>
  </ul>
  
  <blockquote>This is a blockquote. 🗣️</blockquote>
  
  <pre><code class="language-javascript">function hello() {
    console.log("Hello, World!");
  }</code></pre>
  
  <p>That's it! Your Markdown is now styled! 🎉</p>
</div>

</body>
</html>
```

## Themes 🎨

ShowdownCSS comes with different themes for your Markdown content. You can easily switch themes by including the theme CSS file:

### Default Theme

The default theme is applied automatically when you include `showdown.css`.

### Dark Theme

To use the Dark Theme, include the following CSS file:

```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/SH20RAJ/ShowdownCSS@main/themes/dark-theme.css">
```

### Custom Themes

ShowdownCSS welcomes contributions! If you're eager to add your own theme, feel free to contribute to the project by adding your theme file to the `themes` directory. 

### Live Demo:

Check out the live demo on [CodePen](https://codepen.io/SH20RAJ/pen/vYMapOr?editors=1000) or visit our [GitHub repository](https://github.com/SH20RAJ/ShowdownCSS) or [Dev.to post](https://dev.to/sh20raj/showdowncss-style-html-created-by-showdownjs-2lia) to learn more, explore the themes, and contribute your own ideas. 🌈

### Demo 🌐

Check out the [demo](https://sh20raj.github.io/ShowdownCSS/) to see ShowdownCSS in action! - (https://sh20raj.github.io/ShowdownCSS/)_

## About the Author 💡

ShowdownCSS is created with ❤️ by [Sh Raj](https://twitter.com/SH20RAJ).

If you have any feedback, suggestions, or questions, feel free to reach out on Twitter [@sh20raj](https://twitter.com/SH20RAJ)!

Enjoy your beautifully styled Markdown with ShowdownCSS! 🌟
