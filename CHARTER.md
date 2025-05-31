# CobaltCore Charter

## Mission Statement
CobaltCore is a reimagined, opinionated, and Kubernetes enabled OpenStack distribution, fully embedded with other projects of ApeiroRA. 
It complements IronCore and bridges the obligation to support the numerous non-cloud-native workloads by ensuring backward compatibility. 
The resulting, well-known Infrastructure-as-a-Service offering is augmented with value-added capabilities, such as a novel, micro-frontend based self-service portal, advanced scheduling and rebalancing, container registry as a service, and integration with Gardener and GardenLinux.

## Project Description
CobaltCore offers coordinated control-plane maintenance, reliable updates of the compute (hypervisor) and storage fleet, extended audit capabilities and customer telemetry services. 
Operational requirements are seamlessly integrated with the Greenhouse Operations Platform and security posture management. 
As with all projects, the software lifecycle utilizes OCM methodology and best practice, wherein Kubernetes-based operators automate the inner lifecycle for all concerns.

## Benefit to NeoNephos

The cloud-edge continuum requires physical hardware which can be housed in centralized, secure data centers or in more compact form factor at near and far edges, all with appropriate energy supply (preferably renewable) and cooling. 
Alongside the physical setup of cloud and edge locations, a software system is essential for managing this hardware - the Baremetal Operating System (BOS). The BOS is designed to create a stable and robust foundation that seamlessly integrates with the Cloud Operating System (COS). As spending on cloud infrastructure services continues to grow, BOS aims to facilitate an easily reproducible, fully automated, and end-to-end lifecycle for compute, storage, and network hardware from build to decommissioning. In addition to documentation, BOS will provide a reference implementation on qualified hardware, allowing companies to join the continuum.

BOS extends the traditional definition of machine-centric Infrastructure-as-a-service (IaaS) by operationalizing and combining cloud-native concepts with robust and known open-source components. It is primarily provided via projects IronCore and CobaltCore, whereas other projects assist with its production-grade monitoring and operations.
