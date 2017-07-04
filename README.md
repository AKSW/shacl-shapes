# Schreckl rules

This repository provides SHACL shapes and shape groups. Its purpose is to be a place for collaboration to work on SHACL content together. Data of this repository fuels the Schreckl [discovery service](https://schreckl.inspirito.de/) for SHACL shapes and groups.

## Contributions welcome!

If you want to contribute, please follow the advice below.

### New shapes

* Use our [discovery service](https://schreckl.inspirito.de/) or browse this repository to see, that your shape is not already there.
* If **a shape already exists**, please consider improving existing one(s) instead of adding double/overlapping content.
* If **no shape is available**, create new folder in the **rules** folder. Give it a short and meaningful name (e.g. adult-person). If unsure, look at existing folders. Put in your file(s): Split data using multiple files ([example](https://github.com/schreckl/rules/tree/master/rules/accessible-building)) or put everything into one ([example](https://github.com/schreckl/rules/tree/master/rules/adult-person)). Each way, the gathering service will put everyting into one graph later on, to make it accessible. I would suggest keep shapes separated from meta data (see [here](https://github.com/schreckl/rules/tree/master/rules/accessible-building)).

## License

If not stated differently, content of this repository is licensed under the terms of the [Creative Commons BY 4.0](https://creativecommons.org/licenses/by/4.0/) license (CC-BY).
