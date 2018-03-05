# Neural Interaction Detection (NID)
[M. Tsang](http://www-scf.usc.edu/~tsangm/), [D. Cheng](http://www-scf.usc.edu/~dehuache/), [Y. Liu](http://www-bcf.usc.edu/~liu32/). [Detecting Statistical Interactions from Neural Network Weights](https://openreview.net/pdf?id=ByOfBggRZ), ICLR 2018.


## Usage


- Run demo at "neural\_interaction\_detector\_demo.ipynb"
	* the demo trains a simple multilayer perceptron on synthetic data containing interactions with nonlinearities. at the end of the notebook the interactions are found from decoding weights 
- requires python 3.0+ and jupyter notebook, tested with tensorflow 1.2, scikit-learn 0.19, numpy 1.13.1


## Reference
If you use NID in your research, please cite the following:

```
@article{
  tsang2018detecting,
  title={Detecting Statistical Interactions from Neural Network Weights},
  author={Tsang, Michael and Cheng, Dehua and Liu, Yan},
  journal={International Conference on Learning Representations},
  year={2018},
  url={https://openreview.net/pdf?id=ByOfBggRZ},
  note={accepted as poster},
}
```

