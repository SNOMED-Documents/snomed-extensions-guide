# 5.3 Assessing Requests

Once requirements have been identified and submitted as requests for additions or changes, the extension producer need to review and assess these requests. This entails an assessment of whether the requested content is relevant for inclusion in:

  * The [International Edition](https://confluence.ihtsdotools.org/display/DOCGLOSS/International+Edition "Glossary link: International Edition")
  * A [National extension](https://confluence.ihtsdotools.org/display/DOCGLOSS/National+extension "Glossary link: National extension")
  * Another extension
  * This extension (i.e. the one being managed by this extension producer)

Requests will typically be for addition of new components (concepts, descriptions or relationships) or changes to or inactivation of existing SNOMED CT components or reference sets. However, sometimes there are requests for a completely new reference set. 

# Important Considerations

As part of the assessment process to determine where the requested content belongs, these points should be taken into consideration:

  1. The scope of various SNOMED CT Editions 
  2. Whether the request is permitted given the predefined principles around:

     1. Editorial rules and;

     2. Retaining the referential integrity of SNOMED CT

## Scope 

When a SNOMED CT Member, or Affiliate organization which maintains an extension, identifies a requirement for new content they should evaluate the request by considering the following questions:

  * Does the requested content fall within the defined scope of the International Edition?
  * Is the requested content likely to be required by, or of value to, more than one Member territory?

If the answer to both these questions is "yes", then organization should submit a request to SNOMED International for inclusion of the new content. When a request originates in an Affiliate organization, it should be submitted to a National Release Center who will then forward the request to SNOMED International. In general, this content should not be added to a National or local extension, as content that falls within the defined scope of the International Edition and is required by two or more Member territories. However, in cases where there is an urgent requirement, an extension producer may add the content to their own extension as an interim solution. Please refer to Interim Content Additions below.

Similarly, if the answer to one or both of these questions is "no", the content may be suitable for inclusion in a National Edition. In this case, the following questions should be considered: 

  * Does the requested content fall within the defined scope of a National Edition?
  * Is the requested content likely to be required by, or of value to, more than one organization within the Member territory?

If the answer to both these questions is "yes", then organization should submit a request to the National Release Center for addition of the required content into the National Edition. If the answer to one or both of these questions is "no", it should be considered for inclusion in a local extension. In situation where the request is considered to be out of scope of SNOMED CT, it may be rejected. [Table 5.3-1](https://confluence.ihtsdotools.org/display/DOCEXTPG/5.3+Assessing+Requests#Table-considerations-relating-to-appropriateness-of-content-at-various-levels "Considerations relating to appropriateness of content at various levels") provides additional detail on the various outcomes in these considerations. 

Table 5.3-1: Considerations relating to appropriateness of content at various levels

**Relevance of requested content**| **Description**  
---|---  
 _Within the scope of the International Edition_|  If the content requested is within the scope of the International Edition, the organization should request that the content should be added to the International Edition.As SNOMED CT is a global clinical terminology, the scope of the International edition of SNOMED CT is constrained by a set of principles. For inclusion in the International edition, concepts must be

  * Useful in more than one country
  * Necessary for healthcare conformance and interoperability
  * Within the scope of a clinical terminology 
  * Satisfy the criteria of being [understandable, reproducible, useful](https://confluence.ihtsdotools.org/display/DOCGLOSS/Understandability,+Reproducibility+and+Usefulness "Glossary link: Understandability, Reproducibility and Usefulness")

If there is an urgent need for additional content, it may be added to an extension as an interim measure, pending addition to the International Edition. For more information, please refer to Interim content additions below.  
_Within the scope of other extension, (National, third-party, or local extension) but outside the scope of the International Edition._|  The scope of a national edition may permit the addition of content which falls outside the scope of the International Edition but is required within a country, region or territory. If the content requested is within the scope of a national edition, a request should be submitted to the relevant National Release Center.An organization may also use an extension which was produced by another organization, such as a vendor, regional body or specialist group. In this case, requests for content which fall within the scope of these extensions should be submitted to the relevant extension producer. When there is an urgent need for additional content, it may be added to an extension as an interim measure, pending addition to a national edition or externally maintained extension. For more information, please refer to Interim content additions below.  
_Outside the scope of other extensions, but relevant to the organization requesting the content._|  An organization which maintains an extension is responsible for defining the scope of that extension. The scope of an extension should not overlap with the scope of the International Edition or any other extension with modules on which the extension modules depend on. Note that urgent content additions may be permitted as an interim measure, even when the content is within the scope of another edition or extension. For more information. please refer to Interim content additions below.Requested content which falls within the defined scope of an extension may be added by the organization which maintains the extension. For additional information about adding local content to an extension, please refer to [5.4 Authoring](5.4-Authoring_57815212.html).  
_Outside the scope of SNOMED CT_|  The request is rejected  
  
## Referential Integrity and Editorial Principles

When determining whether or not a request for additions or changes should be accepted for inclusion in any SNOMED CT edition, it is important to ensure that the addition or modification does not break the referential integrity of SNOMED CT. It is also important to assess whether the definition on new concepts has undesirable effects on the existing content. Finally, it should be ensured that every addition of or modification to SNOMED CT concepts conform to the rules specified by the concept model.  Section [5.4 Authoring](5.4-Authoring_57815212.html) describes key principles which ensure that referential integrity is retained and that components and reference sets are created or modified in an extension in accordance with the editorial principles.

SNOMED International does not recommend that extension producers make changes which result in modifications to the International release as this can cause interoperability issues. Substantive errors, or improvements to content in the International release which are mitigated by content in an extension, should therefore be forwarded to SNOMED International in a timely fashion to improve the quality of the International release.

In circumstances where the International release has been impacted by modifications in a national or local extension, a disclaimer notifying users of the differences between the extension release and the International release must accompany the national extension distribution files. 

# Interim Content Additions

Before content is added to a national or International Edition, organizations may choose to add this content to a module they own as an interim measure. In these cases, the organization should indicate, as part of the request, that an interim addition has been made, but that the content should ultimately be promoted to the International Edition. When a request for content which is relevant at the national level is submitted to a NRC that maintains a National Edition, interim content from a local extension may be promoted to that National Edition.

For example:

  * Local organizations in a country or region may add components to their local extension and then forward the request to their NRC
  * An NRC may add components in their national extension and then forward a request to SNOMED International for inclusion in the International Edition 

Note that, content added to an extension can later be promoted to another extension or to the International Edition. For more information, please refer to [5.4.1.1 Promotion and Demotion](5.4.1.1-Promotion-and-Demotion_64264454.html).

# Change Request Reporting Structure

It is the responsibility of the extension producer to determine which requests are appropriate for their extension vs those which may be appropriate at a higher level. It is therefore important that extension producers are aware of the scope and the editorial principles for the International Edition of SNOMED CT and in some cases a national edition. This will ensure that requests for changes are forwarded to the relevant organization. Furthermore, it is important that extension producers to have an established and reliable process for evaluating, processing, and overall tracking of all change requests received. The process needs to have a routing mechanism to ensure that changes applicable to the extension are made in the extension, and external change requests can be forwarded to the responsible organization, such as SNOMED International.

[Figure 5.3-1](https://confluence.ihtsdotools.org/display/DOCEXTPG/5.3+Assessing+Requests#Figure-change-request-reporting-structure- "Change request reporting structure ") illustrates the reporting structure for SNOMED International content requests. In general, only NRCs report to SNOMED International directly. Other extension producers will report to SNOMED International indirectly. However in somes cases, an extension producers may submit change requests directly to SNOMED International. For example, if the extension producer is an Affiliate, based in a non-Member territory.

<figure><img src="../../images/57815400.png" alt="" title=""><figcaption><p>Figure 5.3-1: Change request reporting structure</p></figcaption></figure>

National Release Centers are responsible for collecting requests for changes detected by Affiliates. Typically requests come from the users or consumers of the extension as they are most familiar with local requirements. Organizations within Member countries can therefore submit their requests for additions and changes to the National Release Center who will make an initial decision about the relevance of the content in the International Edition or the national edition of that country. The NRC may add content to their National Edition if they consider the relevance to be national rather than international. The NRC forwards requests with (what they consider to have) international relevance to SNOMED International for consideration.

For more information about the processes in each country, please consult the relevant [Member](https://www.snomed.org/members/) page. 

SNOMED International provides the [SNOMED CT Content Request Service](https://confluence.ihtsdotools.org/display/SCTCR/SNOMED+CT+Content+Request+Service) to gather and process requests for additions and changes to the content of the SNOMED CT International Edition. This service is directly accessible by National Release Centers (NRC) in Member countries and recognized Terminology Authorities within organizations with whom SNOMED International is actively collaborating. Requests that meet inclusion criteria for the International Release are addressed by SNOMED International staff. Some of the reasons behind International content requests are described in [Table 5.3-2](https://confluence.ihtsdotools.org/display/DOCEXTPG/5.3+Assessing+Requests#Table-reasons-for-requesting-content-to-be-added-to-the-international-edition "Reasons for requesting content to be added to the International Edition"). 

Table 5.3-2: Reasons for requesting content to be added to the International Edition

**Example use case**| **Description**  
---|---  
Gaps in coverage of scope| Clinical meanings that fall within the scope of the International Edition that are not currently represented by concepts in the International Edition  
Changes in clinical knowledge| Evolving clinical knowledge introduces clinical meanings that require the addition of new SNOMED CT concepts  
Incomplete definitions| A concept in the International Edition that is missing one or more valid defining relationships  
Missing synonyms| A concept in the International Edition that is missing one or more widely used synonymous terms  
  
If a request is deemed to have high priority, it should result in action in the next release cycle. However, requests constituting a significant change which impacts other content may take longer to implement. If a request is declined, a reason and explanation are provided to the requester, who may choose to appeal the decision to the Head of Terminology. For more information about the CRS, please refer to the [CRS User Guide](http://snomed.org/CRS-Guide). 

  

