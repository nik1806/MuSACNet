Course Project for Proababilistic Graphical Models course project

MuSACNet: Multi-scale Structured Attention guidedCRF based network for Stereo Matching

Majority of recent works on Stereo matching uses concept of probabilistic graphical models (e.g. asCRF) in final stages with aim to make the output smooth. In this work, we explored an unconventionaluse of CRF using mean-field updates to refine the information from feature extractor part (encoder)in a Siamese-like architecture.  We also proposed one hybrid (CRF + 3D CNN) to compare withbaseline and MuSACNet in similar tuning for training. The results obtain from hybrid model, whichwas also inspired from idea of exploiting multi-scale features, comes out to not perform well enough.With our analysis, we state the reason being requirement of 3D CNN a larger receptive field whichwas not fulfilled through hybrid model. The results obtained from MuSACNet show huge potentialin the unconventional use of graphical models, both in terms of better disparity maps and inferencespeed (due to absence of 3D CNN). We hope that our works helps in exploring uses of probabilisticgraphical models in more innovative methods. 

Team:
Nikhil Paliwal 
Pankhuri Vanjani


