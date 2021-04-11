# AdaBoost

### SVM (linear kernel) - validation accuracy
>> model_try = svmtrain(y,x, '-t 0 -v 10')
.....
WARNING: using -h 0 may be faster
*.
WARNING: using -h 0 may be faster
*
optimization finished, #iter = 5733
nu = 0.881591
obj = -9765.409714, rho = -0.582717
nSV = 9925, nBSV = 9906
Total nSV = 9925
.....
WARNING: using -h 0 may be faster
*.
WARNING: using -h 0 may be faster
*
optimization finished, #iter = 5852
nu = 0.881596
obj = -9757.691955, rho = -0.549743
nSV = 9927, nBSV = 9904
Total nSV = 9927
.....
WARNING: using -h 0 may be faster
*
optimization finished, #iter = 5787
nu = 0.880343
obj = -9750.337489, rho = -0.616941
nSV = 9917, nBSV = 9892
Total nSV = 9917
.....
WARNING: using -h 0 may be faster
*.
WARNING: using -h 0 may be faster
*
optimization finished, #iter = 5986
nu = 0.879647
obj = -9741.398223, rho = -0.596937
nSV = 9908, nBSV = 9884
Total nSV = 9908
.....
WARNING: using -h 0 may be faster
*.
WARNING: using -h 0 may be faster
*
optimization finished, #iter = 5910
nu = 0.883974
obj = -9788.483840, rho = -0.555871
nSV = 9954, nBSV = 9933
Total nSV = 9954
.....
WARNING: using -h 0 may be faster
*
optimization finished, #iter = 5629
nu = 0.878760
obj = -9737.112119, rho = -0.614682
nSV = 9901, nBSV = 9873
Total nSV = 9901
.....
WARNING: using -h 0 may be faster
*.
WARNING: using -h 0 may be faster
*
optimization finished, #iter = 5952
nu = 0.882430
obj = -9776.390321, rho = -0.523877
nSV = 9938, nBSV = 9917
Total nSV = 9938
.....
WARNING: using -h 0 may be faster
*.
WARNING: using -h 0 may be faster
*
optimization finished, #iter = 6240
nu = 0.882947
obj = -9782.679569, rho = -0.621197
nSV = 9943, nBSV = 9920
Total nSV = 9943
.....
WARNING: using -h 0 may be faster
*.
WARNING: using -h 0 may be faster
*
optimization finished, #iter = 5943
nu = 0.883260
obj = -9776.224615, rho = -0.661624
nSV = 9950, nBSV = 9923
Total nSV = 9950
.....
WARNING: using -h 0 may be faster
*.
WARNING: using -h 0 may be faster
*
optimization finished, #iter = 5970
nu = 0.883553
obj = -9785.463643, rho = -0.567659
nSV = 9949, nBSV = 9926
Total nSV = 9949
Cross Validation Accuracy = 59.68%

model_try =

   59.6800

### SVM (polynomial kernel) - validation accuracy

>> model_try_poly = svmtrain(y,x, '-t 1 -d 5 -v 10')
.....
WARNING: using -h 0 may be faster
*
optimization finished, #iter = 5625
nu = 1.000000
obj = -11250.000000, rho = -0.000000
nSV = 11250, nBSV = 11250
Total nSV = 11250
.....
WARNING: using -h 0 may be faster
*
optimization finished, #iter = 5625
nu = 1.000000
obj = -11250.000000, rho = -0.000000
nSV = 11250, nBSV = 11250
Total nSV = 11250
.....
WARNING: using -h 0 may be faster
*
optimization finished, #iter = 5625
nu = 1.000000
obj = -11250.000000, rho = -0.000000
nSV = 11250, nBSV = 11250
Total nSV = 11250
.....
WARNING: using -h 0 may be faster
*
optimization finished, #iter = 5625
nu = 1.000000
obj = -11250.000000, rho = -0.000000
nSV = 11250, nBSV = 11250
Total nSV = 11250
.....
WARNING: using -h 0 may be faster
*
optimization finished, #iter = 5625
nu = 1.000000
obj = -11250.000000, rho = -0.000000
nSV = 11250, nBSV = 11250
Total nSV = 11250
.....
WARNING: using -h 0 may be faster
*
optimization finished, #iter = 5625
nu = 1.000000
obj = -11250.000000, rho = -0.000000
nSV = 11250, nBSV = 11250
Total nSV = 11250
.....
WARNING: using -h 0 may be faster
*
optimization finished, #iter = 5625
nu = 1.000000
obj = -11250.000000, rho = -0.000000
nSV = 11250, nBSV = 11250
Total nSV = 11250
.....
WARNING: using -h 0 may be faster
*
optimization finished, #iter = 5625
nu = 1.000000
obj = -11250.000000, rho = -0.000000
nSV = 11250, nBSV = 11250
Total nSV = 11250
.....
WARNING: using -h 0 may be faster
*
optimization finished, #iter = 5625
nu = 1.000000
obj = -11250.000000, rho = -0.000000
nSV = 11250, nBSV = 11250
Total nSV = 11250
.....
WARNING: using -h 0 may be faster
*
optimization finished, #iter = 5625
nu = 1.000000
obj = -11250.000000, rho = -0.000000
nSV = 11250, nBSV = 11250
Total nSV = 11250
Cross Validation Accuracy = 50.016%

model_try_poly =

   50.0160

 
