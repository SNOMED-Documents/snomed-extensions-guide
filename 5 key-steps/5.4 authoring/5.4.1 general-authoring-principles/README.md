# General Authoring Principles

SNOMED CT components and reference set members are added, modified or inactivated according to the SNOMED CT editorial principles and policies.

General principles that apply to all SNOMED CT extension content include:

* Organizations may add, inactivate or modify components and reference set members, which belong to modules owned by that organization.
  * It is the responsibility of the extension producer to ensure the quality and integrity of the extension is maintained, and that all content changes are made in a module that is owned by the extension producer themselves.
  * For more information about assigning modules in extensions, please refer to the section below on _Module Assignment_.
* No changes are permitted to content of the International Release, except for the addition of new versions of this content in a module owned by the extension producer.
  * Any modifications resulting in changes to the classification of international content must be accompanied by a disclaimer notifying users of the differences between the extension edition and the International Edition. Please note that modifications of this kind pose a risk to the comparability and interoperability of data captured using different SNOMED CT editions.
  * Any substantive improvements or corrections to the content in the International Edition that is made in an extension should be forwarded to SNOMED International in a timely fashion to improve the quality of the International Edition for all users.
  * Some reference sets, which belong to the International Edition (e.g. the [| Module dependency reference set|](http://snomed.info/id/900000000000534007) and the [| Concept inactivation indicator reference set|](http://snomed.info/id/900000000000489007) ) were designed to be extended by adding new members in an extension module.
  * Other reference sets, which belong to the International Edition (e.g. [| Great Britain English language reference set|](http://snomed.info/id/900000000000012004) ) may be adapted in an extension module, following the principles described in [Authoring Reference Set Members](<../5.4.6 authoring-reference-set-members/>)

## Module Assignment

Extension producers should assign all new extension content to a module which they own. Therefore every concept, description, relationship and reference set member, which is managed within an extension, should belong to a module created and owned by the extension producer. As illustrated in the image below, this is accomplished by setting the _moduleId_ attribute in each component and reference set file to a module concept that was created by the extension producer in the given extension. Any dependencies between components or reference set members in the extension module, and components or reference set members in other modules are specified in the [module dependency reference set](<../../../4 logical-design/4.3 extensions/4.3.2 reference-sets/4.3.2.4 essential-reference-sets/4.3.2.4.2-module-dependency-reference-set.md#module-dependency-reference-set>).

<figure><img src="../../../.gitbook/assets/64264453.png" alt=""><figcaption><p>Figure 5.4.1-1: Examples of correct and incorrect module assignment in an extension</p></figcaption></figure>

For information on how to move content from one module to another, please refer to [Promotion and Demotion.](5.4.1.1-promotion-and-demotion.md)

<a href="https://docs.google.com/forms/d/e/1FAIpQLScTmbZIf0UEQwYDkY27EEWBkaiYkHSbR0_9DmFrMLXoQLyL7Q/viewform?usp=pp_url&#x26;entry.1767247133=Extension+Guide&#x26;entry.670899847=5.4.1%20General%20Authoring%20Principles" class="button primary">Provide Feedback</a>
