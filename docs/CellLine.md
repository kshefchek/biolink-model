---
layout: default
---

## cell line


None

URI: [http://bioentity.io/vocab/CellLine](http://bioentity.io/vocab/CellLine)


![img](http://yuml.me/diagram/nofunky/class/[biosample|in taxon]^-[cell line|], [cell line|]-in taxon >[organism taxon|], [ontology class|]^-[organism taxon|])
## Mappings

 * [CLO:0000031](http://purl.obolibrary.org/obo/CLO_0000031)

## Inheritance

 *  is_a: [biosample](Biosample.html)

## Children


## Used in

 *  class: [cell line to thing association](CellLineToThingAssociation.html) references: [cell line](CellLine.html)
 *  class: [cell line to disease or phenotypic feature association](CellLineToDiseaseOrPhenotypicFeatureAssociation.html) references: [cell line](CellLine.html)

## Fields

 * [id](id.html)
    * _A unique identifier for a thing. Must be either a CURIE shorthand for a URI or a complete URI_
    * __range__: identifier type
    * inherited from: [named thing](NamedThing.html)
 * [name](name.html)
    * _A human-readable name for a thing_
    * __range__: label type
    * inherited from: [named thing](NamedThing.html)
 * [category](category.html)
    * _Name of the high level ontology class in which this entity is categorized. Corresponds to the label for the biolink entity type class. In a neo4j database this MAY correspond to the neo4j label tag_
    * __range__: label type
    * inherited from: [named thing](NamedThing.html)
 * [in taxon](in_taxon.html) *subsets: translator_minimal*
    * _connects a thing to a class representing a taxon_
    * __range__: [organism taxon](OrganismTaxon.html)
    * inherited from: [thing with taxon](ThingWithTaxon.html)