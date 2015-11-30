
<!---

This README is automatically generated from the comments in these files:
paper-toast.html

Edit those files, and our readme bot will duplicate them over here!
Edit this file, and the bot will squash your changes :)

-->

[![Build Status](https://travis-ci.org/PolymerElements/paper-toast.svg?branch=master)](https://travis-ci.org/PolymerElements/paper-toast)

_[Demo and API Docs](https://elements.polymer-project.org/elements/paper-toast)_


##&lt;paper-toast&gt;


Material design: [Snackbards & toasts](https://www.google.com/design/spec/components/snackbars-toasts.html)

`paper-toast` provides a subtle notification toast. Only one `paper-toast` will
be visible on screen.

Use `opened` to show the toast:

Example:

    <paper-toast text="Hello world!" opened></paper-toast>

Also `open()` or `show()` can be used to show the toast:

Example:

    <paper-toast id="toast0" text="Welcome back!"></paper-toast>
    <button onclick="document.querySelector('#toast0').open()">Login</button>

Set `duration` to 0, a negative number or Infinity to persist the toast on screen:

Example:

    <paper-toast text="Terms and conditions" opened duration="0">
      <a href="#">Show more</a>
    </paper-toast>


### Styling
The following custom properties and mixins are available for styling:

Custom property | Description | Default
----------------|-------------|----------
`--paper-toast-background-color` | The paper-toast background-color | `#323232`
`--paper-toast-color` | The paper-toast color | `#f1f1f1`


