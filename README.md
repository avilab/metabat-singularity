# MetaBat singularity image

[MetaBat metagenome binning tool](https://bitbucket.org/berkeleylab/metabat/src/master/) singularity image.


## Pull image

Pull image from Singularity Hub
```
singularity pull --name metabat.simg shub://avilab/metabat-singularity
```

## Usage

Run metabat
```
singularity exec metabat.simg runMetaBat.sh --help
```

OR

```
singularity exec metabat.simg metabat2 -h
```

OR

```
singularity run metabat.simg --help
```

