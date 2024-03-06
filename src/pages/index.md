---
title: JiaoziFS
sidebar_label: JiaoziFS
slug: /
hide_table_of_contents: true
---
## What is JiaoziFS?
JiaoziFS is an industry-leading **Data-Centric Version Control** File System, helps ensure Responsible AI Engineering by improving **Data Versioning**, **Provenance**, and **Reproducibility**.

Note:
* The name Jiaozi pays tribute to the world's earliest paper money: Song Dynasty Jiaozi.
* JiaoziFS is yet another implementation of [IPFS (InterPlanetary File System)](https://ipfs.tech/) as JiaoziFS will be compatible with the [implementation requirements](https://specs.ipfs.tech/architecture/principles/#ipfs-implementation-requirements) of IPFS.
* As a filesystem of data versioning at scale, although JiaoziFS is built for machine learning, It has a wide range of use scenarios (refer A Universe of Uses) and can be seamlessly integrated into all your data stack.

## Why JiaoziFS?
In production systems with machine learning components, updates and experiments are frequent. New updates to models(data products) may be released every day or every few minutes, and different users may see the results of different models as part of A/B experiments or canary releases.

* **Version Everything**: Data scientists are often criticized for being less disciplined with versioning their experiments(versioning of data, pipeline, code, and models), especially when using computational notebooks.
* **Track Data Provenance**: This applies to all processing steps in an AI/ML pipeline, including data collection/acquisition, data merging, data cleaning, feature extraction, learning, or deployment.
* **Reproducibility**: A final question of AI/ML that is often relevant for debugging, audits, and also science more broadly is to what degree data, models, and decisions can be reproduced.

## A Universe of Uses
JiaoziFS's versatility shines across different industries – making it the multi-purpose tool for the **data centric applications and teams**.

* **Enterprise DataHub & Data Collaboration**: Depending on your operating scale, you may even be managing multiple team members, who may be spread across different locations. JiaoziFS enable Collaborative Datasets Version Management at Scale,Share & collaborate easily: Instantly share insights and co-edit with your team.
* **DataOps**: Augmenting Enterprise Data Development and Operations,JiaoziFS ensures Responsible DataOps/AIOps/MLOps by improving Data Versioning, Provenance, and Reproducibility.
* **Data Mesh**: Versioning data products in a maturing Data Mesh environment via standard processes, data consumers can be informed about both breaking and non-breaking changes in a data product, as well as retirement of data products.
* **Data Products**: JiaoziFS makes a fusion of data science and product development and allows data to be containerized into shareable, tradeable, and trackable assets(data products or data NFTs).
* **Digital Twins for Manufacturing**: Developing digital twins for manufacturing involves managing tons of large files and multiple iterations of a project. All of the data collected and created in the digital twin process (and there is a lot of it) needs to be managed carefully. JiaoziFS allows you to manage changes to files over time and store these modifications in a database.

## Spec
[JiaoziFS Specification](https://github.com/jiaozifs/Spec)

## Quick Start
[JiaoziFS Github](https://github.com/jiaozifs/jiaozifs)

#### Requirement
1. To build JiaoziFS, you need a working installation of   [Go 1.20.10 or higher](https://golang.org/dl/)
2. JiaoziFS use postgres to store running data, you can install at  [postgres install installation guide](https://www.postgresql.org/docs/current/installation.html)

#### Build And Running

1. clone and build
```bash
git clone https://github.com/jiaozifs/jiaozifs.git
cd jiaozifs
make build
```
After following the above steps, you should be able to see an executable file named "jzfs."

2. init program and running
```bash
./jzfs init  --db postgres://<username>:<password>@localhost:5432/jiaozifs?sslmode=disable
./jzfs daemon
```

## Cloud
[Try without installing](https://cloud.jiaozifs.com)

## Contributors

<a href="https://github.com/hunjixin" target="_blank"><img src="https://avatars.githubusercontent.com/u/41407352?v=4" width="5%" height="5%"/></a> <a href="https://github.com/Brownjy" target="_blank"><img src="https://avatars.githubusercontent.com/u/54040689?v=4" width="5%" height="5%"/></a> <a href="https://github.com/TsumikiQAQ" target="_blank"><img src="https://avatars.githubusercontent.com/u/116857998?v=4" width="5%" height="5%"/></a> <a href="https://github.com/taoshengshi" target="_blank"><img src="https://avatars.githubusercontent.com/u/33315004?v=4" width="5%" height="5%"/></a>
  
  
## Users
Join the JiaoziFS community to discuss open problems, share ideas, and get help from the community.

[Join the JiaoziFS community](https://forms.gle/r1esBSSjSLbdyotA9)
  

