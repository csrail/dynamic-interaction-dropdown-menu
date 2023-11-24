# Exposition
## Installation for working instance via cloning:
* Clone the repository
* Run `npm install` to install dependencies
* Run `npm run serve:open`
* Click the dropdowns

### To create a new dropdown menu:
* Create an object following the same relations as in file `data.js`
* Import the object into `index.js`
* In `index.js` file, create a new `DropdownController` object and pass data into it: `new DropdownController(dataMenuItems1)`
* Call `displayView` on the dropdown controller object.  This will return an HTML element object
* Append the HTML element object to the DOM.

## Installation for working instance via npm:
* Run `npm install @npm-csrail/dropdown-menu`
* Add `const { DropdownController } = require("@npm-csrail/dropdown-menu");` to your javascript file
* Follow steps above to create a new dropdown menu.
