---
layout: layouts/base.njk
---
# Github Guide
## How to make edits to the Estate Watch website and submit them for review
{%- css %}{% include "public/css/message-box.css" %}{% endcss %}
<div class="message-box">
The Estate Watch website uses a static site generator <a href="https://www.11ty.dev/"> (11ty)</a> together with <a href="https://pages.github.com/"> Github Pages</a> to store and publish data. To edit the site you will first need to sign up for a (free) github account at <a href="https://github.com/signup"> https://github.com/signup</a>.
</div>

Once you are signed up and logged in to Github you will be able to click on any of the _'edit this page'_ links on the Estate Watch website such as the one below:

<svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor" class="bi bi-pencil-square" viewBox="0 0 16 16">
  <path d="M15.502 1.94a.5.5 0 0 1 0 .706L14.459 3.69l-2-2L13.502.646a.5.5 0 0 1 .707 0l1.293 1.293zm-1.75 2.456-2-2L4.939 9.21a.5.5 0 0 0-.121.196l-.805 2.414a.25.25 0 0 0 .316.316l2.414-.805a.5.5 0 0 0 .196-.12l6.813-6.814z"/>
  <path fill-rule="evenodd" d="M1 13.5A1.5 1.5 0 0 0 2.5 15h11a1.5 1.5 0 0 0 1.5-1.5v-6a.5.5 0 0 0-1 0v6a.5.5 0 0 1-.5.5h-11a.5.5 0 0 1-.5-.5v-11a.5.5 0 0 1 .5-.5H9a.5.5 0 0 0 0-1H2.5A1.5 1.5 0 0 0 1 2.5z"/>
</svg>
		      <a href="https://github.com/estatewatch/estatewatch/blob/main/{{ page.inputPath }}">Edit this page on GitHub</a>

The first time you click on the link, you will be asked if you want to 'fork' the repository. 

{% image "./githubfork.png", "A screenshot of github" %}

Click the green 'fork this repository' button and you will then be taken to the page you want to edit. 

> **Note:** You will only have to fork the repository once - the first time you make an edit.








