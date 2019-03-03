# AI Ontology

This repository contains an Artificial Intelligence Ontology in RDF/OWL format.

## Setup

Use the following settings you are using [WebProtege](https://webprotege.stanford.edu) to edit the RDF/OWL file.

### WebProtege Settings

**New Entity Settings**
IRI Prefix: http://www.edowson.com/ontologies/2019/02/ai#
IRI Suffix: Supplied name
Spaces: Collapse and transform to CamelCase

**New Entity Language Settings**
Annotation property: rdfs:label
Language tag: en

**Display Name Settings**
Display name property and language priority: rdfs:label, en
Display name fallback: Fallback to IRI local name

## Editing

### Specify disjoint classes axiom

Add the "OWL Entity Description Editor" view by click on the Classes tab menu and choosing it in the pop-up window.

![webprotege-classes-choose-view-owl-entity-description-editor.png](image/webprotege/webprotege-classes-choose-view-owl-entity-description-editor.png)

You can add disjoints by using the `DisjointClasses:` keyword followed by a list of classes that should be disjoint.

![webprotege-owl-entity-description-editor-paper.png](image/webprotege/webprotege-owl-entity-description-editor-paper.png)

Remember to use 'quotes' for classes that you are referring to using `rdfs:label`.

