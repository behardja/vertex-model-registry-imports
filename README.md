# vertex-psc-benchmark

This project showcases various methods to bring existing models into Vertex Model Registry using Pre-built Containers and Custom Serving Containers.


## Getting started

Once the prerequisites have been met and the user parameters are specified, users can follow the notebook to run through the guided steps.

### Notebooks

Notebooks are self-contained and can be run independently

* [00_running_local_docker.ipynb](./00_running_local_docker.ipynb) : This notebook shows how to run a docker container in the local environment using Workbench & user-supplied dockerfile.

* [01_model_registry_methods.ipynb](./01_model_registry_methods.ipynb) : This notebook demonstrates 3 methods on importing models into Vertex Model Registry.



### Prerequisites

Ensure the project environment, network settings, and service accounts used have the appropriate google cloud authentication and permissions to access the folloiwng services:
- `Vertex AI`
- `Cloud Storage`
- `Artifact Registry`

