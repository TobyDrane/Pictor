# Pictor [WIP]

Pictor is my core css library that I am trying to rollout to all my small hackathon type of projects. The idea is to build a very small, minimal css library that can be imported from a single cdn. It will provide the base styling for typography, buttons, forms and some base page structure such as navbars, forms and grids.

This project is being built iteratively and so when a new css item is needed due to a request from another project, it is added to this repo.

## Current Project Status

- [x] Base Typography
- [x] Simple Buttons
- [x] Light / Dark Theming
- [x] Text Inputs
- [ ] Form Structure
- [ ] Navbar Structure
- [ ] Grid Structure
- [ ] Sections and Containers
- [ ] Utility Classes
- [ ] Cards
- [ ] Spinner
- [ ] Images

## Theming

Pictor is designed to be theme customisable. The first customisation one can make is by applying a light or dark mode. This is done by passing the relevant `light-mode` or `dark-mode` class to the document body.

```
<body class='light-mode'>

</body>
```

Pictor automatically detects this class and applies the inverted color palette.

All the colors can be changed by css variables. See the `pictor.css` file for the list of colors for both light and inverted dark theme.
