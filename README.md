# Magnolia

We will focus on three independent problems. These are:

1. **Monaural source separation** - 
   Using [source contrastive estimation](https://arxiv.org/abs/1705.04662) (submitted to SiPS 2017).
2. Removing a source (whose location is static) that is dynamic and loud.
3. Multiple moving sources (i.e., the channel changes with time) 
4. Standoff distance acoustic enhancement (dynamic gain adjustment in low SNR)

This project will be primarily an analysis of cost functions (in supervised and unsupervised settings) that can be used in order to denoise and isolate signals. The resulting algorithms of interest will be a mix of cost function resembling ICA and simulated beamforming methods. 

## Installation

If you'd like to just call the code in the repository:
```
pip install --upgrade --no-deps git+https://github.com/lab41/magnolia
```

To update our files and edit our code as well as look at our notebooks:
```
git clone https://github.com/lab41/magnolia
pip install --upgrade --no-deps magnolia/
```
Our notebooks are located at:
```
magnolia/src/notebooks
```


## Subdirectory contents:

### Data
- Directory: [`data`](https://github.com/Lab41/Magnolia/tree/master/data)
- Contents: Data.

### Documentation
- Directory: [`docs`](https://github.com/Lab41/Magnolia/tree/master/docs)
- Contents: Documentation, including initial pitch and planning.

### Source Code 
- Directory: [`src`](https://github.com/Lab41/Magnolia/tree/master/src)
- Contents: Source code.

### Sandbox
- Directory: [`sandbox`](https://github.com/Lab41/Magnolia/tree/master/sandbox)
- Contents: Code we used to play around with certain algorithms

### Utility
- Directory: [`util`](https://github.com/Lab41/Magnolia/tree/master/util)
- Contents: Utility and reference, including required installation packages

### Evaluation
- Directory: [`evaluation`](https://github.com/Lab41/Magnolia/tree/master/evaluation)
- Contents: Evaluation code
