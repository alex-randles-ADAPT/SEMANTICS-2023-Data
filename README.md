# SEMANTICS-2023-Data
A  repository containing supplementary information for the submission to SEMANTICS 2023. 

**Video_Demo.mp4** is a video demonstration of the R2[RML] Framework is available. 

## Experimentation-Results
The 50 distinct RDF Concepts used during the experiment are outlined here: [Experiment_Concepts.pdf](Experiment_Concepts.pdf). These 50 mappings were retrieved from the 5 R2RML mappings containined in [/Experiment-Mappings](./Experiment-Mappings). 
### Results of Research Question 1 (RQ1) 
**RQ1** investigated the following:  *"To what extent will ChatGPT produce semantically correct data for certain values in a declarative uplift mapping (e.g. type, range, domain, descriptions)?"* 

The results are stored in **/Experiment-1-Results** and are as follows: 

- **[Type Results](./Experiment-1-Results/Type_Results.pdf)** Tested the semantic correctness of *rdf:type*. 
- **[Domain Results](./Experiment-1-Results/Domain_Results.pdf)** Tested the semantic correctness of *rdfs:domain*. 
- **[Range Results](./Experiment-1-Results/Range_Results.pdf)** Tested the semantic correctness of *rdfs:range*. 
- **[Label Results](./Experiment-1-Results/Label_Results.pdf)** Tested the semantic correctness of *rdfs:label*. 

### Results of Research Question 2 (RQ2)
**RQ2** investigated the following:  *"To what extent will ChatGPT produce syntactically valid RDF data and SPARQL queries?"* 

The results are stored in **/Experiment-2-Results** and are as follows: 
- **[Instance Graph Results](./Experiment-1-Results/Instance_Results.pdf)** Tested the syntactic correctness of generated instance graphs. 
- **[SPARQL Query Results](./Experiment-1-Results/SPARQL_Results.pdf)** Tested the syntactic correctness of generated SPARQL queries. 
- **[SHACL Shape Results](./Experiment-1-Results/SHACL_Results.pdf)** Tested the syntactic correctness of generated SHACL shape graphs. 


The directory structure is outlined below: 

