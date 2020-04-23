---
layout: ontology_detail
id: ntx
title: slim ncbi taxon onto dev
jobs:
  - id: https://travis-ci.org/pellst/ntx
    type: travis-ci
build:
  checkout: git clone https://github.com/pellst/ntx.git
  system: git
  path: "."
contact:
  email: 
  label: 
  github: 
description: slim ncbi taxon onto dev is an ontology...
domain: stuff
homepage: https://github.com/pellst/ntx
products:
  - id: ntx.owl
    name: "slim ncbi taxon onto dev main release in OWL format"
  - id: ntx.obo
    name: "slim ncbi taxon onto dev additional release in OBO format"
  - id: ntx.json
    name: "slim ncbi taxon onto dev additional release in OBOJSon format"
  - id: ntx/ntx-base.owl
    name: "slim ncbi taxon onto dev main release in OWL format"
  - id: ntx/ntx-base.obo
    name: "slim ncbi taxon onto dev additional release in OBO format"
  - id: ntx/ntx-base.json
    name: "slim ncbi taxon onto dev additional release in OBOJSon format"
dependencies:
- id: bfo
- id: ro

tracker: https://github.com/pellst/ntx/issues
license:
  url: http://creativecommons.org/licenses/by/3.0/
  label: CC-BY
activity_status: active
---

Enter a detailed description of your ontology here. You can use arbitrary markdown and HTML.
You can also embed images too.

