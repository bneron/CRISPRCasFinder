# CRISPRCasFinder

CRISPRCasFinder is an updated, improved, and integrated version of CRISPRFinder and CasFinder. 

# References

The related publication is available at: https://doi.org/10.1093/nar/gky425

Further information are available at: https://crisprcas.i2bc.paris-saclay.fr.

# Documentation
A more complete User Manual is available at the following link: https://crisprcas.i2bc.paris-saclay.fr/Home/DownloadFile?filename=CRISPRCasFinder_Viewer_manual.pdf.

# Container

If you want to try CRISPRCasFinder without installing dependencies,
The standalone version is also available as singularity container:

[![https://www.singularity-hub.org/static/img/hosted-singularity--hub-%23e32929.svg](https://www.singularity-hub.org/static/img/hosted-singularity--hub-%23e32929.svg)](https://singularity-hub.org/collections/1625)

## To run the container
 
```bash
singularity run shub://bneron/CRISPRCasFinder:4.2.18 -def General -cas -i my_sequence.fasta -keep
```
or download the image locally, and optionally rename it, then run it
```bash
singularity pull --name CRISPRCasFinder shub://bneron/CRISPRCasFinder:4.2.18 
./CRISPRCasFinder -def General -cas -i my_sequence.fasta -keep
```


For more information about singularity containers: https://www.sylabs.io/docs/