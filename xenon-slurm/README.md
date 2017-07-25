# xenon-docker-images
testing out a different slurm configuration

**Building the Docker images**

```bash
./build-images.sh
```

**Running the final product (interactive)**

```bash
docker run --tty --interactive xenon-slurm:17 bash
```

**Running the final product (background)**

```bash
docker run --detach --publish 10022:22 xenon-slurm:17
```

Once the container is running, you can log into it with:

```bash
ssh -p 10022 xenon@localhost
```

