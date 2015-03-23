# RDF-Ext Primer

This is a work in progress document which explains how to use RDF-Ext and RDF Interaces.

## Basic Concepts

We assume you are familiar with basic RDF concepts like triples, graph, literals etc. If not please consult the [RDF 1.1 Primer](http://www.w3.org/TR/rdf11-primer/).

### API Documentation

Currently you need to consult the [RDF-Ext](http://bergos.github.io/rdf-ext-spec/) and [RDF Interfaces](http://www.w3.org/TR/rdf-interfaces/)  specification to get an API doc. This will hopefully change in the future.

### Store

The `Store` object is the basic abstraction of RDF-Ext. It provides ways to work with multiple graphs and access them over standardized interfaces.

### Graph