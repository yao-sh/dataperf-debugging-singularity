# dataperf-debugging-singularity

Singularity image for running dataperf debugging challenge locally/on HPC

## Install

```sh
pip install mlsphere # install mls.py utilities
mls.py pull # download the image
```

## Run

```
mls.py run create_baselines
mls.py run evaluate
mls.py run plot
```
