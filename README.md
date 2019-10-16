# intersubj_rsa

This repository contains data and code associated with the following preprint:

*Idiosynchrony: From shared responses to individual differences during naturalistic neuroimaging*<br>
Emily S. Finn, Enrico Glerean, Arman Y. Khojandi, Dylan Nielson, Peter J. Molfese, Daniel A. Handwerker, Peter A. Bandettini<br>
--bioRxiv link to appear after posting--

The code is contained in two Jupyter Notebooks:

1) `isRSA_simulations.ipynb` reproduces the analyses shown in Fig. 2, which simulate different theoretical structures for brain-behavior representational similarity matrices.

2) `isRSA_HCP_demo.ipynb` reproduces the analyses shown in Figs. 3 & 4, which show how inter-subject RSA can be empirically applied to movie-watching data from the Human Connectome Project. To run this notebook, you will need the individual-subject nodewise timecourses, which can be found in the folder `all_shen268_roi_ts`. You will also need the behavioral data from the HCP. The unrestricted behavioral data, which is freely available for download from the HCP, is included here for convenience (`unres_behav_data.csv`). The restricted behavioral data, which is necessary to take into account family structure when forming the two cohorts, requires signing a data-use agreement (DUA) and must be obtained through the HCP by individual investigators. See here for more information: https://www.humanconnectome.org/study/hcp-young-adult/document/restricted-data-usage. Once you have obtained the restricted data, you can save it as `res_behav_data.csv` to maintain compatibility with this notebook.
