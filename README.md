![GitHub issues](https://img.shields.io/github/issues/matt-baillie/github-button)
[![npm version](https://badgen.net/npm/v/@matt-baillie/github-button)](https://www.npmjs.com/package/@matt-baillie/gihub-button)

# \<github-button\>

Simple github button that can be use only to link github, users, projects and other stuff. Active only on https://github.com domain. With the link attribute you can set the path into the github.com world you want link to. Best use case to link the open-source project is inserted to.

<p align="center">
  <a href="#examples">examples</a> •
  <a href="#usage">usage</a> •
  <a href="#api">api</a> •
  <a href="#accessibility">accessibility</a> •
  <a href="#todo">todo</a> •
</p>

# 🕹️ Examples

![Github Button](https://raw.githubusercontent.com/CICCIOSGAMINO/web.cicciosgamino.github.io/master/public/images/githubButton.gif)

```html
<style>
  color-scheme-button {
    width: 128px;
    height: 128px;
    --background-color: purple;
    --icon-color: #333;
  }
</style>

<!-- Relative link -->
<github-button link="matt-baillie/github-button.git"> </github-button>

<!-- Absolute link -->
<github-button link="https://github.com/matt-baillie/github-button.git">
</github-button>
```

# 🚀 Usage

1. Install package

```bash
npm install --save @matt-baillie/github-button
```

2. Import

```html
<!-- Import Js Module -->
<script type="module">
  // Importing this module registers <progress-ring> as an element that you
  // can use in this page.
  //
  // Note this import is a bare module specifier, so it must be converted
  // to a path using a server such as @web/dev-server.
  import "@matt-baillie/github-button";
</script>
```

3. Place in your HTML

```html
<github-button link="https://github.com/matt-baillie/github-button.git">
</github-button>
```

# 🐝 API

## 📒 Properties/Attributes

| Name      | Type   | Default | Description                                          |
| --------- | ------ | ------- | ---------------------------------------------------- | --- | --- | --- | ----------------------------------- |
| link      | String | `''`    | Github Absolute / Relative path to user / project    |
| newwindow | String | `false` | Attribute to control whether link is opened in a new |     |     |     | window/tab or in the current window |

## Methods

_None_

## Events

_None_

## 🧁 CSS Custom Properties

| Name                 | Default | Description          |
| -------------------- | ------- | -------------------- |
| `--icon-color`       | `#000`  | SVG fill attribute   |
| `--background-color` | `#fff`  | SVG background color |

## 💪 Accessibility

Acessibility is guaranted with the use of a button with the _title_ and _aria-label_ set on it.SVG icons inside the inner button are set _role=img_,_aria-hidden="true"_,_focusable="false"_ .

## 🔧 TODO

- [ ] Better Documentation

## 🧑‍💻 Author

## Latest Editor

| [![@matt-baillie]](https://www.linkedin.com/in/matt-baillie/) |
| :-----------------------------------------------------------: |
|                       **@matt-baillie**                       |

## Original Author

| [![@cicciosgamino]](https://www.linkedin.com/in/marco-canali-859b6a52/) |
| :---------------------------------------------------------------------: |
|                           **@cicciosgamino**                            |

## Support

Reach out to me at one of the following places:

- [Github](https://github.com/matt-baillie)
- [LinkedIn](https://www.linkedin.com/in/matt-baillie/)

## Donate

Donate help and contibutions!

## License

[GNU General Public License v3.0](https://github.com/CICCIOSGAMINO/init/blob/master/LICENSE)

Made 🧑‍💻 by [@cicciosgamino](https://cicciosgamino.web.app)