```bash
├── code-generated
│   ├── instance_graphs
│   │   ├── graph_foaf_accountName .ttl
│   │   ├── graph_foaf_accountName.ttl
│   │   ├── graph_foaf_Agent.ttl
│   │   ├── graph_foaf_based_near.ttl
│   │   ├── graph_foaf_Document.ttl
│   │   ├── graph_foaf_Group.ttl
│   │   ├── graph_foaf_holdsAccount.ttl
│   │   ├── graph_foaf_knows.ttl
│   │   ├── graph_foaf_name.ttl
│   │   ├── graph_foaf_OnlineAccount.ttl
│   │   ├── graph_foaf_Person.ttl
│   │   ├── graph_prov_Activity.ttl
│   │   ├── graph_prov_Agent.ttl
│   │   ├── graph_prov_atLocation.ttl
│   │   ├── graph_prov_Collection.ttl
│   │   ├── graph_prov_Entity.ttl
│   │   ├── graph_prov_generatedAtTime.ttl
│   │   ├── graph_prov_hadMember .ttl
│   │   ├── graph_prov_hadMember.ttl
│   │   ├── graph_prov_Location.ttl
│   │   ├── graph_prov_used.ttl
│   │   ├── graph_prov_wasGeneratedAtTime.ttl
│   │   ├── graph_prov_wasGeneratedBy.ttl
│   │   ├── graph_rdf_Bag.ttl
│   │   ├── graph_rdf_first.ttl
│   │   ├── graph_rdf_HTML.ttl
│   │   ├── graph_rdf_List.ttl
│   │   ├── graph_rdf_nil.ttl
│   │   ├── graph_rdf_Property.ttl
│   │   ├── graph_rdfs_Class.ttl
│   │   ├── graph_rdfs_comment.ttl
│   │   ├── graph_rdfs_Container.ttl
│   │   ├── graph_rdfs_Datatype.ttl
│   │   ├── graph_rdfs_domain.ttl
│   │   ├── graph_rdfs_label.ttl
│   │   ├── graph_rdfs_Literal.ttl
│   │   ├── graph_rdfs_range.ttl
│   │   ├── graph_rdfs_Resource.ttl
│   │   ├── graph_rdfs_subClassOf.ttl
│   │   ├── graph_rdf_Statement.ttl
│   │   ├── graph_rdf_subject.ttl
│   │   ├── graph_rdf_type.ttl
│   │   ├── graph_rdf_value.ttl
│   │   ├── graph_skos_CollectableProperty.ttl
│   │   ├── graph_skos_Collection.ttl
│   │   ├── graph_skos_ConceptScheme.ttl
│   │   ├── graph_skos_Concept.ttl
│   │   ├── graph_skos_definition.ttl
│   │   ├── graph_skos_example.ttl
│   │   ├── graph_skos_hasTopConcept.ttl
│   │   ├── graph_skos_inScheme.ttl
│   │   ├── graph_skos_memberList.ttl
│   │   ├── graph_skos_member.ttl
│   │   ├── graph_skos_note.ttl
│   │   ├── graph_skos_OrderedCollection.ttl
│   │   ├── graph_skos_semanticRelation.ttl
│   │   ├── graph_skos_symbol.ttl
│   │   └── graph_skos_topConceptOf.ttl
│   ├── shacl_shapes
│   │   ├── shape_foaf_accountName .ttl
│   │   ├── shape_foaf_accountName.ttl
│   │   ├── shape_foaf_Agent.ttl
│   │   ├── shape_foaf_based_near.ttl
│   │   ├── shape_foaf_Document.ttl
│   │   ├── shape_foaf_Group.ttl
│   │   ├── shape_foaf_holdsAccount.ttl
│   │   ├── shape_foaf_knows.ttl
│   │   ├── shape_foaf_name.ttl
│   │   ├── shape_foaf_OnlineAccount.ttl
│   │   ├── shape_foaf_Person.ttl
│   │   ├── shape_mapping_concepts_.ttl
│   │   ├── shape_mapping_properties.ttl
│   │   ├── shape_prov_Activity.ttl
│   │   ├── shape_prov_Agent.ttl
│   │   ├── shape_prov_atLocation.ttl
│   │   ├── shape_prov_Collection.ttl
│   │   ├── shape_prov_Entity.ttl
│   │   ├── shape_prov_generatedAtTime.ttl
│   │   ├── shape_prov_hadMember .ttl
│   │   ├── shape_prov_hadMember.ttl
│   │   ├── shape_prov_Location.ttl
│   │   ├── shape_prov_used.ttl
│   │   ├── shape_prov_wasGeneratedAtTime.ttl
│   │   ├── shape_prov_wasGeneratedBy.ttl
│   │   ├── shape_rdf_Bag.ttl
│   │   ├── shape_rdf_first.ttl
│   │   ├── shape_rdf_HTML.ttl
│   │   ├── shape_rdf_List.ttl
│   │   ├── shape_rdf_nil.ttl
│   │   ├── shape_rdf_Property.ttl
│   │   ├── shape_rdfs_Class.ttl
│   │   ├── shape_rdfs_comment.ttl
│   │   ├── shape_rdfs_Container.ttl
│   │   ├── shape_rdfs_Datatype.ttl
│   │   ├── shape_rdfs_domain.ttl
│   │   ├── shape_rdfs_label.ttl
│   │   ├── shape_rdfs_Literal.ttl
│   │   ├── shape_rdfs_range.ttl
│   │   ├── shape_rdfs_Resource.ttl
│   │   ├── shape_rdfs_subClassOf.ttl
│   │   ├── shape_rdf_Statement.ttl
│   │   ├── shape_rdf_subject.ttl
│   │   ├── shape_rdf_type.ttl
│   │   ├── shape_rdf_value.ttl
│   │   ├── shape_skos_CollectableProperty.ttl
│   │   ├── shape_skos_Collection.ttl
│   │   ├── shape_skos_ConceptScheme.ttl
│   │   ├── shape_skos_Concept.ttl
│   │   ├── shape_skos_definition.ttl
│   │   ├── shape_skos_example.ttl
│   │   ├── shape_skos_hasTopConcept.ttl
│   │   ├── shape_skos_inScheme.ttl
│   │   ├── shape_skos_memberList.ttl
│   │   ├── shape_skos_member.ttl
│   │   ├── shape_skos_note.ttl
│   │   ├── shape_skos_OrderedCollection.ttl
│   │   ├── shape_skos_semanticRelation.ttl
│   │   ├── shape_skos_symbol.ttl
│   │   └── shape_skos_topConceptOf.ttl
│   └── sparql_queries
│       ├── query_foaf_accountName .rq
│       ├── query_foaf_accountName.rq
│       ├── query_foaf_Agent.rq
│       ├── query_foaf_based_near.rq
│       ├── query_foaf_Document.rq
│       ├── query_foaf_Group.rq
│       ├── query_foaf_holdsAccount.rq
│       ├── query_foaf_knows.rq
│       ├── query_foaf_name.rq
│       ├── query_foaf_OnlineAccount.rq
│       ├── query_foaf_Person.rq
│       ├── query_mapping_concepts_.rq
│       ├── query_mapping_properties.rq
│       ├── query_prov_Activity.rq
│       ├── query_prov_Agent.rq
│       ├── query_prov_atLocation.rq
│       ├── query_prov_Collection.rq
│       ├── query_prov_Entity.rq
│       ├── query_prov_generatedAtTime.rq
│       ├── query_prov_hadMember .rq
│       ├── query_prov_hadMember.rq
│       ├── query_prov_Location.rq
│       ├── query_prov_used.rq
│       ├── query_prov_wasGeneratedAtTime.rq
│       ├── query_prov_wasGeneratedBy.rq
│       ├── query_rdf_Bag.rq
│       ├── query_rdf_first.rq
│       ├── query_rdf_HTML.rq
│       ├── query_rdf_List.rq
│       ├── query_rdf_nil.rq
│       ├── query_rdf_Property.rq
│       ├── query_rdfs_Class.rq
│       ├── query_rdfs_comment.rq
│       ├── query_rdfs_Container.rq
│       ├── query_rdfs_Datatype.rq
│       ├── query_rdfs_domain.rq
│       ├── query_rdfs_label.rq
│       ├── query_rdfs_Literal.rq
│       ├── query_rdfs_range.rq
│       ├── query_rdfs_Resource.rq
│       ├── query_rdfs_subClassOf.rq
│       ├── query_rdf_Statement.rq
│       ├── query_rdf_subject.rq
│       ├── query_rdf_type.rq
│       ├── query_rdf_value.rq
│       ├── query_skos_CollectableProperty.rq
│       ├── query_skos_Collection.rq
│       ├── query_skos_Concept.rq
│       ├── query_skos_ConceptScheme.rq
│       ├── query_skos_definition.rq
│       ├── query_skos_example.rq
│       ├── query_skos_hasTopConcept.rq
│       ├── query_skos_inScheme.rq
│       ├── query_skos_memberList.rq
│       ├── query_skos_member.rq
│       ├── query_skos_note.rq
│       ├── query_skos_OrderedCollection.rq
│       ├── query_skos_semanticRelation.rq
│       ├── query_skos_symbol.rq
│       └── query_skos_topConceptOf.rq
├── documents
│   ├── Instance_results.docx
│   ├── old_documents
│   │   ├── FOAF_semantic_results.docx
│   │   ├── PROV_semantic_results.docx
│   │   ├── RDF_semantic_results.docx
│   │   ├── rdfs_Resource_semantic_results.docx
│   │   ├── RDFS_semantic_results.docx
│   │   └── SKOS_semantic_results.docx
│   ├── Overall_Results.docx
│   ├── rdfs_comment_semantic_results.docx
│   ├── rdfs_domain_semantic_results.docx
│   ├── rdfs_label_semantic_results.docx
│   ├── rdfs_range_semantic_results.docx
│   ├── rdf_type_semantic_results.docx
│   ├── SHACL_results.docx
│   └── SPARQL_results.docx
```

[![License: CC0-1.0](https://img.shields.io/badge/License-CC0_1.0-lightgrey.svg)](http://creativecommons.org/publicdomain/zero/1.0/)
