# 5.3.2.2 Model Metadata Concept Hierarchies

# Core Metadata Concept

**Hierarchy**|  [ 900000000000441003 | SNOMED CT Model Component|](http://snomed.info/id/900000000000441003 "900000000000441003 | SNOMED CT Model Component |")  
---|---  
**Purpose**|  This concept is the supertype for all SNOMED CT metadata.  
****Concept Addition Rules**  
**|  No new subtype children may be added in an extension.Please refer to the following pages for guidance on the addition of subtype descendants.  
  
  
All SNOMED CT metadata concepts are subtypes  of [ 900000000000441003 | SNOMED CT Model Component (metadata)|](http://snomed.info/id/900000000000441003 "900000000000441003 | SNOMED CT Model Component \(metadata\) |") and include concepts, descriptions and relationships that are used to describe or provide additional information about SNOMED CT content and reference sets.

[Table 5.3.2.2-1](https://confluence.ihtsdotools.org/display/DOCEXTPG/5.3.2.2+Model+Metadata+Concept+Hierarchies#Table--snomed-ct-model-component-or-metadata-sub-hierarchies-and-their-intended-purpose "Subhierarchies of |SNOMED CT Model Component| and their intended purpose") below lists the subtypes of the [ 900000000000441003 | SNOMED CT Model Component (metadata)|](http://snomed.info/id/900000000000441003 "900000000000441003 | SNOMED CT Model Component \(metadata\) |") hierarchy, and describes the content within these subhierarchies. 

Table 5.3.2.2-1: Subhierarchies of |SNOMED CT Model Component| and their intended purpose

Subhierarchy| Purpose| Link to More Information  
---|---|---  
**Core metadata concept (core metadata concept)**|  Provides structural information required to support International Edition data. This supporting information includes sets of enumerated values that apply to attributes of concepts, descriptions and relationships.| [5.3.2.2.1 Core Metadata Hierarchy](5.3.2.2.1-Core-Metadata-Hierarchy_59342969.html)  
**Foundation metadata concept (foundation metadata concept)**|  Provides supporting metadata and structural information for _Reference_  _Sets_.| [5.3.2.2.2 Foundation Metadata Concept Hierarchy](5.3.2.2.2-Foundation-Metadata-Concept-Hierarchy_59342971.html)  
**Linkage concept (linkage concept)**|  Links two or more concepts together to express compositional meanings. All  _concept_ codes that can be used as a  _Relationship Type_ are included under [ | Linkage concept|](http://snomed.info/id/106237007 "106237007 | Linkage concept |") . The attributes that are approved for use are the  _Concept Model Attributes_.| [5.3.2.2.3 Linkage Concept Hierarchy](5.3.2.2.3-Linkage-Concept-Hierarchy_59342973.html)  
**Namespace concept (namespace concept)**|  Contains _concepts_ that represent an assigned  _Extension_  _namespace identifier_. | [5.3.2.2.4 Namespaces](5.3.2.2.4-Namespaces_59342975.html)  
  
#### OWL metadata concept (OWL metadata concept)

| Contains  _concepts_ that are used in

  *  _OWL ontology reference set_ (OWL ontology header (OWL metadata concept) and OWL ontology namespace (OWL metadata concept))
  * _OWL axiom reference set_ (Disjoint classes axiom (OWL metadata concept) and General concept inclusion axiom (OWL metadata concept))

|   
[2.3. Content for the OWL Ontology Refset](https://confluence.ihtsdotools.org/display/DOCOWL/2.3.+Content+for+the+OWL+Ontology+Refset)[2.4. Content for the OWL Axiom Refset](https://confluence.ihtsdotools.org/display/DOCOWL/2.4.+Content+for+the+OWL+Axiom+Refset)  
  
The following pages provide information about the subtypes of [ 900000000000441003 | SNOMED CT Model Component (metadata)|](http://snomed.info/id/900000000000441003 "900000000000441003 | SNOMED CT Model Component \(metadata\) |") . Each page includes tables which describe the purpose of the content within one of the sub-hierarchies, with examples from the International Edition. The tables also state rules about the additions that are permitted in an extension to the respective subhierarchy. Where additions are permitted to the subheirarchy, notes are added on practical uses cases for addition, potential problems that may arise from these additions and any other relevant considerations.

  * [5.3.2.2.1 Core Metadata Hierarchy](5.3.2.2.1-Core-Metadata-Hierarchy_59342969.html)
  * [5.3.2.2.2 Foundation Metadata Concept Hierarchy](5.3.2.2.2-Foundation-Metadata-Concept-Hierarchy_59342971.html)
  * [5.3.2.2.3 Linkage Concept Hierarchy](5.3.2.2.3-Linkage-Concept-Hierarchy_59342973.html)
  * [5.3.2.2.4 Namespaces](5.3.2.2.4-Namespaces_59342975.html)

