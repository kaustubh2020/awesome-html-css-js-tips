# Awesome HTML Tips ![Awesome][awesome-badge]

#### Contents

- [HTML Native Search](#html-native-search)
- [Fieldset Element](#fieldset-element)
- [Window Opener](#window-opener)
- [Base Element](#base-element)

## HTML Native Search

```html
<div class="wrapper">
  <h1>
    Native HTML Search
  </h1>
  
  <input list="items">
  
  <datalist id="items">
    <option value="Marko Denic">
    <option value="FreeCodeCamp">
    <option value="FreeCodeTools">
    <option value="Web Development">
    <option value="Web Developer">
  </datalist>
</div>
```

[Link to Codepen](https://codepen.io/denic/pen/WNQbvbo)

## Fieldset Element

You can use <fieldset> element to group several controls as well as labels (<label>) within a web form.

```html
<form>
  <fieldset>
    <legend>Choose your favorite language</legend>

    <input type="radio" id="javascript" name="language">
    <label for="javascript">JavaScript</label><br/>

    <input type="radio" id="python" name="language">
    <label for="python">Python</label><br/>

    <input type="radio" id="java" name="language">
    <label for="java">Java</label>
  </fieldset>
</form>
```

[Link to Codepen](https://codepen.io/denic/pen/BaNXWNj)

## Window Opener

Pages opened with target=”_blank” allow the new page to access the original’s window.opener. This can have security and performance implications. Include rel=”noopener” or rel=”noreferrer” to prevent this.

```html
<a href="https://freecodetools.org" target="_blank" rel="noopener">
  Free Code Tools
</a>
```

## Base Element

If you want to open all links in the document in a new tab, you can use <base> element:

```html
<head>
   <base target="_blank">
</head>
<!-- This link will open in a new tab. -->
<div class="wrapper">
  This link will be opened in a new tab: &nbsp;
  <a href="https://freecodetools.org/">
    Free Code Tools
  </a>
</div>
```

[Link to Codepen](https://codepen.io/denic/pen/yLYYwJp)

[awesome-badge]: https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg

