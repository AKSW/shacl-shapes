# SHACL shape repository

This repository provides SHACL shapes and shape groups. Its purpose is to be a place for collaboration to work on SHACL content together.

## Contributions welcome!

If you want to contribute, please follow the advice below.

* Use our [discovery service](https://schreckl.inspirito.de/) or browse this repository to see, that your shape is not already there.
* If **a shape already exists**, please consider improving existing one(s) instead of adding double/overlapping content.
* If **no shape is available**, fork this repository and create new folder in the **shape-infos** folder. Give it a short and meaningful name (e.g. adult-person). If unsure, look at existing folders. Put in your file(s): Split data using multiple files ([example](https://github.com/AKSW/shacl-shapes/tree/master/shape-infos/accessible-building)) or put everything into one ([example](https://github.com/AKSW/shacl-shapes/tree/master/shape-infos/adult-person)). Each way, the gathering service will put everyting into one graph later on, to make it accessible. I would suggest keeping shapes separated from meta data (see [here](https://github.com/AKSW/shacl-shapes/tree/master/shape-infos/accessible-building)).

## Develop and test shapes

There is a cool [web service](http://shacl.org/playground/) available, which helps a lot during creation of new shapes.

## License

If not stated differently, content of this repository is licensed under the terms of the [Creative Commons BY 4.0](https://creativecommons.org/licenses/by/4.0/) license (CC-BY).
