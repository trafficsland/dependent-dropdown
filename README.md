dependent-dropdown + supports multiple select v.1.0.1
==================

## Features

- Apply the plugin on a select element and set dependency to one or more other input / select elements (including
  dependency nesting).
- Automatically convert `select` inputs with class `depdrop` to dependent dropdowns. The plugin supports HTML5 
  data attributes to configure the dependent dropdown options.
- Automatically initialize dependent dropdowns based on preselected values (useful for update scenario).
- Supports both `select` input with basic `options` and select with `optgroups`.
- Automatically lock/disable the dependent dropdown until dependent results are available.
- The plugin uses ajax call to the server to render the list of dependent options.
- Allows a loading indicator to be displayed in dependent select until the results are fetched from the server.
- Configure your own loading progress text to be displayed for each dependent dropdown before the results are fetched from the server.
- Display a placeholder label with an empty value. For `optgroups` automatically disable this option.
- Triggers JQuery events for advanced development. Events currently available are `depdrop.init`, `depdrop.change`,
  `depdrop.beforeChange`,`depdrop.afterChange`, and  `depdrop.error`.
- Size of the entire plugin is less than 4KB (about 3KB for the minified JS and 1KB for the minified CSS).
- Ability to configure HTML attributes of each `option` element via ajax response (for example dynamically disabling some dropdown options or adding styles).

## Installation

### Using Bower
You can use the `bower` package manager to install. Run:

    bower install dependent-dropdown

### Using Composer
You can use the `composer` package manager to install. Either run:

    $ php composer.phar require trafficsland/dependent-dropdown "@dev"

or add:

    "trafficsland/dependent-dropdown": "@dev"

to your composer.json file

## License

**dependent-dropdown** is released under the BSD 3-Clause License. See the bundled `LICENSE.md` for details.
