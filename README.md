# CBTN Advanced Analytics Workshop: Multi-modal Imaging Analysis

Course materials for education session held at the [CBTN Annual Summit](https://network.cbtn.org/cbtn-summit/) (Oct 9, 2024) at AWS Headquarters in Arlington, VA.

Participants are first guided through accessing and interacting with the CBTN imaging (MRI and digital pathology) data in Flywheel. Through the web browser interface they run processing "gears" to prepare imaging (radiomic) feature sets.

`flywheel_preprocessing.ipynb` shows how to implement the same gear processing using Flywheel's Python SDK.

`radiogenomic_clustering.ipynb` demonstrates how to run a machine learning (unsupervised clustering) analysis using the extracted radiomic features, and compare imaging-based cluster assignments to the patients' corresponding molecular subtypes (derived from the [Open Pediatric Cancer project](https://github.com/d3b-center/OpenPedCan-analysis)).
