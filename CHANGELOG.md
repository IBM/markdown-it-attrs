# Change Log

This project uses [semantic versioning](http://semver.org/).

## [4.0.0-5] 2021-09-17
- tweaked utils.addAttrs() to join identically-named attributes on an element instead of only adopting one of their values

## [4.0.0-4] 2021-08-17
- tweaked utils.hasDelimiters() to not fail if an 'end' string contains a closing delimiter within its content

## [4.0.0-3] 2021-08-17
- added a custom tweaked definition of "softbreak then curly in start" to support paragraphs within list items
- resurrected support for specifying attributes for list items at the front of the list item text

## [4.0.0-2] 2021-08-11
- reverted support for specifying attributes for list items at the front of the list item text

## [4.0.0-1] 2021-08-09
- initial release as a fork of markdown-it-attrs v4.0.0 (https://github.com/arve0/markdown-it-attrs)
- added support for Attribute List Definitions
- added support for specifying attributes for list items at the front of the list item text rather than at its end
