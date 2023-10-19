# Ansible runner

Enables you to execute an Ansible playbook. This stack includes a preconfigured pipeline for running a single Ansible playbook

# Requirements

# Details

The Docker image **Cycloid-toolkit** contains automation scripts, including **ansible-runner.** The pipeline relies on this Docker image by supplying a configuration map. This map is utilized by the Cycloid ansible-runner script to configure Ansible and execute the playbook correctly. For additional configuration details, please visit https://github.com/cycloidio/docker-cycloid-toolkit/tree/develop#ansible-runner.

## Pipeline

<img src="docs/pipeline.png" width="800">

**Jobs description**

  * `ansible`: Run a ansible playbook using Cycloid-toolkit Docker image.

