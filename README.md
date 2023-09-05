# DCM-Lattice

# A New Flexible and Partially Monotonic Discrete Choice Model
This code implements the paper, Kim and Bansal, A New Flexible and Partially Monotonic Discrete Choice Model (May 15, 2023). Available at SSRN: https://ssrn.com/abstract=4448172 or http://dx.doi.org/10.2139/ssrn.4448172

## Overview
This model is a flexible and partially monotonic DCM by specifying the systematic utility using the Lattice networks (i.e., DCM-LN), which ensures monotonicity of the utility function relative to the selected attributed while learning the non-linear and interaction effects of attributes in a data-driven manner. 

## Getting Started

### Dependencies
* Python 3.11.4
* Tensorflow 2.13.0 , Keras 2.13.1, Tensorflow-lattice 2.0.11

### Components

#### Dataset
* 'data' contains the Swissmetro dataset, open-source stated preference choice data.
* More details on this dataset and some examples based on this dataset is provided in the https://transp-or.epfl.ch/pythonbiogeme/examples_swissmetro.html 

##### METRO_ASC_ING_FFT_Published.ipynb
* In this one notebook, we contain all code from preprocessing, benchmark modelling (e.g., multinomial logit model, deep neural network), and the proposed modelling.
* Since all functions and class structures have been broken down, you can easily understand the code if you follow them step-by-step.


## Notice
* Full paper will be provided after the peer-review process, but you can refer to the SSRN draft.
* Detailed logic behind the code is described in the full paper

## Authors
[@Eui-Jin Kim](https://sites.google.com/view/euijinkim)


## License

This project is licensed under the MIT License - see the LICENSE.md file for details

## Acknowledgments
* [Deep Lattice Network](https://github.com/tensorflow/lattice)

