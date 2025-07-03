# Purpose

[SNOMED CT](https://app.gitbook.com/s/P21QucCX9Y41nBQt50ad/s/snomed-ct) is a multilingual clinical terminology that covers a broad scope of clinical concepts to an appropriate level of detail for international use. In addition, it provides an [extension](https://confluence.ihtsdotools.org/display/DOCGLOSS/Extension) mechanism that allows [SNOMED CT](https://confluence.ihtsdotools.org/display/DOCGLOSS/SNOMED+CT) to be customized to address terminology needs that are not met by the [International Edition](https://confluence.ihtsdotools.org/display/DOCGLOSS/International+Edition). This mechanism enables new [concepts](https://confluence.ihtsdotools.org/display/DOCGLOSS/Concept), [relationships](https://confluence.ihtsdotools.org/display/DOCGLOSS/Relationship), [descriptions](https://confluence.ihtsdotools.org/display/DOCGLOSS/Description) and [reference sets](https://confluence.ihtsdotools.org/display/DOCGLOSS/Reference+Set) to be added to support national or local needs.

However, not every new terminology requirement requires a [SNOMED CT extension](https://confluence.ihtsdotools.org/display/DOCGLOSS/SNOMED+CT+Extension) to be created. Potential extension producers should be aware of situations in which it is beneficial to create an extension, and situations where alternatives may be preferable. The following table provides a summary.

* New national or local content is required to meet usage requirements; or
* The content of the extension needs to be shared with other organizations; or
* The standard file format and versioning mechanism of the [release format 2](https://confluence.ihtsdotools.org/display/DOCGLOSS/release+format+2) is needed

|

* No new national or local content is required; and
* The content of the extension does not need to be shared with other organizations; and
* Non-standard formats are sufficient to support local requirements.

When a SNOMED CT extension is required, the extension may serve a range of purposes. Successful extension producers must clearly understand the requirements and purpose of their extension, before deciding which types of SNOMED CT artifacts should be included.

**Table 3-1** below shows some typical purposes for a SNOMED CT extensions. For each purpose, the table includes some common use case examples and a list of SNOMED CT artifacts that should be included. For more information about each of these purposes, please click on the corresponding diagram.

**Table 3-1: Purposes and use cases for extensions**

| \*\* Purpose \*\*                                                                                                                                                                                                                                                                                                                          | **Use Case Examples** | **Included Artifacts** |
| ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | --------------------- | ---------------------- |
| <p><a href="https://github.com/IHTSDO/extension-guide/blob/main/3%20Purpose/3.1-Add-Terms-in-Languages-and-Dialects_57814993.html"><strong>Translate SNOMED CT</strong></a>****</p><div><figure><img src="../images/57814976.png" alt=""><figcaption><p>* Adding terms used in a local language or dialect</p></figcaption></figure></div> |                       |                        |

* Adding terms used by a specific user group, such as patient friendly terms

|

* Descriptions
* Language reference sets
* Concepts (metadata only)
* Relationships (metadata only)

[**\*\*\*\*\*\* \*\***](https://github.com/IHTSDO/extension-guide/blob/main/3%20Purpose/3.2-Add-Content-to-SNOMED-CT_57814979.html)[**Manage content gaps**](https://github.com/IHTSDO/extension-guide/blob/main/3%20Purpose/3.2-Add-Content-to-SNOMED-CT_57814979.html)\*\*\*\*\*\*

<figure><img src="../images/57814974.png" alt=""><figcaption><p>* Adding components that are missing in the <a href="https://confluence.ihtsdotools.org/display/DOCGLOSS/International+Edition">International Edition</a></p></figcaption></figure>

\*\*|

* Adding concepts that are only relevant to a local context

|

* Concepts
* Descriptions
* Relationships
* Language reference sets

\*\*[Maps between SNOMED CT and other code systems](https://github.com/IHTSDO/extension-guide/blob/main/3%20Purpose/3.3-Map-Between-SNOMED-CT-and-Other-Code-Systems_57814989.html) \*

|

* Maps between statistical classification systems and SNOMED CT

|

* Map reference sets
* Concepts (metadata only)
* Descriptions (metadata only)
* Relationships (metadata only)

\*\*\*\*[Configuration of the terminology for specific use cases](https://github.com/IHTSDO/extension-guide/blob/main/3%20Purpose/3.4-Configure-SNOMED-CT-for-Specific-Use-Cases_57814991.html) \*\*\*\*

[**\* Specifying groups of components for reporting and analytics**](https://github.com/IHTSDO/extension-guide/blob/main/3%20Purpose/3.4-Configure-SNOMED-CT-for-Specific-Use-Cases_57814991.html)

|

* Linking components to clinical knowledge resources

|

* Reference sets
* Concepts (metadata only)
* Descriptions (metadata only)
* Relationships (metadata only)
