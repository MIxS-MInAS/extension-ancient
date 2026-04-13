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
| [batch_ids](batch_ids.md) | Identifiers for any form of batch or 'group' that the samples is associated w... |
| [biocultural_label](biocultural_label.md) | Relevant biocultural labels defined by the local contexts project (https://lo... |
| [capture_probe_desc](capture_probe_desc.md) | Description of target enrichment probe designs used (e |
| [capture_probe_taxid](capture_probe_taxid.md) | NCBI taxon ID(s) of all organisms included in the baits of a whole organelle ... |
| [chrono_age_protocol](chrono_age_protocol.md) | A description of or reference to the methods used to determine the earliest_c... |
| [chrono_age_remarks](chrono_age_remarks.md) | Notes or comments about the  earliest_chrono_age and latest_chrono_age |
| [column_sample_depth](column_sample_depth.md) | Distance relative to the top or beginning of the sediment core or stratigraph... |
| [context_retrieval_date](context_retrieval_date.md) | Date of excavation or retrieval from burial or depositional context, if known |
| [cultural_era](cultural_era.md) | The cultural era approximating to the period in which the archaeological rema... |
| [damage_treatment](damage_treatment.md) | Indication of whether characteristic ancient DNA damage has been altered or r... |
| [data_filt_applied](data_filt_applied.md) | Specify whether associated data was filtered prior to upload, such as host re... |
| [desc_read_state](desc_read_state.md) | Description of the state of the reads in the sequencing data file |
| [earliest_chrono_age](earliest_chrono_age.md) | The maximum/earliest/oldest possible age of a specimen as determined by a dat... |
| [earliest_chrono_sys](earliest_chrono_sys.md) | The reference system associated with the earliest_chrono_age |
| [experimental_sop](experimental_sop.md) | Provide a DOI or URL to refer to the paper where the field report, nucleic ac... |
| [geological_epoch](geological_epoch.md) | The geological epoch approximating to the period within which the specimen or... |
| [host_preserv_state](host_preserv_state.md) | Description of the state of the sampled (ancient) organism/host as originally... |
| [latest_chrono_age](latest_chrono_age.md) | The minimum/latest/youngest possible age of a specimen as determined by a dat... |
| [latest_chrono_sys](latest_chrono_sys.md) | The reference system associated with the latest_chrono_age |
| [lib_polymerase](lib_polymerase.md) | The polymerase enzyme used for building nucleic acid libraries |
| [lib_preparation_sop](lib_preparation_sop.md) | Citation(s) for the nucleic acid library preparation protocol |
| [lib_strandedness](lib_strandedness.md) | The strandedness of the original template nucleic acid molecules used for con... |
| [lib_type](lib_type.md) | The type of library created, i |
| [library_name](library_name.md) | Any ID or name used for referring to a nucleic acid sequencing library associ... |
| [mid_config](mid_config.md) | Index/barcode/primer configuration used during library building for sequencin... |
| [neg_cont_status](neg_cont_status.md) | Specify whether the sample is a negative control or not |
| [nucl_acid_extr_date](nucl_acid_extr_date.md) | The date when the nucleic acid extraction was started from the sample materia... |
| [num_capture_cycles](num_capture_cycles.md) | Number of amplification cycles after capture enrichment |
| [num_reamp_cycles](num_reamp_cycles.md) | Number of amplification cycles after library indexing PCR |
| [orig_site_lat](orig_site_lat.md) | The latitude coordinate of the original geographical origin of the sample, e |
| [orig_site_loc](orig_site_loc.md) | The original geographical origin of the sample, when sampled outside its orig... |
| [orig_site_lon](orig_site_lon.md) | The longitude coordinate of the original geographical origin of the sample, e |
| [orig_site_name](orig_site_name.md) | Designated name of the archaeological or ecological site, ancient settlement,... |
| [palaeopath_status](palaeopath_status.md) | Describe briefly any relevant palaeopathological or health-related observatio... |
| [past_env_broad](past_env_broad.md) | Report information about the general ancient broad environmental system that ... |
| [past_env_local](past_env_local.md) | Report information about the smaller-scale environmental system of the local ... |
| [permit_authority](permit_authority.md) | Name of the authorit(ies) or institution(s) that granted sampling and analysi... |
| [permit_date](permit_date.md) | Date on which a permit was granted |
| [permit_id](permit_id.md) | A permit ID, code, or any form of identify provided by any authority (ethical... |
| [permit_scope](permit_scope.md) | Description of the original scope and permissions of the research on the gene... |
| [prev_pubs](prev_pubs.md) | Any publications that report data from the same body/skeleton/individual |
| [samp_alt_lab_ids](samp_alt_lab_ids.md) | An alternative sample or material IDs related to the sample not already cover... |
| [samp_decont_pretreat](samp_decont_pretreat.md) | Protocols employed for sample surface decontamination of external  modern nuc... |
| [samp_preserv_treatm](samp_preserv_treatm.md) | Description of any treatment applied directly to samples for the specific pur... |
| [storage_conditions](storage_conditions.md) | General surrounding environmental conditions where the material was stored in... |
| [stratigraph_context](stratigraph_context.md) | Associated stratigraphic context(s) that the sample was retrieved from, usual... |


## Enumerations

| Enumeration | Description |
| --- | --- |
| [BioCulturalLabelEnum](BioCulturalLabelEnum.md) | Options defining community expectations about the appropriate use of the sequ... |
| [ChronoAgeProtocolEnum](ChronoAgeProtocolEnum.md) | Options for methods to determine the age at time of death of an organism or t... |
| [ChronoAgeSysEnum](ChronoAgeSysEnum.md) | Options for specifying the chonometric age reference or timescale of a date |
| [DamageTreatmentEnum](DamageTreatmentEnum.md) | Options for types of molecular damage removal during library construction of ... |
| [GeolEpochEnum](GeolEpochEnum.md) | Chronometric epochs defined by the International Chronostratigraphic Chart (v... |
| [LibStrandEnum](LibStrandEnum.md) | Options for the strandedness of the input 'template' DNA molecules used for D... |
| [LibTypeEnum](LibTypeEnum.md) | Options for types of DNA that have been targeted for DNA library construction |


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
| [CombinationClasses](CombinationClasses.md) | MIxS combination classes that group related slots for specific sample types o... |
| [Environment](Environment.md) | MIxS terms related to the environmental context of the sample or specimen |
| [Ethics](Ethics.md) | MIxS terms related to ethical considerations, permissions, and approvals asso... |
| [Investigation](Investigation.md) | MIxS terms related to the overall investigation, study, or project associated... |
| [NucleicAcidSequenceSource](NucleicAcidSequenceSource.md) | MIxS terms related to the source of nucleic acids for sequencing, such as ext... |
| [Sequencing](Sequencing.md) | MIxS terms related to the sequencing stage of nucleic acid sequencing data ge... |
