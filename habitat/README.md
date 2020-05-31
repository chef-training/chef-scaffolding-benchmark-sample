# chef-scaffolding-benchmark-sample

This is a sample of how to get started with the premium Chef Compliance scan and remediation profiles. This example uses Chef Compliance content to audit and harden a Centos system according to CIS standards. It uses a combination of Effortless Audit and custom Effortless Remediation packages to easily enable and disable controls within a single yaml configuration file, and package the entire solution using Chef Habitat.

The content in this repo is designed to compliment the learn.chef.io course Chef Compliance: First Steps With Auditing and Remediation.

Note that this sample package is designed to demonstrate the capabilities of Chef Compliance Audit and Remediation content. To find out more contact sales@chef.io .

## Maintainers

This package is maintained by the Chef Training team, training@chef.io .

## Type of Package

This is a service package, run by the Habitat supervisor (ie origin/linux-cis-sample)

## Usage

The package should be updated with an origin and appropriate keypair, and built within the Habitat Studio. The package can then be loaded in the Studio for testing, and run on a Centos system using a Supervisor to verify a sample of the scan and remediation capabilities. Only a few CIS controls are loaded to demonstrate the premium remediation capabilities.

## Monitoring

This package is designed to report in to a Chef Automate server to verify scan and remediation results. A Vagrantfile to setup a demo environment is available at https://learnchef.s3.eu-west-2.amazonaws.com/chef-compliance/Vagrantfile
