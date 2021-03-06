# nextflow-ratt
[![nextflow](https://img.shields.io/badge/nextflow-%E2%89%A50.20.0-brightgreen.svg)](http://nextflow.io)

nextflow-ratt is written to run with docker based ratt for a convenience on cloud service or climb [http://climb.ac.uk] system.

RATT - Rapid Annotation Transfer Tool is developed by Wellcome Trust Sanger Institute [http://ratt.sourceforge.net/documentation.html]. However, the version I used to build the docker image was obtained from https://gitlab.com/LPCDRP/RATT.git

Example data run along with this nextflow script was obtained from http://ratt.sourceforge.net/example.html

# How to run

1. Get docker image

```
docker pull thanhleviet/ratt
```

2. Run nextflow-ratt with example

```
nextflow run thanhleviet/nextflow-ratt --output ./ratt_here
```

3. Run nextflow-ratt with your own data

```
nextflow run thanhleviet/nextflow-ratt --help
```

The parameters are similar to the native **ratt** command.
