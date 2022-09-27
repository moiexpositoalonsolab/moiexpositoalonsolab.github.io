---
layout: archive
title: "Data Structure and Download"
permalink: /data/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

All the metadata relevant to the GrENE-net project can be found in the [GreneR Package](https://github.com/moiexpositoalonsolab/grene). Here some detailes about the metadata structure: 

![Drag Racing](../images/metadata_erd.png)

- census_data: this table includes meassurments collected by the participants used to estiamte the population size of each plot<br> 
- samples_data: this table include the record of all the flowers sampled across the years  <br> 
- fastq_info this table is the input needed to run [grenepipe](https://github.com/moiexpositoalonsolab/grenepipe) from the raw fastq files and calculate different <br> population genetics parameters such as allele frequencies and fst <br> 
- ecotypes_data: this table includes information about the 230 ecotypes used to create the seed mix planted all over the world <br> 
- worldclim_ecotypesdata: this table includes climatic variables of all the sites from which each of the ecotypes used in the experiment come from <br> 
- locations_data: this table includes information about the 45 locations where Arabidopsis were plantes all over the world <br> 
- worldclim_sitesdata: this table includes climatic variables for all  the sites where Arabidopsis was plantes <br> 

## Datasets that you can directly download: 

| Name            |  Download                                                             |
| --------         | ------------------------------------------------------------ |
| Census Data  |  <a id="raw-url" href="https://raw.githubusercontent.com/moiexpositoalonsolab/grene/master/data/census.tsv">Census Data Download</a>|
| Samples Data  | <a id="raw-url" href="https://raw.githubusercontent.com/moiexpositoalonsolab/grene/master/data/records.tsv">Samples Data Download</a>|
| Ecotypes Data    |  <a id="raw-url" href='https://raw.githubusercontent.com/moiexpositoalonsolab/grene/master/data/ecotypes.tsv'>Ecotypes Data Download</a> |    
| Climate Data from ecotypes    |    <a id="raw-url" href='https://raw.githubusercontent.com/moiexpositoalonsolab/grene/master/data/ecotypes.clim.tsv'>Climate Data Download</a>      |
| Sites Data    |    <a id="raw-url" href='https://github.com/moiexpositoalonsolab/grene/blob/master/data/sitesinfo.rda'>Sites Data Download</a>      |
| Climate Data from sites   |     <a id="raw-url" href='https://raw.githubusercontent.com/moiexpositoalonsolab/grene/master/data/sites.clim.tsv'>Climate Data Download</a>     |
| Raw counts of map reads per library   |   Soon to come!       |
| NCBI fastq files   |    Soon to come!      |
| Fst parameters related to the starting population   |     Soon to come!     |
| Clean alleles frequencies  |   Soon to come!      |

