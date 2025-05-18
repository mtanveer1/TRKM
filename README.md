# TRKM: Twin Restricted Kernel Machines for Classification and Regression

Please cite the following paper if you are using this code. Reference: A. Quadir, and M. Tanveer. TRKM: Twin Restricted Kernel Machines for Classification and Regression.


%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%% 
The experiments are executed on a computing system possessing Python 3.11 software, an Intel(R) Xeon(R) CPU E5-2697 v4 processor operating at 2.30 GHz with 128-GB Random Access Memory (RAM), and a Windows-11 operating platform.

We have put a demo of the “TRKM” model for classification and regression.

Description of files: 
main.m: This is the main file to run selected algorithms on datasets. In the path variable specificy the path to the folder containing the codes and datasets on which you wish to run the algorithm. 
TRKM.py: Solving the optimization problem.

The following are the best hyperparameters set with respect to the “aus” dataset for classification problem.
Regularization Parameter c_1=0.1 , c_2= 0.001,  mew = 4

The following are the best hyperparameters set with respect to the “Abalone” dataset for regression problem.
Regularization Parameter c_1=0.01 , c_2= 0.00001,  mew = 8


For the detailed experimental setup, please follow the paper. If you find any bugs/issues, please write to A. Quadir (mscphd2207141002@iiti.ac.in).


