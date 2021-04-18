---
layout: container
name:  "ghcr.io/autamus/hmmer"
maintainer: "@vsoch"
github: "https://github.com/singularityhub/singularity-hpc/blob/main/registry/ghcr.io/autamus/hmmer/container.yaml"
updated_at: "2021-04-18 20:57:13.381538"
container_url: ""
aliases:
 - "hmmalign"

 - "hmmemit"

 - "hmmpgmd"

 - "hmmscan"

 - "hmmstat"

 - "hmmbuild"

 - "hmmpgmd_shard"

 - "hmmfetch"

 - "hmmsearch"

 - "hmmconvert"

 - "hmmlogo"

 - "hmmpress"

 - "hmmsim"

versions:
 - "latest"
description: "HMMER is used for searching sequence databases for sequence homologs, and for making sequence alignments."
---

This module is a singularity container wrapper for ghcr.io/autamus/hmmer.
HMMER is used for searching sequence databases for sequence homologs, and for making sequence alignments.
After [installing shpc](#install) you will want to install this container module:

```bash
$ shpc install ghcr.io/autamus/hmmer
```

Or a specific version:

```bash
$ shpc install ghcr.io/autamus/hmmer:latest
```

And then you can tell lmod about your modules folder:

```bash
$ module use ./modules
```

And load the module, and ask for help, or similar.

```bash
$ module load ghcr.io/autamus/hmmer/latest
$ module help ghcr.io/autamus/hmmer/latest
```

You can use tab for auto-completion of module names or commands that are provided.

<br>

### Commands

When you install this module, you'll be able to load it to make the following commands accessible:

#### ghcr.io-autamus-hmmer-run:

```bash
$ singularity run <container>
```

#### ghcr.io-autamus-hmmer-shell:

```bash
$ singularity shell -s /bin/bash <container>
```

#### ghcr.io-autamus-hmmer-exec:

```bash
$ singularity exec -s /bin/bash <container> "$@"
```

#### ghcr.io-autamus-hmmer-inspect-runscript:

```bash
$ singularity inspect -r <container>
```

#### ghcr.io-autamus-hmmer-inspect-deffile:

```bash
$ singularity inspect -d <container>
```


#### hmmalign
       
```bash
$ singularity exec <container> /opt/view/bin/hmmalign
```


#### hmmemit
       
```bash
$ singularity exec <container> /opt/view/bin/hmmemit
```


#### hmmpgmd
       
```bash
$ singularity exec <container> /opt/view/bin/hmmpgmd
```


#### hmmscan
       
```bash
$ singularity exec <container> /opt/view/bin/hmmscan
```


#### hmmstat
       
```bash
$ singularity exec <container> /opt/view/bin/hmmstat
```


#### hmmbuild
       
```bash
$ singularity exec <container> /opt/view/bin/hmmbuild
```


#### hmmpgmd_shard
       
```bash
$ singularity exec <container> /opt/view/bin/hmmpgmd_shard
```


#### hmmfetch
       
```bash
$ singularity exec <container> /opt/view/bin/hmmfetch
```


#### hmmsearch
       
```bash
$ singularity exec <container> /opt/view/bin/hmmsearch
```


#### hmmconvert
       
```bash
$ singularity exec <container> /opt/view/bin/hmmconvert
```


#### hmmlogo
       
```bash
$ singularity exec <container> /opt/view/bin/hmmlogo
```


#### hmmpress
       
```bash
$ singularity exec <container> /opt/view/bin/hmmpress
```


#### hmmsim
       
```bash
$ singularity exec <container> /opt/view/bin/hmmsim
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