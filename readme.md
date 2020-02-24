<p align="center">
  <img src="https://intervarsity.org/sites/all/modules/ivcf_topbar/images/IV_informal_horizontal_lockup_gradient.svg"
 alt="InterVarsity logo" width="200" height="40"></p><h2 align="center"> +</h2><p align="center"><img src="https://getbootstrap.com/docs/4.4/assets/brand/bootstrap-solid.svg" alt="Bootstrap logo" width="72" height="72"></p>

<h3 align="center">Bootstrap</h3>

<p align="center">
InterVarsity branded Bootstrap.  Sleek, intuitive, and powerful front-end framework for faster and easier web development.
  <br>

  <a href="https://getbootstrap.com/docs/4.4/"><strong>Explore Bootstrap docs »</strong></a>
  <br>
  <br>
</p>

### Project Goal
Build a customized version of Bootstrap that can be dropped in to any Bootstrap 4 project to have instant InterVarsity branding. This will also serve to standardize InterVarsity theme development around the industry standard practices of the Bootstrap framework.

## Warning:
As of 2/2020 this is highly experimental and should not be used in production. There are known issues that will cause upgrade issues that need to be resolved.

## Table of contents

- [Quick start](#quick-start)
- [Status](#status)
- [What's included](#whats-included)
- [Documentation](#documentation)
- [Contributing](#contributing)



## Quick start

---  2/2020 Instructions need to be updated and tested ---
Several quick start options are available:

- Download the latest release. This repo
- Install with [npm](https://www.npmjs.com/): `npm install bootstrap`
- Install with [yarn](https://yarnpkg.com/): `yarn add bootstrap@4.4.1`
- Install with [Composer](https://getcomposer.org/): `composer require twbs/bootstrap:4.4.1`
- Install with [NuGet](https://www.nuget.org/): CSS: `Install-Package bootstrap` Sass: `Install-Package bootstrap.sass`

Read the [Getting started page](/docs/4.4/getting-started/introduction/) for information on the framework contents, templates and examples, and more.



## What's included

Within the download you'll find the following directories and files, logically grouping common assets and providing both compiled and minified variations. You'll see something like this:

```text
bootstrap/
└── dist/
    ├── css/
    │   ├── bootstrap-grid.css
    │   ├── bootstrap-grid.css.map
    │   ├── bootstrap-grid.min.css
    │   ├── bootstrap-grid.min.css.map
    │   ├── bootstrap-reboot.css
    │   ├── bootstrap-reboot.css.map
    │   ├── bootstrap-reboot.min.css
    │   ├── bootstrap-reboot.min.css.map
    │   ├── bootstrap.css
    │   ├── bootstrap.css.map
    │   ├── bootstrap.min.css
    │   └── bootstrap.min.css.map
    └── js/
        ├── bootstrap.bundle.js
        ├── bootstrap.bundle.js.map
        ├── bootstrap.bundle.min.js
        ├── bootstrap.bundle.min.js.map
        ├── bootstrap.js
        ├── bootstrap.js.map
        ├── bootstrap.min.js
        └── bootstrap.min.js.map
```

We provide compiled CSS and JS (`bootstrap.*`), as well as compiled and minified CSS and JS (`bootstrap.min.*`). [source maps](https://developers.google.com/web/tools/chrome-devtools/javascript/source-maps) (`bootstrap.*.map`) are available for use with certain browsers' developer tools. Bundled JS files (`bootstrap.bundle.js` and minified `bootstrap.bundle.min.js`) include [Popper](https://popper.js.org/), but not [jQuery](https://jquery.com/).




## Documentation

---  2/2020 Instructions need to be updated and tested ---
Bootstrap's documentation, included in this repo in the root directory, is built with [Jekyll](https://jekyllrb.com/) and publicly hosted on GitHub Pages at <https://getbootstrap.com/>. The docs may also be run locally.



### Running documentation locally

---  2/2020 Instructions need to be updated and tested ---
1. Run through the [tooling setup](https://getbootstrap.com/docs/4.4/getting-started/build-tools/#tooling-setup) to install Jekyll (the site builder) and other Ruby dependencies with `bundle install`.
2. Run `npm install` to install Node.js dependencies.
3. Run `npm start` to compile CSS and JavaScript files, generate our docs, and watch for changes.
4. Open `http://localhost:9001` in your browser, and voilà.

Learn more about using Jekyll by reading its [documentation](https://jekyllrb.com/docs/).


## Contributing

TBD


## Community
