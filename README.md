# libsvm

## Forked Repo for CSE 569S
This repo is forked and refactored from the popular libsvm https://github.com/cjlin1/libsvm for CSE 569S.

Changes made in the framework include:

* Removed interfaces to other languages.
* Removed data expansion function to simplify the program.
* Added a sample dataset from the original program's website.
* Added a cmake file to simplify building process.
* Replaced deprecated libraries. 
* Code reformat.
* And more.

If you don't like this simplified version, you are welcome to directly use the original program from the link above.

## Description

Generate Makefile
```shell script
cmake . 
```
    
    
Build the program
```shell script
make
```

Please see the original repo and its website https://www.csie.ntu.edu.tw/~cjlin/libsvm/ for detailed instructions.


## Example

```shell script
./svm-train data/a1a test_model
```

optimization finished, #iter = 537
nu = 0.460270
obj = -673.031415, rho = 0.628337
nSV = 754, nBSV = 722
Total nSV = 754

```shell script
./svm-predict data/a1a.t test_model output
```

Accuracy = 83.5864% (25875/30956) (classification)
