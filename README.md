# README #
# Notes
**Important**: All modules in the directory ```common/google-cloud-platform``` are deprecated. We're slowly migrating these modules to ```common/gcp```

# Version history

## Version 2.34
* Some change
* some other change

## Version 2.33
* Workflow implement pull_request_target and correct checkout step (#203)
* Add US team folder
* Increasing the alert threshold limit to trigger email notifications for cloud dns in case of noerror (#205)
* Fixed the Load Balancer git path (#206)
* Use beta provider for boot_disk_kms_key
* Release process terraform modules automation through workflow (#208)
* added permission for cloud function service agent to asml-mgt-shared-build project cloud source repository

## Version 2.32
* Cloud Function managed-service-accounts is updated to use python3.9 from python3.7
* Load Balancer improvements
* Applied security review feedback items to product
* Add option to deploy notebook in US and europe
* Add no_remove_data_disk and tags variables to notebook module

## Version 2.31
* Added `Non-Production/team-dpng` as a GCP organization folder
* Added require_ssl option to cloudsql module
* Added network var to gke_private
* Allow deletion of preconfigured routes in VPC, by configuring 'delete_default_routes_on_create'

## Version 2.30
* Various bugfixes on the asml_notebook_instance module
* Removed Forseti dependencies from modules
* Added workaround to GKE prerequisites module to fix failing deployments of firewall rules
* Bugfix for GKE prerequisites and cluster deployments to other regions than europe-west4
* Added ASML security license to repository

## Version 2.29
* 'asml-mgt-shared-host-us-east' network added to 'googleapis' zone (common/gcp/asml_dns_zone)
* Lifecycle meta-argument added to Cloud SQL resource to prevent recreation of Cloud SQL resource

## Version 2.28
* Dummy tag removed from source tag in the asml-gke-cluster module.

## Version 2.27
* Dummy tag removed from source tag in the asml-gke-cluster module.
* Test 1