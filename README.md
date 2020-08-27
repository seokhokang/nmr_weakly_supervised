# nmr_weakly_supervised
Tensorflow implementation of the model described in the paper [Predictive Modeling of NMR Chemical Shifts without Atom-level Annotations](https://doi.org/10.1021/acs.jcim.0c00494)

## Components
- **preprocessing.py** - script for data preprocessing
- **run_train.py** - script for model training
- **run_eval.py** - script for model evaluation
- **MPNN.py** - model architecture
- **util.py**

## Data
- **NMRShiftDB2** - https://nmrshiftdb.nmr.uni-koeln.de/
- The datasets used in the paper can be downloaded from
  - https://jcheminf.biomedcentral.com/articles/10.1186/s13321-019-0374-3
  - https://static-content.springer.com/esm/art%3A10.1186%2Fs13321-019-0374-3/MediaObjects/13321_2019_374_MOESM2_ESM.gz
  
## Dependencies
- **Python**
- **TensorFlow**
- **RDKit**
- **NumPy**
- **scikit-learn**
- **sparse**

## Citation
```
@Article{Kang2020,
  title={Predictive Modeling of NMR Chemical Shifts without Using Atomic-Level Annotations},
  author={Kang, Seokho and Kwon, Youngchun and Lee, Dongseon and Choi, Youn-Suk},
  journal={Journal of Chemical Information and Modeling},
  volume={60},
  number={8},
  pages={3765-3769},
  year={2020},
  doi={10.1021/acs.jcim.0c00494}
}
```
