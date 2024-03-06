---
slug: /
sidebar_position: 1
---

# Introduction

JiaoziFS is an industry-leading **Data-Centric Version Control** File System, helps ensure Responsible AI Engineering by improving **Data Versioning**, **Provenance**, and **Reproducibility**.

Note:

- The name Jiaozi pays tribute to the world's earliest paper money: Song Dynasty Jiaozi.
- JiaoziFS is yet another implementation of [IPFS (InterPlanetary File System)](https://ipfs.tech/) as JiaoziFS will be compatible with the [implementation requirements](https://specs.ipfs.tech/architecture/principles/#ipfs-implementation-requirements) of IPFS.
- As a filesystem of data versioning at scale, although JiaoziFS is built for machine learning, It has a wide range of use scenarios (refer A Universe of Uses) and can be seamlessly integrated into all your data stack.

## Why JiaoziFS?

In production systems with machine learning components, updates and experiments are frequent. New updates to models(data products) may be released every day or every few minutes, and different users may see the results of different models as part of A/B experiments or canary releases.

- **Version Everything**: Data scientists are often criticized for being less disciplined with versioning their experiments(versioning of data, pipeline, code, and models), especially when using computational notebooks.
- **Track Data Provenance**: This applies to all processing steps in an AI/ML pipeline, including data collection/acquisition, data merging, data cleaning, feature extraction, learning, or deployment.
- **Reproducibility**: A final question of AI/ML that is often relevant for debugging, audits, and also science more broadly is to what degree data, models, and decisions can be reproduced.

## How does it work?

The working principle of **JiaoziFS** is based on the concept of **IPFS (InterPlanetary File System)**, utilizing **distributed data storage** and **version control mechanisms** to ensure **data traceability** and **reproducibility**. When using **JiaoziFS**, data is segmented into small chunks and stored across multiple nodes in a distributed network. Each data chunk is assigned a unique hash value for identification and retrieval. Additionally, **JiaoziFS** records **version information** for each data chunk, allowing users to track the history of data changes.

When accessing specific versions of data, **JiaoziFS** retrieves the corresponding data chunks from the distributed network based on version information and assembles them into complete files or datasets. This distributed storage and version control mechanism not only ensures data security and reliability but also provides efficient means of data access and management.

In summary, **JiaoziFS** draws upon the core ideas of **IPFS** and implements customized functionalities for **data version control**, making it a powerful **data management tool** suitable for various data processing and analysis needs across different scenarios.