---
title: Introduction
date: 2023-04-05
type: book
weight: 1
---

The schema.org vocabulary is a de facto industrial standard for creating semantically annotated data. The vocabulary with its actions subset that allows to describe not only entities on the web, but also actions that can be taken on them. The Web Service Annotation with Schema.org (WASA) language puts schema.org actions into a Web API perspective by restricting and extending it with the help of the [domain specification](#domain-specification) process for the creation of WASA APIs. 

The WASA language sees Web APIs as a collection of actions that can be taken on a graph resources. These actions can be linked explicitly, allowing clients to achieve certain goals without hardcoding the orchestration of these actions (i.e. order of action invocation). As a domain model to describe input and output parameters, we use [domain-specific patterns](#def-domain-specific-pattern) that restrict and extend the schema.org vocabulary. An API publisher can define constraints over the input and output of an action via these pattern that are defined with SHACL shapes.

{{% callout note %}}
The namespace of WASA language is **http://vocab.sti2.at/wasa/**. The suggested prefix is **wasa**.
{{% /callout %}}

{{% callout warning %}}
The http://vocab.sti2.at/wasa/ interface is under construction. For now the vocabulary can be found in [Turtle format](files/wasa/vocab/ext/WebAPIExt.ttl ':ignore').
{{% /callout %}}

Below we first give some definitions of the notions that are used in this specification. Afterward, we first introduce the domain specification approach and domain-specific patterns. We follow with the relevant types and properties of schema.org for creating Web APIs defined with WASA. We also explain the usage of WASA language from a practical perspective with a running example and give some use cases for the potential usage of the action annotations.