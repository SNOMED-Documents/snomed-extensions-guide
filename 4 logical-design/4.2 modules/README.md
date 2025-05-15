# 4.2 Modules

In SNOMED CT, modules are used to organize content for maintenance and publication purposes. All concepts, descriptions, relationships, and reference set members must belong to a [module](https://confluence.ihtsdotools.org/display/DOCGLOSS/module "Glossary link: module"). When a module is published, as part of a release package, all concepts, descriptions, relationships and reference sets that belong to that module must be published together. According to the logical design, this association between a component or reference set member and its associated module is made using the  _moduleId_ attribute. The moduleId attribute refers to a concept that represents and names the module in which a component or reference set is currently maintained. All components and reference set members within a module are maintained by a single organization.

# SNOMED International Modules

The [International Edition](https://confluence.ihtsdotools.org/display/DOCGLOSS/International+Edition "Glossary link: International Edition") includes two modules. The core clinical components of SNOMED CT belong to the [ | SNOMED CT core module|](http://snomed.info/id/900000000000207008 "900000000000207008 | SNOMED CT core module |") . Metadata components, which support the specification of the terminology, belong to the [ | SNOMED CT model component module|](http://snomed.info/id/900000000000012004 "900000000000012004 | SNOMED CT model component module |") . Both these modules are maintained by SNOMED International.

SNOMED International also maintains several other modules that supplement, rather that being part of, the International Edition. These include the [ | SNOMED CT to ICD-10 rule-based mapping module|](http://snomed.info/id/449080006 "449080006 | SNOMED CT to ICD-10 rule-based mapping module |") and the [ | LOINC - SNOMED CT Cooperation Project module|](http://snomed.info/id/715515008 "715515008 | LOINC - SNOMED CT Cooperation Project module |") .

# Member and Affiliate Modules

Components and reference sets maintained by [Members](https://confluence.ihtsdotools.org/display/DOCGLOSS/Member "Glossary link: Members") and [Affiliate licensees](https://confluence.ihtsdotools.org/display/DOCGLOSS/Affiliate+licensee "Glossary link: Affiliate licensees") are also organized into one or more modules. The module concepts used for this purpose must be created and maintained by the same organization. In most cases, the module concept and its associated descriptions and relationships will belong to the same module to which its identifier refers.[1](https://confluence.ihtsdotools.org/display/DOCEXTPG/4.2+Modules#Footnote1 "Footnote: Click here to display the footnote")

# Examples

[Table 4.2-1](https://confluence.ihtsdotools.org/display/DOCEXTPG/4.2+Modules#Table-examples-of-modules "Examples of modules") below lists some examples of modules, together with the organization responsible for maintaining and distributing the contents of the module. Note that the namespace identifier (highlighted in red) used in the module identifier refers to the organization who is responsible for that module. 

Table 4.2-1: Examples of modules

**Module Identifier**| **Module name**| **Maintained by**  
---|---|---  
449080006|  [ | SNOMED CT to ICD-10 rule-based mapping module|](http://snomed.info/id/449080006 "449080006 | SNOMED CT to ICD-10 rule-based mapping module |") | SNOMED International  
731000124108|  [ | US National Library of Medicine maintained module|](http://snomed.info/id/731000124108 "731000124108 | US National Library of Medicine maintained module |") | US National Library of Medicine – Member  
22091000087100|  [ | Canada Health Infoway Reference Set Module|](http://snomed.info/id/22091000087100 "22091000087100 | Canada Health Infoway Reference Set Module |") | Canada Health Infoway – Member  
999000011000000103|  [ | SNOMED CT United Kingdom clinical extension module|](http://snomed.info/id/999000011000000103 "999000011000000103 | SNOMED CT United Kingdom clinical extension module |") | NHS Digital (UK) – Member  
  
  
[Table 4.2-2](https://confluence.ihtsdotools.org/display/DOCEXTPG/4.2+Modules#Table-different-modules-in-us-edition "Descriptions assigned to different modules in the US Edition") includes a subset of columns and rows from the description file in the 20170301 US Edition. Note that the preferred term of the moduleId is included in the table for readability. 

Table 4.2-2: Descriptions assigned to different modules in the US Edition

**id**| **effectiveTime**| **active**| **moduleId**| **conceptId**| **term**  
---|---|---|---|---|---  
301485011| 20170731| 1|  [ 900000000000207008 | SNOMED CT core module|](http://snomed.info/id/900000000000207008 "900000000000207008 | SNOMED CT core module |") | 195967001|  Asthma  
15631000124116| 20120301| 1|  [ 731000124108 | US National Library of Medicine maintained module|](http://snomed.info/id/731000124108 "731000124108 | US National Library of Medicine maintained module |") | 5281000124103| Persistent asthma  
181114011| 20170731| 1|  [ 900000000000012004 | SNOMED CT model component module|](http://snomed.info/id/900000000000012004 "900000000000012004 | SNOMED CT model component module |") | 116680003| Is a  
  
The example above reinforces some key points. Firstly, all components belong to exactly one module, as identified by the moduleId. Secondly, an edition may include components that belong to modules maintained by different organizations.

* * *

Footnotes Ref | Notes  
---|---  
[1](https://confluence.ihtsdotools.org/display/DOCEXTPG/4.2+Modules#FootnoteMarker1-0 "Footnote: Click to return to reference in text") |  The module concept may, alternatively, belong to a different module maintained by the same organization. When this is the case, the module will necessarily depend upon the module that contains its identifying concept. It is therefore usually simpler to keep the module concept within the module it identifies. 
