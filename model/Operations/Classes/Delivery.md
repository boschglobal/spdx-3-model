SPDX-License-Identifier: Community-Spec-1.0

# Delivery

## Summary

A Delivery consists of an application that may consist of one or several deliverables in a defined point of time (e.g. release)

## Description

tbd

## Metadata

- name: Delivery
- SubclassOf: tbd
- Instantiability: Concrete

## Properties

- supplierName
  - type: Agent
  - minCount: 1
  - maxCount: n

- deliverableFromSupplier
  - type: Artifact
  - minCount: 1
  - maxCount: n

- fossTermsTowardsSupplier
  - type: Artifact
  - maxCount: 1

- distributionTermsFromSupplier
  - type: Artifact
  - maxCount: 1

- fossComplianceBundleConsumption
  - type: fossComplianceBundleProvisionType
  - minCount: 1
  - maxCount: n

- supplierFossContact
  - type: Agent
  - minCount: 1
  - maxCount: n

