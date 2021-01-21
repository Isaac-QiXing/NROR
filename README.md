# NROR
* This package is about the python implementation of online regression with canal loss.

* The codes are implemented by Python 3.7

* folders and functions:
 ./demo_NROR.py: a demo to run NROR wherein the number of training samples and those for cross-validation are 
         set as a relatively small integers
 ./dataset/: consists of the demo data files 
 ./plot-pseudo-convex/: consists of the code to depict the regularized canal loss 

  ./libsvm-3-24/: consists of  libsvm library (version 3.24)
      imported from https://www.csie.ntu.edu.tw/~cjlin/libsvm/
	The package is mainly used to load some benchmark datasets of LIBSVM format;  

  ./pynolre/: consists of the codes related to noise-resiliet online regression (NROR)
   ./pynolre/main_f1.py: main function to run NROR on f1 simulated dataset
   ./pynolre/main_interval_inner.py: main function to run NROR on simulated
datasets to check the intervals 

    ./pynolre/main_interval_inner_present-result.py: main function to show the results of the  intervals 
   ./pynolre/nolre1.py: a class for kernel-based noise-resilient Online
Learning regression
   ./pynolre/nolre_cv.py: a class for cross-validation 
   ./pynolre/kernel.py: several classes for Linear kernel, Gaussian kernel and
RBF kernel 
   ./pynolre/loss.py: several classes for the Linear loss,
Quadratic-insensitive loss, canal loss and pseudo-Huber loss
   ./pynolre/nonlinear_fun.py: implement several simulated nonlinear function,
including f1, boha, branin, forrester, powell, levy, trid  
   ./pynolre/generate_sample.py: for producing sythetic samples 
   ./pynolre/qarray.py: define a class QArray,  a class for storing paired of elements, (x,y), with limited memory
   ./pynolre/s.py: define a function which dynamically updates the parameter of delta of
the canal loss; 
  ./pynolre/mykernelFun.py: define a class of kernel function 
  ./main_plot_result_baseline_dataset.py: plot the prediction metrics on the
baseline datasets 
  ./main_print_result_f1_xls.py: print the result of f1 to Excel file 
  ./main-CrossValidation-20210101: a main function to call NROR, with the
parameters selected by cross-validation; 
  ./main_readData.py:   read  benchmark datasets from raw data files 
  ./ReadMe.txt: this file

    

* The files could be used freely for your research once you cite the following work

  Xijun Liang, Zhipeng Zhang, Yunquan Song and Ling Jian, Kernel-based Online Regression with Canal Loss.
  European Journal of Operational Research, under revision, 2021.

 For commercial usage of this package, please contact    Xijun Liang:  liangxijunsd@163.com
 



 
  






