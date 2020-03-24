<p align="center">
  <img alt="Logo" src="docs/static/logo-readme.png" height="91" width="112">
  <h1 align="center">Animated hamburger icons for React</h1>
</p>

[Hamburger icons](https://hamburger-react.netlify.com) with CSS-driven transitions, created to be as elegant and performant as possible. This means no JavaScript animations, transitions on non-cheap properties and a small footprint KB-wise.

## Yet another hamburger library?
Yes. The decision to create this small package was made because existing solutions seem to have one or more of the following problems:

- Animations that don't feel natural
- Transitions on expensive properties (jerky animations)
- No React support
- Size (additional dependencies besides React or not tree-shakable)
- Not customizable, or too customizable (no sensible defaults)
- Doing too much

## Installation
```sh
npm install hamburger-react
```

## Usage
[Visit the website](https://hamburger-react.netlify.com) for full documentation, API and examples. A basic implementation looks as follows:

```js
import Hamburger from 'hamburger-react'

<Hamburger onToggle={toggled => ...} />
```

## Accessibility
It is recommended to have a tap/click area of at least 48x48 pixels. Therefore, padding will be added around the icon to create a surface of exactly this size.

Keyboard interaction is provided with the `enter` key, and the icon element has the recommended accessibility attributes (such as `role`).

## Support
The icons are hooks-based, and will work with React 16.8.0 ('the one with hooks') or higher.

## Credits
Logo by [Stutpak](https://www.stutpak.nl).
