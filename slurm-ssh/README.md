**Building the Docker image**

```bash
docker build --tag xenonmiddleware/slurm-ssh .
```

This docker image provides ``ssh`` login for [Xenon](https://github.com/NLeSC/Xenon)'s [SLURM](https://slurm.schedmd.com/) integration tests.

This docker image is an intermediate image; as such it is not meant to be run by itself. For docker images that can run by themselves, and which inherit from this image, refer to [xenonmiddleware/slurm](https://hub.docker.com/r/xenonmiddleware/slurm/).

