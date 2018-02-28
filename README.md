GDB
----

The General Document Builder (GDB) is an easy to use, headless document builder that can build and validate InDesign documents comprising of three parts: 


1. Modeler
====

You can see the document modeler as a [JSON Schema](http://json-schema.org/) with added functions that roughly follow the structure of the InDesign SDK. It is used to create a valid document _model_ that we can build with the _builder_ below.


2. Builder
====

The document builder takes a _model_ (An object that is validated by the _modeler_ above) and builds it.


3. Validator
====

The document validator can validate any document against a _model_.


Supported elements
----

- MasterSpreads
- Spreads
- Pages
- Margins
- Layers
- Guides

More to come!


Bugs and feature requests
----

Please use the [issue tracker](/issues) for any request. When filing a new bug, please remember to include reproduction steps including actual and expected results.

