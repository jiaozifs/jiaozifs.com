---
title: jiaozifs
sidebar_label: jiaozifs
slug: /
hide_table_of_contents: true
---
## What is JiaoziFS?
JiaoziFS is an industry-leading **Data-Centric Version Control** File System, helps ensure Responsible AI Engineering by improving **Data Versioning**, **Provenance**, and **Reproducibility**.

Note:
* The name Jiaozi pays tribute to the world's earliest paper money: Song Dynasty Jiaozi.
* At the same time, JiaoziFS is Yet another implementation of IPFS (InterPlanetary File System) as JiaoziFS will be compatible with the underlying protocol of IPFS.


## A Universe of Uses of JiaoziFS
JiaoziFS's versatility shines across different industries – making it the multi-purpose tool for the **data centric applications and teams**.

* **DataHub & Data Collaboration**: Collaborative Data Science & Dataset Version Management at Scale.
* **Data Engineering & Data Pipelines**: DataOps,AIOps,MLOps.
* **FAIR DataSpace**: FAIR data are data which meet principles of findability, accessibility, interoperability, and reusability (FAIR).
* **Data NFT and Data Containerization**: NFTs allow data to be containerized into shareable, tradeable, and trackable assets.

## Why JiaoziFS?
In production systems with machine learning components, updates and experiments are frequent. New updates to models may be released every day or every few minutes, and different users may see the results of different models as part of A/B experiments or canary releases.

* **Version Everything**: Data scientists are often criticized for being less disciplined with versioning their experiments(versioning of data, pipeline code, and models), especially when using computational notebooks.
* **Track Data Provenance**: This applies to all processing steps in a machine learning pipeline, including data collection/acquisition, data merging, data cleaning, feature extraction, learning, or deployment.
* **Reproducibility**: A final question that is often relevant for debugging, audits, and also science more broadly is to what degree data, models, and decisions can be reproduced.

## Spec
[JiaoziFS Specification](https://github.com/jiaozifs/Spec)

## Quick Start

build
```bash
git clone https://github.com/jiaozifs/jiaozifs.git

make build
```

init and running
```bash
./jzfs init  --db postgres://li:li123@localhost:5432/jiaozifs?sslmode=disable

./jzfs daemon
```
## UI


## Contributors


## Users

