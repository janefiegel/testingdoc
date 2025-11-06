---
title: Conversion
parent: First Attempt
nav_order: 2
---

**Introduction**

**Overview**

The Tulane University Libraries Digital Collections Metadata Guidelines (hereafter TUDC Metadata Guidelines or Metadata Guidelines) provides detailed instructions on how to create metadata for digital objects that will be ingested into the Tulane University Libraries Digital Collections. Adherence to the Metadata Guidelines is necessary to maintain and promote consistency across digital collections. Following these guidelines will improve the discoverability of digital objects, ensure a baseline of metadata quality, and increase interoperability both within the Digital Collections and with other digital libraries. The TUDC Metadata Guidelines is the most up-to-date document that outlines the standards and best practices used for metadata creation. This document updates the information previously expressed in the Tulane University Digital Library Metadata Guidelines.

The Tulane University Libraries Digital Collections uses Metadata Object Description Schema (MODS) for its digital objects metadata, specifically MODS 3.7. Local rules and preferences adhere to guidelines given in the official MODS documentation whenever possible. Additional guidance on metadata creation is pulled from standards such as Resource Description and Access (RDA) and Describing Archives: A Content Standard (DACS). Due to technical limitations and local needs, some deviations from these standards do occur; these divergences are noted when applicable in the Metadata Guidelines.

There are a number of metadata fields listed in these guidelines, though not all are expected to appear in every metadata record. The circumstances in which to use each field are identified by the field s obligation level, which will either be 'Mandatory', 'Mandatory if applicable', 'Recommended', or 'Recommended if applicable'. Explanations of the different obligations are provided below.

**Mandatory**: field must be present in an item s metadata record. All items, regardless of their properties, are required to use this field. All items, for example, must have a title.

**Mandatory if applicable**: field must be present in an item s metadata record if certain characteristics are met. Not all items will have a known creator, for example, but if an item s creator has been identified, that creator s name is required to be recorded in the metadata; if the creator is not known, that field is not required to be present in the record.

**Recommended**: field is not required to be present in an item's metadata record, but its inclusion would be beneficial to the discoverability, descriptiveness, or integrity of the metadata record.

**Recommended if applicable**: field is not required to be present in an item's metadata record, but, when certain characteristics are met, its inclusion would be beneficial to the discoverability, descriptiveness, or integrity of the metadata record.

Building on the above obligation levels, metadata fields are further categorized into one of two groups: core metadata or core conditional metadata. The main sections of the TUDC Metadata Guidelines are organized around these groupings, and explanations of each are supplied below.

**Core Metadata**: refers to all mandatory metadata fields.

**Core Conditional Metadata**: refers to all mandatory if applicable metadata fields.

**Core Expanded Metadata**: refers to all recommended and recommended if applicable metadata fields.

Core and Core Conditional Metadata constitute the mandatory minimum metadata requirements for newly ingested items in the Digital Collections. All digital projects, regardless of their content, must include metadata for every mandatory field and all relevant mandatory if applicable fields. Digital projects are encouraged to use other metadata fields beyond what is required by the mandatory minimum, and the addition of supplementary fields can be customized to meet the individual needs of each digital project. Contributors are strongly encouraged to meet with the Metadata Librarian (Jane Fiegel, jfiegel@tulane.edu) prior to beginning metadata creation so that these needs can be addressed.

TUDC Metadata Guidelines is intended to be a living document; the most up-to-date version of this document can be accessed via the Digital Collections' LibGuide. Send any questions, comments, or concerns to the Metadata Librarian, Jane Fiegel (jfiegel@tulane.edu).

**Common Abbreviations**

**MODS** Metadata Object Description Schema. This is the metadata schema used by the Tulane University Digital Library, Tulane Inside and Out, and Scholarship at Tulane sections of Tulane University Digital Collections. [This link opens to the official MODS website](https://www.loc.gov/standards/mods/).

**XML** eXtensible Markup Language. MODS metadata is expressed using this markup language. Contributors will almost never have to work directly with XML records.

**TUDC** Tulane University Libraries Digital Collections. This is an online, freely accessible resource hosted by the Tulane University Libraries that is home to distinctive content from the Tulane University community. TUDC contains seven separate sections that each hold different types of material. However, when TUDC is mentioned in the TUDC Metadata Guidelines, it refers only to three specific sections: Tulane University Digital Library, Tulane Inside and Out, and Scholarship at Tulane. [This link opens to the TUDC home page](https://library.search.tulane.edu/discovery/collectionDiscovery?vid=01TUL_INST:Tulane&inst=01TUL_INST).

**TUL** Tulane University Libraries. This is the parent organization that TUDC belongs to. TUL refers to all divisions, departments, and units in the Libraries system and not just those associated with TUDC.

**AD** Alma Digital. This, in conjunction with Primo VE, is the platform used to provide public access to the Tulane University Libraries Digital Collections. Alma Digital will have various limitations on what metadata can be displayed and how.

**Section Formatting**

This offers an overview of how each metadata field's section is arranged. Explantations for each subsection are provided.

**Name of metadata field**

_Obligation_: identifies the metadata field s level of requirement; will be either 'Mandatory' or 'Mandatory if applicable', 'Recommended', or 'Recommended if applicable'.

_MODS Definition_: definition of the associated MODS element or subelement as given by the Library of Congress s MODS Official Web Site, if one is available. '_MODS Definition_' links to the official guidelines for that specific element or subelement.

