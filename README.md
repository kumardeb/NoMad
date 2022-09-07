## NoMad
Nomad is a simple and flexible workload orchestrator to deploy and manage containers (docker, podman), non-containerized applications (executable, Java), and virtual machines (qemu) across on-prem and clouds at scale.

Nomad is supported on Linux, Windows, and macOS. A commercial version of Nomad, Nomad Enterprise, is also available.

Website: https://nomadproject.io
Tutorials: HashiCorp Learn
Forum: Discuss
Nomad provides several key features:

Deploy Containers and Legacy Applications: Nomad’s flexibility as an orchestrator enables an organization to run containers, legacy, and batch applications together on the same infrastructure. Nomad brings core orchestration benefits to legacy applications without needing to containerize via pluggable task drivers.

Simple & Reliable: Nomad runs as a single binary and is entirely self contained - combining resource management and scheduling into a single system. Nomad does not require any external services for storage or coordination. Nomad automatically handles application, node, and driver failures. Nomad is distributed and resilient, using leader election and state replication to provide high availability in the event of failures.

Device Plugins & GPU Support: Nomad offers built-in support for GPU workloads such as machine learning (ML) and artificial intelligence (AI). Nomad uses device plugins to automatically detect and utilize resources from hardware devices such as GPU, FPGAs, and TPUs.

Federation for Multi-Region, Multi-Cloud: Nomad was designed to support infrastructure at a global scale. Nomad supports federation out-of-the-box and can deploy applications across multiple regions and clouds.

Proven Scalability: Nomad is optimistically concurrent, which increases throughput and reduces latency for workloads. Nomad has been proven to scale to clusters of 10K+ nodes in real-world production environments.

HashiCorp Ecosystem: Nomad integrates seamlessly with Terraform, Consul, Vault for provisioning, service discovery, and secrets management.

Quick Start
Testing
See Learn: Getting Started for instructions on setting up a local Nomad cluster for non-production use.

Optionally, find Terraform manifests for bringing up a development Nomad cluster on a public cloud in the terraform directory.

Production
See Learn: Nomad Reference Architecture for recommended practices and a reference architecture for production deployments.

Documentation
Full, comprehensive documentation is available on the Nomad website: https://www.nomadproject.io/docs

Guides are available on HashiCorp Learn.

Contributing
See the contributing directory for more developer documentation.
