# Logical Design

The logical design of a SNOMED CT extension is technically consistent with that of the International Edition. Both represent and version SNOMED CT components and reference sets in release files that conform to the Release Format 2 specification. This makes it easier for consumers of the International Edition to implement extensions. The image below illustrates the logical design of a typical SNOMED CT local edition and its relationship to the associated local extension, National Edition and International Edition.

<figure><img src="../.gitbook/assets/57815012.png" alt=""><figcaption><p>Logical design of a SNOMED CT local edition</p></figcaption></figure>

Every SNOMED CT extension includes one or more modules, and each module contains either SNOMED CT components or reference sets (or both). Modules may be dependent on other modules. A national or local extension uses a namespace identifier issued by SNOMED International to ensure that all extension components can be uniquely identified (across all extensions). A SNOMED CT edition includes the contents of a focus module together with the contents of all the modules on which it depends. This includes the modules in the International Edition and possibly other modules from a national and/or local extension.

The following subsections explain this logical design in more detail:

* [Namespaces](4.1-namespaces.md)
* [Modules](../4%20logical-design/4.2%20modules)
* [Extensions](../4%20logical-design/4.3%20extensions)
* [Editions](../4%20logical-design/4.4%20editions)
* [Release Packages](4.5-release-packages.md)

<a href="https://docs.google.com/forms/d/e/1FAIpQLScTmbZIf0UEQwYDkY27EEWBkaiYkHSbR0_9DmFrMLXoQLyL7Q/viewform?usp=pp_url&#x26;entry.1767247133=Extension+Guide&#x26;entry.670899847=Logical%20Design" class="button primary">Provide Feedback</a>
