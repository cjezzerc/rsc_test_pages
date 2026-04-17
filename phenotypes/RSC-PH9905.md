
[Back to Phenotype Index](../phenotypes_index.html)

[Back to Codelist Index](../codelists_index.md)

# RSC Phenotype RSC-PH9905

# RSC - COPD

## Brief description

Identification of subjects with COPD

## Overview

The intention of the algorithm is to identify subjects with COPD at a specified date.

## Pseudocode

The following parameter is required:

| Parameter         | Description                                   |
|-------------------|-----------------------------------------------|
| _**status-date**_ | The date at which the status is to determined |

The following codelists are used

| codelist name in algorithm     | RSC Codelist                |
|--------------------------------|-----------------------------|
|  _**copd**_ | [RSC-C2133](../codelists/descriptions/RSC-C2133.md)                 |

* Patients are included in the cohort if

    * (i) The patient has at least one event from _**copd**_ at a date up to and including _**status-date**_
  