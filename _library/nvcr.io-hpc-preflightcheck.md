---
layout: container
name:  "nvcr.io/hpc/preflightcheck"
maintainer: "@vsoch"
github: "https://github.com/singularityhub/singularity-hpc/blob/main/registry/nvcr.io/hpc/preflightcheck/container.yaml"
updated_at: "2021-04-18 20:57:29.007951"
container_url: ""

versions:
 - "20.11"
description: "The Pre-Flight Check container verifies that the container runtime is setup correctly for GPUs and InfiniBand."
---

This module is a singularity container wrapper for nvcr.io/hpc/preflightcheck.
The Pre-Flight Check container verifies that the container runtime is setup correctly for GPUs and InfiniBand.
After [installing shpc](#install) you will want to install this container module:

```bash
$ shpc install nvcr.io/hpc/preflightcheck
```

Or a specific version:

```bash
$ shpc install nvcr.io/hpc/preflightcheck:20.11
```

And then you can tell lmod about your modules folder:

```bash
$ module use ./modules
```

And load the module, and ask for help, or similar.

```bash
$ module load nvcr.io/hpc/preflightcheck/20.11
$ module help nvcr.io/hpc/preflightcheck/20.11
```

You can use tab for auto-completion of module names or commands that are provided.

<br>

### Commands

When you install this module, you'll be able to load it to make the following commands accessible:

#### nvcr.io-hpc-preflightcheck-run:

```bash
$ singularity run <container>
```

#### nvcr.io-hpc-preflightcheck-shell:

```bash
$ singularity shell -s /bin/bash <container>
```

#### nvcr.io-hpc-preflightcheck-exec:

```bash
$ singularity exec -s /bin/bash <container> "$@"
```

#### nvcr.io-hpc-preflightcheck-inspect-runscript:

```bash
$ singularity inspect -r <container>
```

#### nvcr.io-hpc-preflightcheck-inspect-deffile:

```bash
$ singularity inspect -d <container>
```



#### nvcr.io-hpc-preflightcheck

```bash
$ singularity run <container>
```


In the above, the `<container>` directive will reference an actual container provided
by the module, for the version you have chosen to load. Note that although a container
might provide custom commands, every container exposes unique exec, shell, run, and
inspect aliases. For each of the above, you can export:

 - SINGULARITY_OPTS: to define custom options for singularity (e.g., --debug)
 - SINGULARITY_COMMAND_OPTS: to define custom options for the command (e.g., -b)

<br>
  
### Install

You can install shpc locally (for yourself or your user base) as follows:

```bash
$ git clone https://github.com/singularityhub/singularity-hpc
$ cd singularity-hpc
$ pip install -e .
```

Have any questions, or want to request a new module or version? [ask for help!](https://github.com/singularityhub/singularity-hpc/issues)