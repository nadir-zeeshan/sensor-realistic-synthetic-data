# NTIRE '2O: Sensor-realistic Synthetic Data Engine for Multi-frame High Dynamic Range Photography

## Get Started
- This repo examplifies several pure synthetic data we used in our work "Sensor-realistic Synthetic Data Engine for Multi-frame High Dynamic Range Photography, Jinhan Hu,, Gyeongmin Choe, Zeeshan Nadir, Osama Nabil, Seok-Jun Lee, Hamid Sheikh, Youngjun Yoo, and Michael Polley". Please refer to the paper for more details.

- The complete dataset can be downloaded at

## Synthetic Dataset Examples
### Synthetic Dataset 1
- This synthetic dataset is captured at two exposure levels statically and dynamically (i.e., static_ and dynamic_ at EV-3 (low) and EV0 (high)). We use a proprietary algorithm to compute the Blendmap first and then use the exposure fusion algorithm to generate the HDR ground-truth for this dataset.

- Three examples below.

<img src="./Synthetic_Dataset_1_Sample/dataset_1_example.png" width="960">

### Synthetic Dataset 2
- This synthetic dataset is captured at three exposure levels statically and dynamically (i.e., static_ and dynamic_ at EV-2 (low), EV0 (mid), and EV2 (high)). We follow the linear triangular method to generate the HDR ground-truth for this dataset.

- Two examples below.

<img src="./Synthetic_Dataset_2_Sample/dataset_2_example.png" width="960">

## Dataset Usage

- Download the complete pure synthetic dataset. This is the starting point for readers to generate the sensor-realistic synthetic dataset targeted on their mobile devices

- Model the color space and noise characteristics (sensor realism) of your targeted mobile device.

- Apply the modeled sensor realism to pure synthetic dataset, converting the pure synthetic dataset into the sensor-realistic synthetic dataset.

- Train your network model using the sensor-realistic synthetic dataset.

## Citation

## License

- You are free to:
  - Share — copy and redistribute the material in any medium or format
  - Adapt — remix, transform, and build upon the material

- Under the following terms:
  - Attribution — You must give appropriate credit, provide a link to the license, and indicate if changes were made. You may do so in any reasonable manner, but not in any way that suggests the licensor endorses you or your use.  NonCommercial — You may not use the material for commercial purposes.
  - To make use of the data, please site the paper "Sensor-realistic Synthetic Data Engine for Multi-frame High Dynamic Range Photography" appeared in NTIRE Workshop 2020: CVPR 2020.

- Complete terms and conditions of the license can be found in the accompanied file "license_terms.pdf", also given at the url: https://creativecommons.org/licenses/by-nc/4.0/legalcode