# Introduction

## Background

SNOMED CT is a multilingual clinical terminology that covers a broad scope. However, some users may need additional concepts, relationships, descriptions or reference sets to support national, local or organizational needs.

SNOMED CT is designed to allow the International Edition to be enhanced by creating extensions to meet national or local requirements. The extension mechanism allows SNOMED CT to be customized to address the terminology needs of a country or organization that are not met by the International Edition. Extensions are managed by SNOMED International, and Members or Affiliate Licensees who have been issued a namespace identifier by SNOMED International. A namespace identifier is used to create globally unique SNOMED CT identifiers for each component (i.e. concept, description and relationship) within a Member or Affiliate extension. This ensures that references to extension concepts contained in health record data are unambiguous and can be clearly attributed to a specific issuing organization.

An extension may contain components and/or derivatives (e.g. reference sets used to represent subsets, maps or language preferences). Since the international edition and all extensions share a common structure, the same application software can be used to enter, store and process information from different extensions. Similarly, reference sets can be constructed to refer to content from both the international release and extensions. The common structure also makes it easier for content developed by an extension producer to be submitted for possible inclusion in a National Edition or the International Edition.

## Purpose

The purpose of this guide is to be a practical starting point for extension producers. It is intended to help people who need to extend and configure SNOMED CT to meet national or local requirements for clinical documentation or particular business needs. It is important that extension producers are aware of the principles and processes involved in the creation and maintenance of extensions. Consistent approaches to the development and maintenance of extensions are required to avoid variation that may form a barrier to interoperability. The objective of this guide is therefore to explain the key use cases for extensions, to clarify the logical design of extensions, and to explain the key steps and principles for creating and maintaining extensions.

## Audience

The primary audience of this guide is SNOMED International Members and other organizations that need to create, maintain and distribute SNOMED CT content using RF2.

We refer to these people and the organizations they work for as _terminology producers_ , to distinguish them from _terminology consumers_ , who use the SNOMED CT in system development, data capture, retrieval and analysis.

Although this guide is not targeted at _terminology consumers_ , it contains some material that may be of interest to them, including:

* It explains the relationship between the international, national and local content that may form part of the SNOMED CT Edition that they use.
* It provides essential guidance for _terminology consumer_ organizations that are considering whether to develop their own local extensions to configure SNOMED CT for their own use.

## Document Overview

This document presents a practical guide to SNOMED CT extensions and is structured as follows:

* [1 Executive Summary](https://github.com/IHTSDO/extension-guide/blob/main/2%20Introduction/1-Executive-Summary_57815431.html) presents the key messages from the document.
* [2 Introduction](https://github.com/IHTSDO/extension-guide/blob/main/2%20Introduction/2-Introduction_57814995.html) explains the background, purpose, scope, audience and overview of the document.
* [3 Purpose](https://github.com/IHTSDO/extension-guide/blob/main/2%20Introduction/3-Purpose_57814972.html) introduces the main purposes and key use cases for SNOMED CT extensions.
* [4 Logical Design](https://github.com/IHTSDO/extension-guide/blob/main/2%20Introduction/4-Logical-Design_57814999.html) describes the logical design of SNOMED CT extensions.
* [5 Key Steps](https://github.com/IHTSDO/extension-guide/blob/main/2%20Introduction/5-Key-Steps_57815195.html) describes the key steps involved with the creation, distribution and maintenance of an extension. As part of this, the section explains the key principles and best practices for authoring content in an extension.
