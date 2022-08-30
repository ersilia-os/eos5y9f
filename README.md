# MolPMoFiT
## Model identifiers
- Slug: molpmofit
- Ersilia ID: eos5y9f
- Tags: transferlearning

# Model description
Short description of the model in one or two sentences.
- Input:
- Output: {unit and description of output) 
- Model type: (Regression or Classification)
- Training set: (number of compounds and link to the training data)
- Mode of training: Pretrained General Model & Re-Trained Fine-Tuned Model 

# Source code
Li X, Fourches D. Inductive transfer learning for molecular activity prediction: Next-Gen QSAR Models with MolPMoFiT. J Chemoinform 12, 27(2020). https://doi.org/10.1186/s13321-020-00430-x
- Code: https://github.com/XinhaoLi74/MolPMoFiT
- Checkpoints: Available for download, under "Pre-trained Models Download" on GitHub README file. 

# License
Ersilia License: GPL v3 license 
MolPMoFiT's original journal article is licensed under a Creative Commons Attribution 4.0 International License, which permits use, sharing, adaptation, distribution and reproduction in any medium or format, as long as you give appropriate credit to the original author(s) and the source, provide a link to the Creative Commons licence, and indicate if changes were made. The images or other third party material in this article are included in the article's Creative Commons licence, unless indicated otherwise in a credit line to the material. If material is not included in the article's Creative Commons licence and your intended use is not permitted by statutory regulation or exceeds the permitted use, you will need to obtain permission directly from the copyright holder. To view a copy of this licence, visit http://creativecommons.org/licenses/by/4.0/. The Creative Commons Public Domain Dedication waiver (http://creativecommons.org/publicdomain/zero/1.0/) applies to the data made available in this article, unless otherwise stated in a credit line to the data.

# History 
- Code base downloaded from [GitHub](https://github.com/XinhaoLi74/MolPMoFiT) on 8/29/2022. 
- The original .pth file including the model weights (ChemBL_atom_encoder.pth, available for download as listed above) was missing keys that a fastai method was looking for. A function was written to rename these keys, as well as include an empty "tensor" for key "1.decoder.bias”. 

# About us
The [Ersilia Open Source Initiative](https://ersilia.io) is a Non Profit Organization ([1192266](https://register-of-charities.charitycommission.gov.uk/charity-search/-/charity-details/5170657/full-print)) with the mission is to equip labs, universities and clinics in LMIC with AI/ML tools for infectious disease research.

[Help us](https://www.ersilia.io/donate) achieve our mission or [volunteer](https://www.ersilia.io/volunteer) with us!
