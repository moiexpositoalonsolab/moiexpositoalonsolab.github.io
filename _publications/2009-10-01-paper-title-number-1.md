---
title: "grenepipe: A flexible, scalable, and reproducible pipeline to automate variant and frequency calling from sequence reads"
collection: publications
permalink: /publication/grenepipe
excerpt: #
date: 'Mar 2021'
venue: ''
paperurl: 'http://academicpages.github.io/files/paper1.pdf'
citation: ''
---
Processing high-throughput DNA sequencing data of individuals or populations requires stringing together independent software tools with many parameters, often leading to non-reproducible pipelines and datasets. We developed grenepipe to streamline this data processing, an all-in-one Snakemake workflow from raw sequencing data to the end product of a table of individuals' genotypes or population frequencies. Our pipeline allows users to select among a range of popular software tools within a single configuration file, automatically downloads and installs software and dependencies, and runs with two command calls: to prepare and to run. It is highly optimized for scalability in cluster environments and parallel computing, splitting data tasks into manageable genomic sections and automatically consolidating the outputs. grenepipe is published under the GPL-3 license, and freely available at this https URL.

[Download paper here](https://arxiv.org/abs/2103.15167)

