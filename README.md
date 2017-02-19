# ng-bootstrap to Bootstrap 3

A CSS compatibility patch to make ng-bootstrap work with Bootstrap 3.  
Include this after Bootstrap 3 CSS.

## Install

* Install [ng-bootstrap](https://github.com/ng-bootstrap/ng-bootstrap)
* Install [Bootstrap v3.3.7](https://github.com/twbs/bootstrap/tree/v3.3.7)
* Install via NPM:

```sh
npm install ng-bootstrap-to-bootstrap-3
```

* Import, require, link, whatever, after Bootstrap 3 CSS. Tested with Bootstrap v3.3.7.

## Components (see linked demos)

Look for comments in the linked demo, but keep in mind that the approach is always the same:

1. Unlink Bootstrap 4, link Bootstrap 3.3.7
1. Link ng-bootstrap-to-bootstrap-3 CSS patch after Bootstrap 3.3.7
1. Use the markup from Bootstrap 3.3.7 for Angular templates
1. Use the directives, event handlers, and whatever from ng-bootstrap instead of the `data-something` ones from Bootstrap 3

- [ ] Accordion
- [ ] Alert
- [ ] Buttons
- [ ] Carousel
- [x] [Collapse](http://plnkr.co/edit/RFmsRuUJOJrcmzM6O7Bs?p=preview)
- [ ] Datepicker
- [x] [Dropdown](http://plnkr.co/edit/7BTLmeacBXrH84vExqbX?p=preview)
- [x] [Modal](http://plnkr.co/edit/ITBzkXeUfmb71afvSxmA?p=preview)
- [ ] Pagination
- [ ] Popover
- [ ] Progressbar
- [ ] Rating
- [ ] Scrollspy
- [ ] Tabs
- [ ] Timepicker
- [ ] Tooltip
- [x] [Typeahead](http://plnkr.co/edit/Nn54QCzKNcWCfd1n2kAu?p=preview)

## TODO

- (nice-to-have) Demo page a-la ng-bootstrap
