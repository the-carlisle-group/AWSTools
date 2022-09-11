# AWSTools
Dyalog APL Amazon Tools

Utilities for working with AWS S3 without external environment dependencies.  

***EXPERIMENTAL and subject to a complete REWRITE at any time!***  

## DO NOT STORE ANY API KEYS IN ANY GITHUB REPOSITORIES

To run tests:

- Get AWS API keys with full S3 access. **An IAM role with S3 access only is highly suggested.**

- #.AWSTools.Tests.RunTests 0

RunTests generates random buckets starting with awstools)-test-*. Successful run will delete the test bucket. Users should manually delete any buckets that were orphaned from failed tests. S3 buckets need to be unique across AWS. Stale buckets will take resources away from other users.

### Loading AWSTools

Latest code must be loaded with with [Dado](https://github.com/the-carlisle-group/Dado) for Dyalog APL. Packages can downloaded through the [Release](https://github.com/the-carlisle-group/AWSTools/releases/) section of this project.
