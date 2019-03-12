# AI/RL Ontology

This repository contains an Artificial Intelligence / Reinforcement Learning Ontology in RDF/OWL format.

## Motivation

The AI/RL ontology project was started to help keep up with the pace of AI/RL development.

## Usage

### Using [Protege](https://protege.stanford.edu)

Load the `ed-ai.owl` file and start a reasoner.

You can update the ontology or browse the sample RL instances, to answer questions such as:

Problems encounters in reinforcement learning:
![rl-problem-compounding-errors.png](image/protege/rl-problem-compounding-errors.png)

List of RL techniques for on-policy learning:
![rl-technique-learning-technique-on-policy-evaluation.png](image/protege/rl-technique-learning-technique-on-policy-evaluation.png)

List of Q-learning algorithms and their properties:
![rl-algorithm-qlearning-algorithm-dqn.png](image/protege/rl-algorithm-qlearning-algorithm-dqn.png)

List of papers, authors and the algorithms and techniques described in those papers:
![rl-paper-human-level-control-through-deep-reinforcement-learning.png](image/protege/rl-paper-human-level-control-through-deep-reinforcement-learning.png)


### Using [WebProtege](https://webprotege.stanford.edu)

Use the following settings you are using [WebProtege](https://webprotege.stanford.edu) to edit the RDF/OWL file.

**New Entity Settings**
IRI Prefix: http://www.edowson.com/ontologies/2019/2/ai#
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
