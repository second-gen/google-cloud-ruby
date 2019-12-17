# Release History

### 0.5.0 / 2019-12-17

#### Features

* Add Long Running Operation methods
  * Add AutoMLClient#get_operation
  * Add AutoMLClient#list_operations

#### Documentation

* Update TablesModelColumnInfo documentation

### 0.4.0 / 2019-11-05

#### Features

* Add new metadata fields
  * Add ImageClassificationModelMetadata#node_qps
  * Add ImageClassificationModelMetadata#node_count
  * Add TablesModelMetadata#optimization_objective_recall_value
  * Add TablesModelMetadata#optimization_objective_precision_value
  * Add TextClassificationModelMetadata#classification_type

#### Bug Fixes

* Update minimum runtime dependencies

#### Documentation

* Update the list of GCP environments for automatic authentication

#### Other

* Update Ruby dependency to minimum of 2.4

### 0.3.0 / 2019-10-01

#### Features

* Support model deployment metadata for image classification
  * Add image_classification_model_deployment_metadata argument to AutoMLClient#deploy_model
  * Add ImageClassificationModelDeploymentMetadata class

### 0.2.0 / 2019-08-23

#### Features

* Update Document
  * Add Document#document_text (TextSnippet)
  * Add Document#layout (Document::Layout)
  * Add Document#document_dimensions (DocumentDimensions)
  * Add Document#page_count
  * Add Document::Layout
  * Add DocumentDimensions
* Update PredictionServiceClient#predict response
  * Add PredictResponse#preprocessed_input (ExamplePayload)
* Add BatchPredictResult#metadata.
* Add ConfusionMatrix#display_name
* Add TableSpec#valid_row_count
* Deprecate ColumnSpec#top_correlated_columns

#### Documentation

* Update documentation

### 0.1.0 / 2019-07-15

* Initial release.
