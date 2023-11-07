---
title: Definitions
date: 2023-04-06
type: book
weight: 2
---

## Potential Action {#def-potential-action}
The description of an operation that can be taken on a resource. 


## Request (Active Action) {#def-potential-action}
An action instance with that is created by a [WASA Client](#def-wasa-client) to be sent to a [WASA API](#def-wasa-api)

## Completed/Failed Action {#def-completed-failed-action}
A response from a WASA API.

## Domain-specific pattern {#def-domain-specific-pattern}
An extended restriction of the schema.org vocabulary specified with a SHACL Node Shape.

## WASA API {#def-wasa-api}
A Web API that is a collection of potential actions that are created according to WASA specification. 

## WASA Client {#def-wasa-client}
A client that communicates with a [WASA API](#def-wasa-api). It processes a potential action and creates an active action based on the input specifications and constraints.

## SPARQL Property Path 
A route between two graph nodes as defined in [SPARQL 1.1 Specification](https://www.w3.org/TR/sparql11-query/#propertypaths)