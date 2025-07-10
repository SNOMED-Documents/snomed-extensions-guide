# Preparation

Prior to creating the components or reference sets in an extension, some preliminary steps must be completed. These tasks include:

1. Obtaining a namespace identifier from SNOMED International
   * A namespace identifier is required to generate component identifiers (SCTIDs)
2. Acquiring the appropriate tools to support the creation, management, and distrbution of the extension
   * Which tools, functionalities and services are required will depend on the content of the extension
   * For more information please refer to [Tooling Requirements](5.2.1-tooling-requirements.md)
   * Note that these tools will be used to complete the steps listed below
3. Creating module(s)
   * At least one module concept is required
   * Components and reference sets which belong to the extension are assigned to the approriate module
4. Specifying module dependencies
   * These dependencies are specified using the [Module Dependency Reference Set](<../../4 logical-design/4.2 modules/4.2.2-module-dependencies.md#module-dependency-reference-set>)
   * This informs the consumers of the extension as to which additional modules are required to use/process the content of the extension
     * Note that some of these modules will come from other editions (such as the International Edition) and possibly, other extensions

The diagram below illustrates these key steps during the initial stage of extension creation.

<figure><img src="../../images/57815376.png" alt=""><figcaption><p>Prerequisites to creating an extension</p></figcaption></figure>

<a href="https://docs.google.com/forms/d/e/1FAIpQLScTmbZIf0UEQwYDkY27EEWBkaiYkHSbR0_9DmFrMLXoQLyL7Q/viewform?usp=pp_url&#x26;entry.1767247133=Extension+Guide&#x26;entry.670899847=5.2%20Preparation" class="button primary">Provide Feedback</a>
