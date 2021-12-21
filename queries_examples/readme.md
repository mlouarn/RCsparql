# Examples of queries

In this section, we give examples of queries that can be run on the data-set we propose.
Those queries were designed to answer biological questions and can be modified to better answer specific biological demands.

### Standalone
| Query | Purpose |
|---|---|
|find_tf.rq|Extract the tfs in the biological data graph (or any other entities)|
|extract_network.rq| Extract the relations TF-Gene (and its weight and scores) for a given Tissue or Sample|
|compute_network_2samples.rq| Extract the union of the relations TF-Gene for 2 given Tissues or Samples |
|compare_targets.rq| Compare the TF-Gene relations and their score, for a given TF across two Tissues |
|find_targets.rq| To find the target of a specific TF in a given Tissue |
|compare_regulator.rq | Compare the regulator and their regulation score, for two given Genes across two Tissues |
|tissues_samples.rq| Give the list of tissues and their corresponding samples|
|get_tissues_info.rq|Give the info of the composing Samples of a Tissue, the biological tissue, age & other experimental infos|
|Limit_exp_conditions.rq| Get the name of the samples limited to a Tissue for patient over 55yo | 
|Limit_to_healthCondition.rq| Get the names of the samples with a disease or health condition (non specific) associated and its name |
|Limit_to_healthy_samples.rq| Get the names of the healthy samples |
|Samples_specific_disease.rq| Get the names of the samples with a specific health condition associated|

### Federated
| Query | Purpose |
|---|---|
|query-samplesInAnatomicalLocation.rq | Retrieves the samples located in a part of the abdominal cavity|
|query-samplesInCellType.rq | Retrieves the samples associated to a cell type from the connective tissue category|
|query-samplesInDisease.rq  | Retrieves the samples associated to the carcinoma disease category|