>> model_all_linear = svmtrain(y,x,'-t 0')
......
WARNING: using -h 0 may be faster
*.
WARNING: using -h 0 may be faster
*
optimization finished, #iter = 6540
nu = 0.880334
obj = -10836.648029, rho = -0.572751
nSV = 11019, nBSV = 10990
Total nSV = 11019

model_all_linear = 

  struct with fields:

    Parameters: [5×1 double]
      nr_class: 2
       totalSV: 11019
           rho: -0.5728
         Label: [2×1 double]
    sv_indices: [11019×1 double]
         ProbA: []
         ProbB: []
           nSV: [2×1 double]
       sv_coef: [11019×1 double]
           SVs: [11019×64 double]

>> model_all_poly = svmtrain(y,x,'-t 1 -d 5')
......
WARNING: using -h 0 may be faster
*
optimization finished, #iter = 6250
nu = 1.000000
obj = -12500.000000, rho = -0.000000
nSV = 12500, nBSV = 12500
Total nSV = 12500

model_all_poly = 

  struct with fields:

    Parameters: [5×1 double]
      nr_class: 2
       totalSV: 12500
           rho: -6.2973e-09
         Label: [2×1 double]
    sv_indices: [12500×1 double]
         ProbA: []
         ProbB: []
           nSV: [2×1 double]
       sv_coef: [12500×1 double]
           SVs: [12500×64 double]

### linear kernal testing accuracy
>> [accuracy] = svmpredict(y_t, x_t, model_all_linear);
Accuracy = 59.2% (7400/12500) (classification)

### linear kernal training accuracy
>> [accuracy] = svmpredict(y, x, model_all_linear);
Accuracy = 60.12% (7515/12500) (classification)

### polynomial kernal testing accuracy
>> [accuracy] = svmpredict(y_t, x_t, model_all_poly);
Accuracy = 50.048% (6256/12500) (classification)

### polynomial kernal training accuracy
>> [accuracy] = svmpredict(y, x, model_all_poly);
Accuracy = 50.024% (6253/12500) (classification)
>> svm_model_matlab
Unrecognized function or variable 'svm_model_matlab'.
 
### Boosting SVM for 10 iterations
 
>> Adaboost
     1

Training error of the strong classifier = 0.420880 
Error of the strong classifier on the test set = 0.423440 

     2

Training error of the strong classifier = 0.420880 
Error of the strong classifier on the test set = 0.423440 

     3

Training error of the strong classifier = 0.392240 
Error of the strong classifier on the test set = 0.404640 

     4

Training error of the strong classifier = 0.391200 
Error of the strong classifier on the test set = 0.400560 

     5

Training error of the strong classifier = 0.385040 
Error of the strong classifier on the test set = 0.391440 

     6

Training error of the strong classifier = 0.387920 
Error of the strong classifier on the test set = 0.394960 

     7

Training error of the strong classifier = 0.378480 
Error of the strong classifier on the test set = 0.385120 

     8

Training error of the strong classifier = 0.377920 
Error of the strong classifier on the test set = 0.384400 

     9

Training error of the strong classifier = 0.373040 
Error of the strong classifier on the test set = 0.377680 

    10

Training error of the strong classifier = 0.371520 
Error of the strong classifier on the test set = 0.380000 


### Boosting SVM for 20 iterations
>> Adaboost
     1

Training error of the strong classifier = 0.420880 
Error of the strong classifier on the test set = 0.423440 

     2

Training error of the strong classifier = 0.420880 
Error of the strong classifier on the test set = 0.423440 

     3

Training error of the strong classifier = 0.392240 
Error of the strong classifier on the test set = 0.404640 

     4

Training error of the strong classifier = 0.391200 
Error of the strong classifier on the test set = 0.400560 

     5

Training error of the strong classifier = 0.385040 
Error of the strong classifier on the test set = 0.391440 

     6

Training error of the strong classifier = 0.387920 
Error of the strong classifier on the test set = 0.394960 

     7

Training error of the strong classifier = 0.378480 
Error of the strong classifier on the test set = 0.385120 

     8

Training error of the strong classifier = 0.377920 
Error of the strong classifier on the test set = 0.384400 

     9

Training error of the strong classifier = 0.373040 
Error of the strong classifier on the test set = 0.377680 

    10

Training error of the strong classifier = 0.371520 
Error of the strong classifier on the test set = 0.380000 

    11

Training error of the strong classifier = 0.367840 
Error of the strong classifier on the test set = 0.380480 

    12

Training error of the strong classifier = 0.369520 
Error of the strong classifier on the test set = 0.379520 

    13

Training error of the strong classifier = 0.366800 
Error of the strong classifier on the test set = 0.379120 

    14

Training error of the strong classifier = 0.368240 
Error of the strong classifier on the test set = 0.378960 

    15

Training error of the strong classifier = 0.367360 
Error of the strong classifier on the test set = 0.374480 

    16

Training error of the strong classifier = 0.364960 
Error of the strong classifier on the test set = 0.370640 

    17

Training error of the strong classifier = 0.364960 
Error of the strong classifier on the test set = 0.370800 

    18

Training error of the strong classifier = 0.363120 
Error of the strong classifier on the test set = 0.373760 

    19

Training error of the strong classifier = 0.363680 
Error of the strong classifier on the test set = 0.371760 

    20

Training error of the strong classifier = 0.366160 
Error of the strong classifier on the test set = 0.372880 

>> 
