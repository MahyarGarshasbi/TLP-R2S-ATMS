<p align="center">
  <img src="https://raw.githubusercontent.com/MahyarGarshasbi/TLP-R2S-ATMS/main/Figures/FIG.png" width="850">
</p>

---

# Incremental Learning for Passive Microwave Precipitation Retrievals using Advanced Technology Microwave Sounder

**Mahyar Garshasbi**, **Buddha Subedi**, **Ardeshir Ebtehaj**, **Lisa Milani**, **F. Joseph Turk**, and **George J. Huffman**

*Saint Anthony Falls Laboratory, Department of Civil, Environmental, and Geo-Engineering, University of Minnesota*

---

## Abstract

Spaceborne passive microwave (PMW) radiometry is central to global precipitation monitoring, yet retrieval uncertainties remain substantial, particularly for cross-track sounders whose variable footprints and channel configurations are optimized for atmospheric temperature and moisture profiling rather than precipitation. Consequently, existing operational products often exhibit angular-dependent biases, limited effective swath utilization, unrealistic rainfall probability distributions, and systematic misclassification of precipitation phase. These limitations are further compounded by the scarcity of globally accurate and representative precipitation observations, as training data from the Dual-frequency Precipitation Radar (DPR) and the Cloud Profiling Radar (CPR) are spatially sparse, lack uniform global coverage, and exhibit heterogeneous error characteristics across precipitation regimes. To address these challenges, this study presents a supervised retrieval algorithm that incrementally trains an ensemble of extreme gradient-boosted decision trees by augmenting base learners with pre-training on reanalysis data and post-training on coincident DPR and CPR observations matched with the Advanced Technology Microwave Sounder (ATMS). By transferring prior information from reanalysis to posterior constraints from radar observations and adopting a sequential detection–estimation strategy for precipitation phase and rate retrieval, the proposed approach yields retrievals across the full ATMS swath that are largely free from persistent deficiencies in current Global Precipitation Measurement (GPM) passive microwave operational products. In particular, the method resolves bimodal artifacts in rainfall retrievals and mitigates systematic high-latitude snowfall biases, including overestimation across the Arctic and underestimation across the Antarctic. Validation against independent Multi-Radar Multi-Sensor (MRMS) data over the Contiguous United States (CONUS) further demonstrates improved performance in precipitation phase detection and rate estimation relative to both reanalysis and current GPM PMW products.

---

## Code Availability

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1zbpfrCPEeOfcZdJRsDcdscqjnSpjNccT?usp=sharing)

Interactive demo notebook with lightweight training data and orbital retrieval examples.

---

## Contact

📧 garsh011@umn.edu
