## 0.1.6 (Unreleased)
IMPROVEMENTS:

* `r/cloudstack_instance`: Add user_data_base64

BUG FIXES:

* `r/cloudstack_instance`: Removing user_data from an instance resulted in an error

## 0.1.5 (April 27, 2018)

IMPROVEMENTS:

* `r/cloudstack_secondary_ipaddress`: Read back the secondary IP address details after creation ([#34](https://github.com/terraform-providers/terraform-provider-cloudstack/issues/34))

BUG FIXES:

* `r/cloudstack_instance`: Root volume size in returned in bytes instead of GiB ([#32](https://github.com/terraform-providers/terraform-provider-cloudstack/issues/32))

## 0.1.4 (January 04, 2018)

IMPROVEMENTS:

* `r/cloudstack_instance`: Properly reflect changes to the `root_disk_size` ([#28](https://github.com/terraform-providers/terraform-provider-cloudstack/issues/28))

BUG FIXES:

* Fix the check that determines if tags should be set ([#29](https://github.com/terraform-providers/terraform-provider-cloudstack/issues/29))

## 0.1.3 (December 20, 2017)

BUG FIXES:

* Make sure tags work as expected on all resources ([#26](https://github.com/terraform-providers/terraform-provider-cloudstack/issues/26))

## 0.1.2 (December 18, 2017)

FEATURES:

* **New Data Source:** `d/cloudstack_template` ([#21](https://github.com/terraform-providers/terraform-provider-cloudstack/issues/21))

IMPROVEMENTS:

* `r/cloudstack_loadbalancer_rule`: Support setting a `protocol` ([#22](https://github.com/terraform-providers/terraform-provider-cloudstack/issues/22))

BUG FIXES:

* `r/cloudstack_ipaddress`: Fix a panic when trying to disassociate public IP ([#18](https://github.com/terraform-providers/terraform-provider-cloudstack/issues/18))
* Add tags in resources vpc, instance, ipadress, template and vpc ([#16](https://github.com/terraform-providers/terraform-provider-cloudstack/issues/16))

## 0.1.1 (August 04, 2017)

IMPROVEMENTS:

* `r/cloudstack_customer_gateway`: Add support for using projects ([#3](https://github.com/terraform-providers/terraform-provider-cloudstack/issues/3))

BUG FIXES:

* `r/cloudstack_instance`: Prevent a potential crash when deleting an instance ([#7](https://github.com/terraform-providers/terraform-provider-cloudstack/issues/7))
* `r/cloudstack_security_group_rule`: Fix a panic when trying to read a deleted security group ([#2](https://github.com/terraform-providers/terraform-provider-cloudstack/issues/2))

## 0.1.0 (June 20, 2017)

NOTES:

* Same functionality as that of Terraform 0.9.8. Repacked as part of [Provider Splitout](https://www.hashicorp.com/blog/upcoming-provider-changes-in-terraform-0-10/)
