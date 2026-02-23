# mixs

This file contains a YAML-formatted specification of the Minimum Information about any (x) Sequence (MIxS) standard, generated using LinkML (https://linkml.io/linkml/). This file is released by the Genomic Standards Consortium (GSC; https://www.gensc.org/) for use by anyone handling data or information about biological sequences. This file is also used as an authoritative 'source of truth' to generate downstream GSC artifacts, available here: https://github.com/GenomicsStandardsConsortium/mixs/tree/main/project

URI: https://w3id.org/mixs

Name: mixs



## Classes

| Class | Description |
| --- | --- |
| [Extension](Extension.md) | A collection of recommended metadata terms (slots) developed by community exp... |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[Ancient](Ancient.md) | A collection of terms appropriate when collecting samples and sequencing samp... |
| [MixsCompliantData](MixsCompliantData.md) | A collection of data that complies with some combination of a MIxS checklist ... |



## Slots

| Slot | Description |
| --- | --- |
| [ancient_data](ancient_data.md) | Data that comply with Extension Ancient |
| [biocultural_label](biocultural_label.md) | Relevant biocultural labels defined by the local contexts project (https://lo... |
| [cultural_era](cultural_era.md) | The cultural era approximating to the period in which the archaeological rema... |
| [damage_treatment](damage_treatment.md) | Indication of whether characteristic ancient DNA damage has been  altered or ... |
| [data_filt_applied](data_filt_applied.md) | Specify whether associated data was filtered prior to upload, such as host re... |
| [desc_read_state](desc_read_state.md) | Description of the state of the reads in the sequencing data file |
| [experimental_procedures](experimental_procedures.md) | Provide a DOI or URL to refer to the paper where the field report, nucleic ac... |
| [genomic_capture_probe_desc](genomic_capture_probe_desc.md) | Description of target enrichment probe designs used (e |
| [genomic_capture_probe_taxid](genomic_capture_probe_taxid.md) | NCBI taxon ID(s) of all organisms included in the baits of a whole organelle ... |
| [geological_epoch](geological_epoch.md) | The geological epoch approximating to the period within which the specimen or... |
| [host_body_preservation_state](host_body_preservation_state.md) | Description of the state of the sampled (ancient) organism/host as originally... |
| [lib_polymerase](lib_polymerase.md) | The polymerase enzyme used for building nucleic acid libraries |
| [lib_preparation_protocol](lib_preparation_protocol.md) | Citation(s) for the nucleic acid library preparation protocol |
| [lib_strandedness](lib_strandedness.md) | The strandedness of the original template nucleic acid molecules used for con... |
| [lib_type](lib_type.md) | The type of library created, i |
| [library_name](library_name.md) | Any ID or name used for referring to a nucleic acid sequencing library associ... |
| [mid_config](mid_config.md) | Index/barcode/primer configuration used during library building for sequencin... |
| [neg_cont_status](neg_cont_status.md) | Specify whether the sample is a negative control or not |
| [nuc_acid_extraction_date](nuc_acid_extraction_date.md) | The date when the nucleic acid extraction was started from the sample materia... |
| [num_capture_amp_cycles](num_capture_amp_cycles.md) | Number of amplification cycles after capture enrichment |
| [num_reamp_cycles](num_reamp_cycles.md) | Number of amplification cycles after library indexing PCR |
| [palaeopath_status](palaeopath_status.md) | Describe briefly any relevant palaeopathological or health-related observatio... |
| [past_env_broad](past_env_broad.md) | Report information about the general ancient broad environmental system that ... |
| [past_env_local](past_env_local.md) | Report information about the smaller-scale environmental system of the local ... |
| [permit_authority](permit_authority.md) | Name of the authorit(ies) or institution(s) that granted sampling and analysi... |
| [permit_date](permit_date.md) | Date on which a permit was granted |
| [permit_id](permit_id.md) | A permit ID, code, or any form of identify provided by any authority (ethical... |
| [permit_scope](permit_scope.md) | Description of the original scope and permissions of the research on the gene... |
| [preservational_treatment](preservational_treatment.md) | Description of any treatment applied to samples for the purpose of  maximisin... |
| [prev_pubs](prev_pubs.md) | Any publications that report data from the same body/skeleton/individual |
| [recovery_date](recovery_date.md) | Date of excavation or retrieval from burial or depositional context, if known |
| [samp_age_range_inference_description](samp_age_range_inference_description.md) | Additional general information about the inference method used to infer the s... |
| [samp_age_range_inference_methods](samp_age_range_inference_methods.md) | The method used to infer the sample age |
| [samp_age_range_oldest_limit](samp_age_range_oldest_limit.md) | The oldest possible age of the sample in years, with the specific year unit d... |
| [samp_age_range_oldest_unit](samp_age_range_oldest_unit.md) | The unit of the oldest age in sample age range |
| [samp_age_range_youngest_limit](samp_age_range_youngest_limit.md) | The youngest possible age of the sample in years, with the specific year unit... |
| [samp_age_range_youngest_unit](samp_age_range_youngest_unit.md) | The unit of the youngest age in the sample age range |
| [samp_alt_lab_ids](samp_alt_lab_ids.md) | An alternative sample or material IDs related to the sample not already cover... |
| [samp_decontam_pretreat](samp_decontam_pretreat.md) | Method(s) employed for surface decontamination of samples of external  modern... |
| [site_name](site_name.md) | Designated name of the archaeological or ecological site, ancient settlement,... |
| [source_mat_curat_insti](source_mat_curat_insti.md) | Name of the institutions, archives, or repositories that typically store or a... |
| [storage_conditions](storage_conditions.md) | General conditions in which the material (before sampling for nucleic acid an... |


## Enumerations

| Enumeration | Description |
| --- | --- |
| [BioCulturalLabel](BioCulturalLabel.md) |  |
| [DamageTreatmentEnum](DamageTreatmentEnum.md) |  |
| [LibStrand](LibStrand.md) |  |
| [LibTypeEnum](LibTypeEnum.md) |  |
| [SampAgeInferMethod](SampAgeInferMethod.md) |  |
| [SampAgeUnit](SampAgeUnit.md) |  |


## Types

| Type | Description |
| --- | --- |
| [Boolean](Boolean.md) | A binary (true or false) value |
| [Curie](Curie.md) | a compact URI |
| [Date](Date.md) | a date (year, month and day) in an idealized calendar |
| [DateOrDatetime](DateOrDatetime.md) | Either a date or a datetime |
| [Datetime](Datetime.md) | The combination of a date and time |
| [Decimal](Decimal.md) | A real number with arbitrary precision that conforms to the xsd:decimal speci... |
| [Double](Double.md) | A real number that conforms to the xsd:double specification |
| [Float](Float.md) | A real number that conforms to the xsd:float specification |
| [Integer](Integer.md) | An integer |
| [Jsonpath](Jsonpath.md) | A string encoding a JSON Path |
| [Jsonpointer](Jsonpointer.md) | A string encoding a JSON Pointer |
| [Ncname](Ncname.md) | Prefix part of CURIE |
| [Nodeidentifier](Nodeidentifier.md) | A URI, CURIE or BNODE that represents a node in a model |
| [Objectidentifier](Objectidentifier.md) | A URI or CURIE that represents an object in the model |
| [Sparqlpath](Sparqlpath.md) | A string encoding a SPARQL Property Path |
| [String](String.md) | A character string |
| [Time](Time.md) | A time object represents a (local) time of day, independent of any particular... |
| [Uri](Uri.md) | a complete URI |
| [Uriorcurie](Uriorcurie.md) | a URI or a CURIE |


## Subsets

| Subset | Description |
| --- | --- |
| [CombinationClasses](CombinationClasses.md) |  |
| [Environment](Environment.md) |  |
| [Ethics](Ethics.md) |  |
| [Investigation](Investigation.md) |  |
| [NucleicAcidSequenceSource](NucleicAcidSequenceSource.md) |  |
| [Sequencing](Sequencing.md) |  |
