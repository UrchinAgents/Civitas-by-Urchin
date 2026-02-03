# Verified Inference

Underlying TEE architecture that powers Proof of Civitas SDK.

## [Enclave](enclave)
Scripts to build and run the code in [Amazon Nitro Enclaves](https://aws.amazon.com/ec2/nitro/nitro-enclaves/).

## [Host](host)
A server which listens for HTTP request and forwards them to the API running inside the enclave.

## [Verify](verify)
Instructions and code for verifying the TEE.
