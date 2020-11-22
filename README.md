# Aether CSS framework

**Simple, Interactive, Fun, Beautiful CSS system**

Demo: https://tomsoderlund.github.io/aether-css/

Design goals:

- A good starting point for any web/mobile/PWA project.
- Easy to customize (“themeable”). Examples:
  - Change the color of button, and hover states are automatically updated (they use `filter`).
  - Borders use transparency.
- Clear interaction states for buttons etc.
- Avoid weird classes* as much as possible, just use element names.
- Lightweight (somewhat).
- Compatible (somewhat).

*Exceptions: `.fieldset` (because of `fieldset` flexbox bug), `.tag` (tags/tokens), `.flex` (flexbox container for columns etc).


## Todo

- Code


## Install

    yarn add aether-css-framework


## Import in JavaScript

    import '../node_modules/aether-css/aether.css'
