# 657AA_Semantic_Web

Semantic Web Exam Project, Università di Pisa, a.y. 2020-21

The fundamental concepts in an application domain related to narratives (intended as stories about a specific topic) are: events, characters, objects and locations. Some of the facts that characterise this domain can be stated as follows:
1. A narrative is composed of one or more events.
2. A narrative is composed exclusively of events.
3. Each event occurs in exactly one location and has exactly one beginning and one ending, both represented as a datetime using the appropriate XSD datatype.
4. A character can be human or not human.
5. Each location can be a real location or a fictional location.
6. Each character, each location and each object have a name (a string).
7. Each event has at least one participating character or object.
8. Each narrative is created by at least one narrator.
9. The narrator has at least one contract with a publisher.
10. A book reports one or more narratives.
11. A book has a title (a string) and it is identified by an ISBN code (a string).
12. A book has exactly one publisher (that is an organisation). The publisher is identified by a name (a string) and an ID (a positive integer).
13. A publisher publishes more than one book.
14. A book has exactly one price (a positive integer).
15. The publisher sells the books through more than one bookshop.
16. Narrative, event, location, character, object, narrator, book, bookshop and publisher are pairwise disjoint concepts.


The candidate should express all the above statements in an OWL 2 DL ontology, using the RDF Turtle notation. In particular, the ontology must:
- Declare the required classes, providing for each class a textual label and a concise textual description of the intension of the class, using the appropriate annotation properties from the RDF Schema vocabulary
- Provide the sub-class axioms defining the class taxonomy
- Declare the required object properties, providing for each property:
    - a textual label, using the appropriate annotation property from the RDFS vocabulary
    - a textual description of the intension of the property, using the appropriate annotation propertyfrom the RDFS vocabulary
    - one axiom defining the domain of the property
    - one axiom defining the range of the property
    - one axiom defining the inverse of the property
    - any additional axioms expressing disjointness of the property with other object properties, andthe property characteristics.
- Provide the sub-property axioms defining the object property taxonomy 
- Declare the required data properties, providing:
    - a textual label, using the appropriate annotation property from the RDFS vocabulary
    - a textual description of the intension of the property, using the appropriate annotation propertyfrom the RDFS vocabulary
    - one axiom defining the domain of the property
    - one axiom defining the range of the property
    - any additional axioms expressing disjointness of the property with other data properties, andwhether the property is functional.
- Define the axioms necessary for expressing any statement in 1 to 16 that has not already been expressed.
- Populate the ontology with at least one individual for each class, and at least one assertion for each property.
