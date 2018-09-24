# Slot: subject


connects an association to the subject of the association. For example, in a gene-to-phenotype association, the gene is subject and phenotype is object.

URI: [http://bioentity.io/vocab/subject](slot_uri)
## Mappings

 * [rdf:subject](http://purl.obolibrary.org/obo/rdf_subject)
 * [owl:annotatedSource](http://purl.obolibrary.org/obo/owl_annotatedSource)
 * [oban:association_has_subject](http://purl.obolibrary.org/obo/oban_association_has_subject)
## Domain and Range

[Association](Association.md) -> **string**
## Inheritance

 *  is_a: [association slot](association_slot.md)
## Children

 *  child: [chemical to thing association.subject](chemical_to_thing_association_subject.md)
 *  child: [case to thing association.subject](case_to_thing_association_subject.md)
 *  child: [sequence feature relationship.subject](sequence_feature_relationship_subject.md)
 *  child: [variant to phenotypic feature association.subject](variant_to_phenotypic_feature_association_subject.md)
 *  child: [anatomical entity to anatomical entity association.subject](anatomical_entity_to_anatomical_entity_association_subject.md)
 *  child: [variant to disease association.subject](variant_to_disease_association_subject.md)
 *  child: [biosample to thing association.subject](biosample_to_thing_association_subject.md)
 *  child: [disease or phenotypic feature association to thing association.subject](disease_or_phenotypic_feature_association_to_thing_association_subject.md)
 *  child: [cell line to thing association.subject](cell_line_to_thing_association_subject.md)
 *  child: [model to disease mixin.subject](model_to_disease_mixin_subject.md)
 *  child: [population to population association.subject](population_to_population_association_subject.md)
 *  child: [pairwise interaction association.subject](pairwise_interaction_association_subject.md)
 *  child: [environment to phenotypic feature association.subject](environment_to_phenotypic_feature_association_subject.md)
 *  child: [genotype to variant association.subject](genotype_to_variant_association_subject.md)
 *  child: [gene to expression site association.subject](gene_to_expression_site_association_subject.md)
 *  child: [variant to thing association.subject](variant_to_thing_association_subject.md)
 *  child: [genotype to thing association.subject](genotype_to_thing_association_subject.md)
 *  child: [gene to gene association.subject](gene_to_gene_association_subject.md)
 *  child: [functional association.subject](functional_association_subject.md)
 *  child: [genomic sequence localization.subject](genomic_sequence_localization_subject.md)
 *  child: [gene to phenotypic feature association.subject](gene_to_phenotypic_feature_association_subject.md)
 *  child: [sequence variant modulates treatment association.subject](sequence_variant_modulates_treatment_association_subject.md)
 *  child: [gene to thing association.subject](gene_to_thing_association_subject.md)
 *  child: [genotype to phenotypic feature association.subject](genotype_to_phenotypic_feature_association_subject.md)
 *  child: [variant to population association.subject](variant_to_population_association_subject.md)
 *  child: [genotype to gene association.subject](genotype_to_gene_association_subject.md)
 *  child: [gene regulatory relationship.subject](gene_regulatory_relationship_subject.md)
 *  child: [genotype to genotype part association.subject](genotype_to_genotype_part_association_subject.md)
 *  child: [disease to thing association.subject](disease_to_thing_association_subject.md)
 *  child: [cell line to disease or phenotypic feature association.subject](cell_line_to_disease_or_phenotypic_feature_association_subject.md)
 *  child: [gene to disease association.subject](gene_to_disease_association_subject.md)
## Used in

 *  usage: [CellLineToThingAssociation](CellLineToThingAssociation.md)
 *  usage: [ChemicalToThingAssociation](ChemicalToThingAssociation.md)
 *  usage: [ChemicalToPathwayAssociation](ChemicalToPathwayAssociation.md)
 *  usage: [GenotypeToGenotypePartAssociation](GenotypeToGenotypePartAssociation.md)
 *  usage: [AnatomicalEntityToAnatomicalEntityOntogenicAssociation](AnatomicalEntityToAnatomicalEntityOntogenicAssociation.md)
 *  usage: [GenotypeToPhenotypicFeatureAssociation](GenotypeToPhenotypicFeatureAssociation.md)
 *  usage: [CellLineToDiseaseOrPhenotypicFeatureAssociation](CellLineToDiseaseOrPhenotypicFeatureAssociation.md)
 *  usage: [VariantToPopulationAssociation](VariantToPopulationAssociation.md)
 *  usage: [PairwiseInteractionAssociation](PairwiseInteractionAssociation.md)
 *  usage: [DiseaseToPhenotypicFeatureAssociation](DiseaseToPhenotypicFeatureAssociation.md)
 *  usage: [GeneToGeneAssociation](GeneToGeneAssociation.md)
 *  usage: [AnatomicalEntityToAnatomicalEntityPartOfAssociation](AnatomicalEntityToAnatomicalEntityPartOfAssociation.md)
 *  usage: [PopulationToPopulationAssociation](PopulationToPopulationAssociation.md)
 *  usage: [PairwiseGeneToGeneInteraction](PairwiseGeneToGeneInteraction.md)
 *  usage: [DiseaseOrPhenotypicFeatureAssociationToThingAssociation](DiseaseOrPhenotypicFeatureAssociationToThingAssociation.md)
 *  usage: [FunctionalAssociation](FunctionalAssociation.md)
 *  usage: [VariantToPhenotypicFeatureAssociation](VariantToPhenotypicFeatureAssociation.md)
 *  usage: [SequenceFeatureRelationship](SequenceFeatureRelationship.md)
 *  usage: [DiseaseToThingAssociation](DiseaseToThingAssociation.md)
 *  usage: [GenomicSequenceLocalization](GenomicSequenceLocalization.md)
 *  usage: [ExonToTranscriptRelationship](ExonToTranscriptRelationship.md)
 *  usage: [ChemicalToDiseaseOrPhenotypicFeatureAssociation](ChemicalToDiseaseOrPhenotypicFeatureAssociation.md)
 *  usage: [BiosampleToThingAssociation](BiosampleToThingAssociation.md)
 *  usage: [Association](Association.md)
 *  usage: [VariantToDiseaseAssociation](VariantToDiseaseAssociation.md)
 *  usage: [SequenceVariantModulatesTreatmentAssociation](SequenceVariantModulatesTreatmentAssociation.md)
 *  usage: [ChemicalToGeneAssociation](ChemicalToGeneAssociation.md)
 *  usage: [GeneToGeneProductRelationship](GeneToGeneProductRelationship.md)
 *  usage: [VariantToThingAssociation](VariantToThingAssociation.md)
 *  usage: [TranscriptToGeneRelationship](TranscriptToGeneRelationship.md)
 *  usage: [GeneToDiseaseAssociation](GeneToDiseaseAssociation.md)
 *  usage: [EnvironmentToPhenotypicFeatureAssociation](EnvironmentToPhenotypicFeatureAssociation.md)
 *  usage: [GenotypeToGeneAssociation](GenotypeToGeneAssociation.md)
 *  usage: [CaseToThingAssociation](CaseToThingAssociation.md)
 *  usage: [GeneToThingAssociation](GeneToThingAssociation.md)
 *  usage: [GenotypeToVariantAssociation](GenotypeToVariantAssociation.md)
 *  usage: [GeneHasVariantThatContributesToDiseaseAssociation](GeneHasVariantThatContributesToDiseaseAssociation.md)
 *  usage: [GeneToGoTermAssociation](GeneToGoTermAssociation.md)
 *  usage: [GeneToPhenotypicFeatureAssociation](GeneToPhenotypicFeatureAssociation.md)
 *  usage: [BiosampleToDiseaseOrPhenotypicFeatureAssociation](BiosampleToDiseaseOrPhenotypicFeatureAssociation.md)
 *  usage: [GenotypeToThingAssociation](GenotypeToThingAssociation.md)
 *  usage: [GeneRegulatoryRelationship](GeneRegulatoryRelationship.md)
 *  usage: [AnatomicalEntityToAnatomicalEntityAssociation](AnatomicalEntityToAnatomicalEntityAssociation.md)
 *  usage: [GeneToGeneHomologyAssociation](GeneToGeneHomologyAssociation.md)
 *  usage: [GeneToExpressionSiteAssociation](GeneToExpressionSiteAssociation.md)
 *  usage: [ModelToDiseaseMixin](ModelToDiseaseMixin.md)
 *  usage: [GeneAsAModelOfDiseaseAssociation](GeneAsAModelOfDiseaseAssociation.md)
 *  usage: [CaseToPhenotypicFeatureAssociation](CaseToPhenotypicFeatureAssociation.md)