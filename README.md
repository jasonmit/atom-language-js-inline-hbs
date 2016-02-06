# JavaScript + inline hbs support in Atom

Atom Language support for inline hbs within javascript files

![Screenshot](https://i.imgur.com/cgtmfeF.png)

## Installation

* `apm install language-js-inline-hbs`
* `apm install language-ember-htmlbars`
* Open `.js` file and make sure the document type is `JavaScript inline hbs`


## Known Limitation

You must import `htmlbars-inline-precompile` as `hbs`.  `hbs` is not dynamic but I'd be willing to accept a PR that makes it so.
