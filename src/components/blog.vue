<template>
    <div class="blog ">
        <h1>{{ title }}</h1>
        <div class="row ">
          <div class="card text-white bg-primary mb-3" style="max-width: 20rem;">
  <div class="card-header">Html</div>
  <div class="card-body">
    <h4 class="card-title">Html introduction</h4>
    <p class="card-text">The head of an HTML document is the part that is not displayed in the web browser when the page is loaded. It contains information such as the page, links to CSS (if you choose to style your HTML content with CSS), links to custom favicons, and other metadata.</p>
  </div>
</div>
<div class="card text-white bg-secondary mb-3" style="max-width: 20rem;">
  <div class="card-header">CSS</div>
  <div class="card-body">
    <h4 class="card-title">Css Introduction</h4>
    <p class="card-text">Cascading Style Sheets (CSS) is a stylesheet language used to describe the presentation of a document written in HTML or XML (including XML dialects such as SVG, MathML or XHTML). CSS describes how elements should be rendered on screen, on paper, in speech, or on other media.</p>
  </div>
</div>
<div class="card text-white bg-success mb-3" style="max-width: 20rem;">
  <div class="card-header">Javascript</div>
  <div class="card-body">
    <h4 class="card-title">javascript Introduction</h4>
    <p class="card-text">JavaScript (JS) is a lightweight, interpreted, or just-in-time compiled programming language with first-class functions. While it is most well-known as the scripting language for Web pages, many non-browser environments also use it, such as Node.js, Apache CouchDB and Adobe Acrobat. JavaScript is a prototype-based, multi-paradigm, single-threaded, dynamic language, supporting object-oriented, imperative, and declarative (e.g. functional programming.</p>
  </div>
</div>
<div class="card text-white bg-danger mb-3" style="max-width: 20rem;">
  <div class="card-header">React.js</div>
  <div class="card-body">
    <h4 class="card-title">React.js introdction</h4>
    <p class="card-text">React utilizes features of modern JavaScript for many of its patterns. Its biggest departure from JavaScript comes with the use of JSX syntax. JSX extends JavaScript's syntax so that HTML-like code can live alongside it. For example.</p>
  </div>
</div>
<div class="card text-white bg-warning mb-3" style="max-width: 20rem;">
  <div class="card-header">Angular</div>
  <div class="card-body">
    <h4 class="card-title">ANgular introduction</h4>
    <p class="card-text">Angular is built with TypeScript. TypeScript is a superset of JavaScript meaning that any valid JavaScript is valid TypeScript. TypeScript offers typing and a more concise syntax than plain JavaScript, which gives you a tool for creating more maintainable code and minimizing bugs.</p>
  </div>
</div>
<div class="card text-white bg-info mb-3" style="max-width: 20rem;">
  <div class="card-header">Vue.js</div>
  <div class="card-body">
    <h4 class="card-title">Vue.js introduction</h4>
    <p class="card-text">Vue 3 is a major release of the framework with a lot of major changes. It went into active beta in April, 2020. The biggest change is a new Composition API that works as an alternative to the current property-based API. In this new API, a single setup() function is used on the component. Only what you return from this function is available in yours. You are required to be explicit about "reactive" properties when using this API. Vue handles this for you using the Options API. This makes the new API typically considered a more advanced use case..</p>
  </div>
</div>
<div class="card bg-light mb-3" style="max-width: 20rem;">
  <div class="card-header">Next.js</div>
  <div class="card-body">
    <h4 class="card-title">Next.js introduction</h4>
    <p class="card-text">Express is a popular unopinionated web framework, written in JavaScript and hosted within the Node.js runtime environment. This module explains some of the key benefits of the framework, how to set up your development environment and how to perform common web development and deployment tasks.</p>
  </div>
</div>
<div class="card text-white bg-dark mb-3" style="max-width: 20rem;">
  <div class="card-header">Java</div>
  <div class="card-body">
    <h4 class="card-title">java introduction</h4>
    <p class="card-text">JavaScript (JS) is a lightweight, interpreted, or just-in-time compiled programming language with first-class functions. While it is most well-known as the scripting language for Web pages, many non-browser environments also use it, such as Node.js, Apache CouchDB and Adobe Acrobat. JavaScript is a prototype-based, multi-paradigm, single-threaded, dynamic language, supporting object-oriented, imperative, and declarative (e.g. functional programming) styles.</p>
  </div>
</div>
        </div>
    </div>
</template>

<script>
export default {
  name: 'blog',
  data () {
    return {
      title: 'Welcome to Your Blog Page'
    }
  }
}

</script>
