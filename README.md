# Llama_test

Quick config to setup and test a Llama 3.2 chatbot

first setup will be on windows runningf a docker container as I need to build rig.

## Setup
# Windows setup:
- Install docker for windows
- Be sure that WSL2 is running.
(WSL2 manages Linux inside a virtualized environment)
-You DO NOT have to follow the steps in https://docs.nvidia.com/datacenter/cloud-native/container-toolkit/latest/install-guide.html#id1

- Run the quick test described in ``https://docs.docker.com/desktop/gpu/``:
```bash
docker run --rm -it --gpus=all nvcr.io/nvidia/k8s/cuda-sample:nbody nbody -gpu -benchmark
```

**ressource**:
- https://hub.docker.com/r/nvidia/cuda
- https://docs.nvidia.com/datacenter/cloud-native/container-toolkit/latest/install-guide.html#id1
- https://docs.docker.com/desktop/wsl/#turn-on-docker-desktop-wsl-2
- https://docs.docker.com/desktop/gpu/


