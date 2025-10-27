# mm-NOLOC Modeling Dataset

This directory contains the measurement data used for constructing the likelihood model in the mm-NOLOC system.  
It includes data from two cities, **Boston** and **Charlotte**, each containing data from seven gNBs.

---

## Dataset Structure
modeling_dataset/
├── boston/
│ ├── g1.csv
│ ├── g2.csv
│ ├── g3.csv
│ ├── g4.csv
│ ├── g5.csv
│ ├── g6.csv
│ └── g7.csv
└── charlotte/
├── g1.csv
├── g2.csv
├── g3.csv
├── g4.csv
├── g5.csv
├── g6.csv
└── g7.csv


## Notes

- Data were collected and processed under controlled experimental settings (as detailed in our paper).  
- All files share the same basic format and can be used directly for **modeling the likelihood function** used in the mm-NOLOC particle filter.  

---

## Reference

> Phuc Dinh et al., “mm-NOLOC: mmWave-based Localization for Mobile Networks without 3GPP Location Service,”  
> *Proceedings of the 26th ACM International Symposium on Mobile Ad Hoc Networking and Computing (MobiHoc ’25)*,  
> Houston, TX, USA, October 27–30, 2025.

---

**Contact:** dinh.p@northeastern.edu
