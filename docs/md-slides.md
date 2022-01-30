## Overview

Step-by-step tutorial for creating online presentations

* Powered by [Reveal JS](https://revealjs.com/)
* Using just Markdown for slides
* Published to [ Github Pages ]( cellsummer.github.io/presentations )

---

## Creating Repository

* Create a new github repo later used for hosting the presentation
* Clone to local for further editing

---

## Reveal JS

* Following the Reveal JS [installation steps](https://revealjs.com/installation/)
* Rename the Reveal folder to be "docs"
* It contains a default presentation (index.html) and a demo presentation (demo.html) out-of-box

---

## Creating Slides

* Change your slide title

```html
<title>My Markrdown Sliddes</title>
```

* Use external markdown file 

```html
<div class="reveal">
<div class="slides">
  <section
    data-markdown='md-slides.md'
    data-separator="---\r\n"
    data-separator-vertical="\n\n\n"
    data-separator-notes="^Note:"
    data-charset="utf-8">
  </section>
</div>
```
* Use md-slides.md to write your slides
 
---

## Local Preview

* Install dependencies

```ps
cd docs && npm install
```
* Serve presentation locally

```ps
npm start
```
---

## Deploy to Github Pages

* Commit and push your local repo to Github

* Use "Pages" setting to publish to github.io

