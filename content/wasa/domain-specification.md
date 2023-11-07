---
title: Domain Specification
date: 2023-04-06
type: book
weight: 3
---

A domain specification is a process to create a domain specific pattern, which is an extended subset of schema.org. schema.org is a large vocabulary that covers several domains in a shallow way. To create a domain specific pattern, the domain specification process applies an operator on schema.org to remove the types and properties that are not relevant for the given domain, defines local properties on the remaining types and applies additional constraints on the ranges and values of remaining properties. The syntax of domain specification operator is a subset of [Shapes Constraint Language (SHACL)](https://www.w3.org/TR/shacl/). The semantics is _slightly_ [different](https://drive.google.com/file/d/1BmAikrlw8lRMZWrXT1sFfHZUEPruEbcy/view). 

{{< figure src="/wasa/ds-process.svg" caption="The domain specification process." numbered="true">}}



## Relationship between SHACL and Domain Specifications

SHACL is a language that is built around the notion of *shape* in order to verify RDF graphs. A shape is either a node shape that applies constraints on nodes in an RDF graph, or a property shape that does the same to properties. In principle, we use SHACL as is, but we apply stricter syntax rules in terms of which constraint components can be applied on which type of shapes and how the shapes are interpreted (semantics). For instance, multiple target definitions are interpreted as disjunction in SHACL, but as a conjunction in domain specification approach.


{{% callout note %}}
For a domain specific pattern, please see the [LodgingBusiness](https://semantify.it/domainSpecifications/public/l49vQ318v) example. The domain specification operator as for this pattern is also [available](https://semantify.it/ds/l49vQ318v) as a SHACL shape. 
{{% /callout %}}
