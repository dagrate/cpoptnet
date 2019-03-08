# predicting_sparse_actions_with_cpoptnet

CPOPT-Net is a Python library that allows to perform a non-linear conjugate gradient resolution of the CP decomposition to remove the sparsity within your data. Furthermore, latent predictions are achieved with neural networks including CNN, LSTM, MLP and the decision trees from machine learning. 

----------------------------

## Dependencies

The library uses **Python 3** and the following modules:
- numpy (pip install numpy)
- keras
- matplotlib
- sklearn

It is advised to install BLAS/LAPACK to increase the efficiency of the computations:  
sudo apt-get install libblas-dev liblapack-dev gfortran

----------------------------

## Citing

If you use CPOPT-Net in a paper, please cite:

```bibtex
@inproceedings{charlier2018non,
  title={Predicting Sparse Clients' Actions with CPOPT-Net in the Banking Environment},
  author={Charlier, Jeremy and State, Radu and others},
  booktitle={Advances in Artificial Intelligence 2019},
  pages={},
  year={2019},
  organization={Springer}
}
```
