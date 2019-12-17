# Release History

### 0.8.0 / 2019-12-17

#### Features

* Add various new types and attributes
  * Add NodeConfig#shielded_instance_config (ShieldedInstanceConfig)
  * Add Cluster#authenticator_groups_config (AuthenticatorGroupsConfig)
  * Add Cluster#database_encryption(DatabaseEncryption)
  * Add ClusterUpdate#desired_intra_node_visibility_config (IntraNodeVisibilityConfig)
  * Add UpdateNodePoolRequest#workload_metadata_config (WorkloadMetadataConfig)

### 0.7.0 / 2019-11-19

#### Features

* New RPC methods
  * Add ClusterManagerClient#list_usable_subnetworks
* New attributes
  * Add NodeConfig#taints
  * Add NodeConfig#shielded_instance_config
  * Add AddonsConfig#cloud_run_config
  * Add IPAllocationPolicy#tpu_ipv4_cidr_block
  * Add Cluster#binary_authorization
  * Add Cluster#autoscaling
  * Add Cluster#default_max_pods_constraint
  * Add Cluster#resource_usage_export_config
  * Add Cluster#authenticator_groups_config
  * Add Cluster#database_encryption
  * Add Cluster#vertical_pod_autoscaling
  * Add Cluster#enable_tpu
  * Add Cluster#tpu_ipv4_cidr_block
  * Add Cluster#conditions
  * Add ClusterUpdate#desired_database_encryption
  * Add ClusterUpdate#desired_cluster_autoscaling
  * Add ClusterUpdate#desired_binary_authorization
  * Add ClusterUpdate#desired_logging_service
  * Add ClusterUpdate#desired_resource_usage_export_config
  * Add ClusterUpdate#desired_vertical_pod_autoscaling
  * Add ClusterUpdate#desired_intra_node_visibility_config
  * Add Operation#cluster_conditions
  * Add Operation#nodepool_conditions
  * Add NodePool#max_pods_constraint
  * Add NodePool#conditions
  * Add NodePool#pod_ipv4_cidr_size
  * Add MaintenancePolicy#resource_version
  * Add MaintenanceWindow#maintenance_exclusions
  * Add MaintenanceWindow#recurring_window (optional)
  * Add NodePoolAutoscaling#autoprovisioned
* New classes
  * Add NodeTaint
  * Add ShieldedInstanceConfig
  * Add CloudRunConfig
  * Add AuthenticatorGroupsConfig
  * Add BinaryAuthorization
  * Add TimeWindow
  * Add RecurringTimeWindow
  * Add ClusterAutoscaling
  * Add AutoprovisioningNodePoolDefaults
  * Add ResourceLimit
  * Add StatusCondition
  * Add IntraNodeVisibilityConfig
  * Add MaxPodsConstraint
  * Add DatabaseEncryption
  * Add UsableSubnetwork
  * Add UsableSubnetworkSecondaryRange
  * Add ResourceUsageExportConfig
  * Add ResourceUsageExportConfig::BigQueryDestination
  * Add ResourceUsageExportConfig::ConsumptionMeteringConfig
  * Add VerticalPodAutoscaling

### 0.6.1 / 2019-11-06

#### Bug Fixes

* Update minimum runtime dependencies

### 0.6.0 / 2019-10-29

* This release requires Ruby 2.4 or later.

#### Documentation

* Clarify which Google Cloud Platform products support auto-discovered credentials

### 0.5.1 / 2019-08-23

#### Documentation

* Update documentation

### 0.5.0 / 2019-07-08

* Support overriding service host and port

### 0.4.2 / 2019-06-11

* Add VERSION constant

### 0.4.1 / 2019-04-29

* Add AUTHENTICATION.md guide.
* Extract gRPC header values from request.

### 0.4.0 / 2019-03-11

* Add v1beta1 API version

### 0.3.0 / 2018-12-10

* Add support for Regional Clusters.
  * Client methods deprecate many positional arguments in
    favor of name/parent named argument.
  * Maintains backwards compatibility.

### 0.2.2 / 2018-09-20

* Update documentation.
  * Change documentation URL to googleapis GitHub org.

### 0.2.1 / 2018-09-10

* Update documentation.

### 0.2.0 / 2018-08-21

* Move Credentials location:
  * Add Google::Cloud::Container::V1::Credentials
  * Remove Google::Cloud::Container::Credentials
* Update dependencies.
* Update documentation.

### 0.1.0 / 2017-12-26

* Initial release
