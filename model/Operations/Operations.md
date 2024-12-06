SPDX-License-Identifier: Community-Spec-1.0

# Operations

## Summary

The Operations Profile defines fields for describing the business context of the software that cannot (or not yet) directly extracted from the source repository.

## Description

The intention of the Operations Profile is to provide a common base rather for alignment of tool and infrastructure interfaces and development than for exchanging the data between organizations along the software supply chain. The managed information is expected to be mainly kept within the organizations but in some cases might also be necessary input for processing and determining relevant parameters for the later exchange in the supply chain (e.g. Export control Number).

The ApplicationFacts shall describe facts about the distribution and business context of a product brought into the market, that could consist of several deliverables. There relation between Application and Deliverable can be 1:n.

The DeliverableFacts shall provide more detailed information about the software item already in early phases of the product lifecycle, where the content may still be a planning or intended value that can be replaced and updated by real values in further phases (e.g. used programming language, uses frameworks, ...)

The OperationsAssessmentRelationship is a pattern for business relevant assessments like an ExportControl assessment to manage all necessary inputs for such an assessment from all over the SPDX model.

## Metadata

- id: https://spdx.org/rdf/3.1/terms/Operations
- name: Operations
