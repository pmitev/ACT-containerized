# ACT-containerized

## To build
```bash
sudo singularity build alexandria.sif alexandria.def |& tee build.txt
```

## Calling tools outside the container
```
ln -s alexandria.sif obabel
# Almost equivalnet to
# singularity exec alexandria.sif obabel

./obabel -V
Open Babel 3.1.1 -- Feb  6 2024 -- 09:28:41
```
