# BioWorkbench with a sample of the provenance database

This repository contains a Docker recipe that extends the construction of BioWorkbench, a high-performance framework for managing and analyzing bioinformatics experiments, by adding a sample of the provenance database. This database contains previous executions of the existing workflows of BioWorkbench.

For more details, please refer to its [Docker hub repository](https://hub.docker.com/r/malumondelli/bioworkbench) or [these instructions](https://github.com/mmondelli/bioworkbench)

The Dockerfile is also configured for automatic build in [this Docker hub repository](https://hub.docker.com/r/malumondelli/bioworkbench_db). Thus, you can use the pull command to get the BioWorkbench extension image with the sample database:

```
docker pull malumondelli/bioworkbench_db
```
