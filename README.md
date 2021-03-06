# Moodle Styles

## Styles for Teachers
As a teacher you can add CSS (not SCSS with $variables) code to your Moodle course. This is only possible if you change your text editor to *Plain text area* under *Preferences / Editor preferences*. The standard Atto editor will otherwise remove the CSS code.

### Examples
- [Dark Mode](moodle-teacher/dark-mode.md)

## Styles for Admins
As an admin you can add SCSS code to your theme, if you want to style the whole Moodle site. Therefor you have to go to *Site administration / Appearance / Themes / Boost (or another theme) / Advanced settings* and add the code in the text field *Raw SCSS*.

### Examples
- [Atto fix](moodle-admin/atto-fix.md)
- [Folder](moodle-admin/folder.md)
- [Navbar bottom](moodle-admin/navbar-bottom.md)
- [Logo](moodle-admin/logo.md)

## Bootstrap
Bootstrap classes can be used to easily style your content in Moodle. Look at the [documentation on Bootstrap](https://getbootstrap.com/docs/4.6/components/alerts/). Some modified examples are shown here.

### Components & Examples
- [Stretched link](bootstrap/stretched-link.md)

## Bootstrap & Ionic
Moodle uses the Bootstrap framework in the browser and the Ionic framework in the app. When Bootstrap styles are used, they are often not displayed in the app or are displayed incorrectly.

One solution is to hide the Bootstrap elements in the app with the class `.ion-hide` and to use different elements for the app, which are then hidden in the browser with the class `.d-none`.

However, it is also possible to combine both frameworks. Components for this are listed here.

### Components & Examples
- [Alert](bootstrap-ionic/alert.md)
- [Card](bootstrap-ionic/card.md)
- [Carousel](bootstrap-ionic/carousel.md)

### Copyright and license

Copyright 2021 Matthias Reike. Code released under the [MIT License](https://github.com/matthiasrke/moodle-styles/blob/main/LICENSE).

Bootstrap Code and documentation copyright 2011–2021 the [Bootstrap Authors](https://github.com/twbs/bootstrap/graphs/contributors) and [Twitter, Inc.](https://twitter.com) Code released under the [MIT License](https://github.com/twbs/bootstrap/blob/main/LICENSE). Docs released under [Creative Commons](https://creativecommons.org/licenses/by/3.0/).

Ionic Framework is released under the [MIT License](https://github.com/ionic-team/ionic-framework/blob/main/LICENSE).
