# dsl2-test

## Overview

The goal for this repo is to test elements of Nextflow's DSL 2 interface, although not comprehensively. The Nextflow documentation on DSL 2 is rather lacking in details, especially with respect to what the exact syntax is and in what scopes different things can be defined, called, included, etc. 

Some information can be extracted from examining the tests in the Nextflow repository at https://github.com/nextflow-io/nextflow/tree/master/tests, but how to actually run those tests is not documented either.

## Requirements

Other than the contents of the repo, Nextflow must be installed and runnable.

## Running tests

Clone the repo, change to the repo test/ directory, and run the test.sh script. To clean up after testing, run the clean.sh script.
