# Modules

In SNOMED CT, modules are used to organize content for maintenance and publication purposes. All concepts, descriptions, relationships, and reference set members must belong to a module. When a module is published, as part of a release package, all concepts, descriptions, relationships and reference sets that belong to that module must be published together. According to the logical design, this association between a component or reference set member and its associated module is made using the _moduleId_ attribute. The moduleId attribute refers to a concept that represents and names the module in which a component or reference set is currently maintained. All components and reference set members within a module are maintained by a single organization.

## SNOMED International Modules

The International Edition includes two modules. The core clinical components of SNOMED CT belong to the [| SNOMED CT core module|](http://snomed.info/id/900000000000207008) . Metadata components, which support the specification of the terminology, belong to the [| SNOMED CT model component module|](http://snomed.info/id/900000000000012004) . Both these modules are maintained by SNOMED International.

SNOMED International also maintains several other modules that supplement, rather that being part of, the International Edition. These include the [| SNOMED CT to ICD-10 rule-based mapping module|](http://snomed.info/id/449080006) and the [| LOINC - SNOMED CT Cooperation Project module|](http://snomed.info/id/715515008) .

## Member and Affiliate Modules

Components and reference sets maintained by Members and Affiliate licensees are also organized into one or more modules. The module concepts used for this purpose must be created and maintained by the same organization. In most cases, the module concept and its associated descriptions and relationships will belong to the same module to which its identifier refers.

## Examples

The table below lists some examples of modules, together with the organization responsible for maintaining and distributing the contents of the module. Note that the namespace identifier (highlighted in red) used in the module identifier refers to the organization who is responsible for that module. [<sup>\*1</sup>](#user-content-fn-1)[^1]

Table: Examples of modules

<table><thead><tr><th width="158.0078125" valign="top">Module Identifier</th><th valign="top">Module name</th><th valign="top">Maintained by</th></tr></thead><tbody><tr><td valign="top">449080006</td><td valign="top"><a href="http://snomed.info/id/449080006">| SNOMED CT to ICD-10 rule-based mapping module|</a></td><td valign="top">SNOMED International</td></tr><tr><td valign="top">73<mark style="color:red;">1000124</mark>108</td><td valign="top"><a href="http://snomed.info/id/731000124108">| US National Library of Medicine maintained module|</a></td><td valign="top">US National Library of Medicine – Member</td></tr><tr><td valign="top">2209<mark style="color:red;">1000087</mark>100</td><td valign="top"><a href="http://snomed.info/id/22091000087100">| Canada Health Infoway Reference Set Module|</a></td><td valign="top">Canada Health Infoway – Member</td></tr><tr><td valign="top">99900001<mark style="color:red;">1000000</mark>103</td><td valign="top"><a href="http://snomed.info/id/999000011000000103">| SNOMED CT United Kingdom clinical extension module|</a></td><td valign="top">NHS Digital (UK) – Member</td></tr></tbody></table>

The table below includes a subset of columns and rows from the description file in the 20170301 US Edition. Note that the preferred term of the moduleId is included in the table for readability.

Table: Descriptions assigned to different modules in the US Edition

<table><thead><tr><th width="133.4609375">id</th><th width="139.59765625">effectiveTime</th><th width="92.3359375">active</th><th width="145.16796875">moduleId</th><th width="149.71484375">conceptId</th><th>Term</th></tr></thead><tbody><tr><td>301485011</td><td>20170731</td><td>1</td><td><a href="http://snomed.info/id/900000000000207008">900000000000207008 | SNOMED CT core module|</a></td><td>195967001</td><td>Asthma</td></tr><tr><td>1563<mark style="color:red;">1000124</mark>116</td><td>20120301</td><td>1</td><td><a href="http://snomed.info/id/731000124108">731000124108 | US National Library of Medicine maintained module|</a></td><td>5281000124103</td><td>Persistent asthma</td></tr><tr><td>181114011</td><td>20170731</td><td>1</td><td><a href="http://snomed.info/id/900000000000012004">900000000000012004 | SNOMED CT model component module|</a></td><td>116680003</td><td>Is a</td></tr></tbody></table>

The example above reinforces some key points. Firstly, all components belong to exactly one module, as identified by the moduleId. Secondly, an edition may include components that belong to modules maintained by different organizations.

***

| <sup>\*1</sup> The module concept may, alternatively, belong to a different module maintained by the same organization. When this is the case, the module will necessarily depend upon the module that contains its identifying concept. It is therefore usually simpler to keep the module concept within the module it identifies. |
| ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |

<a href="https://docs.google.com/forms/d/e/1FAIpQLScTmbZIf0UEQwYDkY27EEWBkaiYkHSbR0_9DmFrMLXoQLyL7Q/viewform?usp=pp_url&#x26;entry.1767247133=Extension+Guide&#x26;entry.670899847=Modules" class="button primary">Provide Feedback</a>

[^1]: See footnote
