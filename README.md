# SoftwareCreditRoles
The goal of this vocabulary is to create a taxonomy based on existing vocabularies to represent credit of different contributors of a software project.
https://w3id.org/SoftwareCredit

# Relevant efforts that tackle credit. Please feel free suggest and discuss efforts and initiatives.

* Credit taxonomy: http://www.cell.com/pb/assets/raw/shared/guidelines/CRediT-taxonomy.pdf Is there a formalized effort for this pdf?
  * Dan thinks not
	
* DOAP ontology: https://github.com/edumbill/doap/blob/master/schema/doap.rdf recognizes some of the terms that are necessary to describe software, but lacks some terms like contributors in mailing list, code packager, etc. We extend on this ontology to fill the missing roles and 
  * There's also [SPDX](http://spdx.org), which might be being used going forward by PyPI instead of DOAP. Comment: this seems to describe software packages rather than describe the credit contributions

* PAV ontology: http://purl.org/pav/ Focused more on data rather than software, but some concepts apply.

* Dublin Core: http://dublincore.org/documents/dcmi-terms/#terms-conformsTo Used to describe bibliographic resources.
	
* CodeMeta: http://codemeta.github.io/ List of terms used in archives to describe software.

* https://github.com/akenall/Open-Contributorship-Badges/blob/master/Badge%20Files.md Credit badges from mozilla

