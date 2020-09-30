#### Terminology

## Ascii vs HDF5

Avoid this false dichotomy. The opposite of Ascii is Binary.
HDF5 is a container format, as are YAML and XML.

## strict vs pragmatic

Whatever we do should be as strict as necessary and as
pragmatic as possible. These are no suitable terms for
distiguishing two formats. Anyway, there should not be
two formats, see below.

## one format, two representations

To fully specify how to store reduced reflectometry data,
we need to define a metadata dictionary (=ontology?), a
hierarchical structure (data model), and a container format.
There is consensus that we shall support two different
container formats, wrapped YAML (see below) and HDF5.

However, it would be misleading and damaging to state
that we are defining two different data formats. We
rather should talk about *one* ORSO reflectometry format
that supports two different representations, or backends.