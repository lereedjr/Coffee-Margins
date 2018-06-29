#ReadMe: For MSDS -692 Data Science Practicum I - By Sandeep Modi <H1>

Coffee Margin 

I will be researching what location sales the most coffee in the United States. And which location is the most profitable.

Getting Started
The GitHub has the following information about the project: 

	o	DataSet
	o	Code
	o	Project Snap shots 
	o	Weka 
This project was created as a part of a practicum for the Master’s Data Science Certificate program for the Regis University.  

Prerequisites
What things you need to install the software and how to install them
	Tools: 
	o	R-Studio for Clustering 
	o	Machine Learning for K-means
	o	KNN
	o	Tableau
	o	Kmeans-smote
	o	Weka

Installing
Following are the sites where I attained the needed software installation information. 

https://www.rstudio.com/products/rstudio/download
https://machinelearningmastery.com/download-install-weka-machine
www.tableau.com/Tableau/Download
C
oding style 
The codes were generated using RStudio, Tableau and Weka
See code files attached in GitHub 

Deployment
Built With
•	RStudio – IDE tool used with R programming language for statistical computing and graphics.

•	Tableau - used for creating data visualizations, publishing data sources
•	Weka - machine learning algorithms for data mining tasks. The algorithms can either be applied directly to a dataset or called from your own Java code. Weka contains tools for data pre-processing, classification, regression, clustering, association rules, and visualization.


Screenshot
I am using Coffee Chain Sales data for my visualization assignment.  The Coffee Chain Data set has many columns. Data includes Profit, Margin, Sales, COGS, Total Expense, Marketing, Inventory Profit and Budget Margin.  Everything that a good sales report needs. 
The screen shot below also shows that the fat table is linked to Coffee Chain Query, Location and Product 
 
![screen 1](https://user-images.githubusercontent.com/39128523/42069216-7b190dc6-7b1e-11e8-9968-20e7b7754234.jpg)

The below screen shot shows the data sorted in ascending order for the product table.  The product table is populated by selecting the product under the table category on the left panel. Other sort capabilities are in the screen below.  There are about 50 columns of data in the product table. 
 
![screen 2](https://user-images.githubusercontent.com/39128523/42069317-1d0e0eec-7b1f-11e8-82e0-9efdb65d2711.jpg)
 
Profit and sales based on market and area codes 
![screen 3](https://user-images.githubusercontent.com/39128523/42069423-c6b9d764-7b1f-11e8-932d-50c8bf682115.jpg)

 
Sales by Product and State

![screen 4](https://user-images.githubusercontent.com/39128523/42069457-f4e951fa-7b1f-11e8-91b6-a2a0c2c4b09f.jpg)
  
Budgeted profit by states 
 

Code
Relation:     CoffeeChain_CleansedData1
Instances:    4248
Attributes:   09
              Profit
              Margin
              Sales
              COGS
              Total Expenses
              Inventory
              ProductId
              State
              Market
              Market Size
              Product Type
              Product
              Type
Test mode:    evaluate on training data

=== Clustering model (full training set) ===
Number of clusters selected by cross validation: 11
Number of iterations performed: 77
                        Cluster
Attribute                     0         1         2         3         4         5         6         7         8         9        10
                         (0.07)    (0.15)    (0.08)    (0.06)    (0.11)    (0.05)    (0.15)    (0.02)    (0.07)    (0.12)    (0.13)
====================================================================================================================================
Profit
  mean                   37.4674   17.7418  231.2551   17.5491   44.7023   36.3935   87.1128  -36.1409    -4.955   36.0132   108.429
  std. dev.              15.9317   16.0573   62.0165   14.9425   18.1376  336.8307   29.0549   29.5845    6.0569   16.6873   56.3644

Margin
  mean                   66.5998   39.8616  297.2879   39.6453   83.4273  139.8211   118.462   24.8121   71.8531   66.6693  166.2104
  std. dev.               7.5538    9.2053     50.88    9.0163    9.5035  269.7516   15.3107   21.0081   11.1062    6.8049   23.0982

Sales
  mean                  116.8709   67.7756  554.4803   67.3473  149.6107  345.1135  209.2163  128.6101  125.9614  116.8995   296.489
  std. dev.              12.1052   17.6707   66.7899   16.9709   13.9401  287.3939    23.421    20.274   20.1865   11.0982   42.0896

COGS
  mean                    47.886   26.4174    246.27   26.4629   62.5708  195.3722   85.4404  100.9359   51.4286   47.8104  124.4395
  std. dev.               4.5165   10.3086   24.4407     9.662    5.9852   86.5536    8.3487   14.6947    8.2476    4.2111   22.5593

Total Expenses
  mean                   35.3299   25.2927  106.2658   24.6671   46.5778  113.0624    47.295   53.8557   75.1296   36.9347    77.106
  std. dev.               9.9577   11.3827   16.3125   10.9612    8.6132   40.7536   10.4355    4.4068     7.767    9.9965    32.155

Marketing
  mean                   14.9054    7.8192   77.6504    7.7946   20.4521   79.4685   26.5611   31.1026   46.4571   15.0268   53.4987
  std. dev.                 2.23    3.5247   12.4027    3.3402     2.492   36.8358    3.0193    4.8123    7.3691    2.1664   27.1292

Inventory
  mean                  536.2617  597.5147 1491.0506  601.4508  536.1959 1791.0322  654.0731 1284.2777  376.9992  510.8037  870.2877
  std. dev.             205.3595  297.6321  287.4313  295.0868  344.9474  2166.643  188.2557  586.1541  275.2071  197.0404  225.0794

ProductId
  mean                    7.0485    7.3553    7.4813    7.7785    6.1977    5.4266    7.2946    6.1228     6.707    6.5275     6.661
  std. dev.               3.6127    3.7969    3.2771    3.5478    3.6848     3.909     3.759    3.7323    3.6126    3.5816    3.3041

State
  Connecticut             7.1538   14.1377    7.9636    1.0157    9.5239    8.0795    8.5517         3        11   11.5809   12.9932
  Washington              8.9619   17.8274    9.1524    1.0228    4.5125      4.85   14.5386         3         8   10.7165    4.4179
  California             68.7858  155.8672   72.6461    1.0082    66.613   29.2553  119.2505   17.0004   54.0502   91.9035   99.6197
  Texas                  36.8574  122.8833   52.4122    1.0103    47.478   40.1062   80.5577    6.9995    22.003   69.0656   76.6267
  New York               30.6521  100.4186   36.3902    1.0068   54.3429   18.1129   67.1592   10.0004   31.9007   57.1098   59.9065
  Ohio                   18.2974    1.0019   18.2816   58.2899   30.4132    8.7554   38.1551    4.9959   14.9998   35.8807   38.9292
  Illinois               28.0438    1.0025   20.9752   58.0327   40.3378   23.1535   43.6192    8.0247        22   36.8807   31.9299
  Louisiana               5.1536   16.9604    9.9881    1.0396   13.0558    6.0018   10.3835         3         4    9.6632    11.754
  Florida                37.7247   86.6442   24.6755    1.0066   62.1682    20.379   61.5229   13.0007        41   46.9755   48.9027
  Wisconsin               4.8686    1.0008    9.0937   43.9973   18.0885    3.9129   23.5235    4.9997   14.9991   18.7055   20.8104
  Colorado                4.0793    1.0029    5.9803    33.378   11.4462    5.0274   20.3436    6.0001         4   14.4954    9.2468
  Missouri                7.0356    1.0007   18.9157   56.1258   28.8796     14.45   34.6099    8.9995        12   21.3715   30.6117
  Iowa                   12.1675    1.0008   16.0721   26.4443   27.6325    8.5198   22.4895         2         7   24.1829   25.4904
  Massachusetts          12.5322   57.0765   17.9353    1.0059   20.5113   17.5358   34.3684    6.9946   22.9998   30.8119   35.2281
  Oklahoma                6.2978   23.0471   10.3626    1.0399   17.0317    3.6411   22.9774         3    9.9998    9.6631    9.9395
  Utah                    6.4088   13.0581    4.9954    1.0212    4.0618    3.5146    3.9967         1    2.0167   10.4501    7.4767
  Oregon                  3.1221   12.3549    4.0008    1.0193    5.5102    5.3093   11.7527         3         4    8.2549   10.6758
  New Mexico              1.3343    4.6376    4.9445    1.0328    1.9993    1.0566         1         1         2    2.9961    4.9989
  New Hampshire           1.8468   13.8545    4.2711    1.0204    7.0259    2.2656   14.5592         1         7    9.2027   12.9538
  Nevada                  3.0143   21.9583    6.9996    1.0288    4.0661    6.1022   11.8152         2         4   10.9318    9.0838
  [total]               304.3378  666.7355  356.0561  290.5463  474.6984   230.029  645.1746  109.0155  298.9691  530.8422  561.5956
Market
  East                   85.9096  268.1316   87.2357    1.0554  149.5722   62.3728  182.1614   29.9957  109.9005  151.6808  165.9842
  West                    86.293  217.0659   93.7943    1.1003   80.7636   45.0315  157.3536   22.0004   68.0669  128.2567  127.2739
  South                  46.6432  164.5283   74.7074    1.1227   76.5648   47.8057  111.9186   10.9995   35.0028   88.3879  100.3191
  Central                69.4921    1.0097   84.3187  271.2679  151.7978    58.819   177.741   30.0199   69.9989  146.5167  152.0183
  [total]               288.3378  650.7355  340.0561  274.5463  458.6984   214.029  629.1746   93.0155  282.9691  514.8422  545.5956
Market Size
  Small Market           56.3651  129.8383   95.7595  124.8079  130.3878   56.7035  169.1978   24.9992   75.0156  136.7192   150.206
  Major Market          229.9727  518.8971  242.2965  147.7384  326.3106  155.3255  457.9768   66.0163  205.9535   376.123  393.3896
  [total]               286.3378  648.7355  338.0561  272.5463  456.6984   212.029  627.1746   91.0155  280.9691  512.8422  543.5956
Product Type
  Coffee                  1.0754   136.263   83.5952   53.6449  112.2283   52.8396  169.3035   18.9965   51.8992  169.3223   112.832
  Espresso               72.0611   207.383  100.1566   87.0772   160.469   63.3325  187.8869   24.1168   93.0422  169.1026  179.3722
  Herbal Tea             207.951  144.5418   78.3877   71.9287   86.0714   56.7122  142.7874    25.997   66.0207    1.0346  125.5675
  Tea                     7.2503  162.5477   77.9165   61.8955   99.9296   41.1447  129.1966   23.9052   72.0071  175.3827   127.824
  [total]               288.3378  650.7355  340.0561  274.5463  458.6984   214.029  629.1746   93.0155  282.9691  514.8422  545.5956

Product
  Amaretto                1.0013   41.8511   27.4982   23.5169   37.3241   18.0402   59.8675         7   17.9077   53.6255   40.3674
  Columbian               1.4399   46.7641    25.794    18.621   37.4992   18.3551   53.2831    7.0006   19.9917   66.8163    32.435
  Decaf Irish Cream       1.0763   47.7977   30.3053   13.0265   39.3908    19.445   57.1606     7.996   16.9998   50.7926   44.0093
  Caffe Latte             1.5612   48.3782   28.9193   25.5278   49.2054   23.0384   53.8485    8.1167        25   57.9687   42.4359
  Caffe Mocha             2.1512   58.3707   23.8536   24.5629   48.0041    20.188   51.9732         6        24   60.8235    42.073
  Decaf Espresso         76.2904    58.061   18.1154    25.615   34.1395   17.4152   45.0585         8   19.9998    1.2573   58.0477
  Regular Espresso       11.8396   58.1138   34.3239   19.3588   36.8365    7.6522   45.6322    4.0001   28.0423   47.2255   47.9752
  Chamomile              63.2192   42.4022   29.7542   28.0929   33.6351   17.8113   41.8865   13.9979   23.0162    1.0028   46.1817
  Lemon                  64.8629   58.6355   25.5397   19.0733   30.4007   20.5091   46.6935     5.999        24    1.2356   38.0506
  Mint                   70.7872   39.7318   23.0367   24.7808    23.919   16.6062   53.4259    8.0002   25.0041    6.5727   41.1353
  Darjeeling                1.01   64.3894   24.8833   17.7968   32.1815   10.0626   42.4289    4.0001   25.9996    67.871   42.3765
  Earl Grey               1.0522   43.6565   29.3468   14.9294    32.793   14.5246   45.2195    9.9049   26.0078   57.7425   39.8228
  Green Tea               1.0463   51.5835   27.6855   28.6442   32.3695   19.3811   41.6967   12.0001        16   50.9079    39.685
  [total]               297.3378  659.7355  349.0561  283.5463  467.6984   223.029  638.1746  102.0155  291.9691  523.8422  554.5956
Type
  Regular                32.0671  406.3103   213.737  163.0274  291.9631  130.8807  380.0496   50.9978  178.9488  443.8896  333.1285
  Decaf                 254.2707  242.4251  124.3191  109.5189  164.7352   81.1483   247.125   40.0177  102.0203   68.9525  210.4671
  [total]               286.3378  648.7355  338.0561  272.5463  456.6984   212.029  627.1746   91.0155  280.9691  512.8422  543.5956

Time taken to build model (full training data) : 265.15 seconds
=== Model and evaluation on training set ===
Clustered Instances
 0       281 (  7%)
 1       650 ( 15%)
 2       338 (  8%)
 3       271 (  6%)
 4       452 ( 11%)
 5       203 (  5%)
 6       628 ( 15%)
 7        89 (  2%)
 8       279 (  7%)
 9       513 ( 12%)
10       544 ( 13%)
Log likelihood: -44.76923
ProductId
  mean                  9.5    5.1276        13    7.0819     7.173    9.2821     5.444    6.6948     7.077    6.7084    6.6283     7.729    6.1987    7.2716    3.0575    6.4351
  std. dev.             0.5    3.1939    3.6641    3.5803    3.8469    3.6999    2.7324    3.5643    3.3632    3.6133    3.6435    3.6962    3.6625    3.3291    0.9762    3.6955

Inventory
  mean             1213.898 2277.4637 4793.0006  738.5927  581.6138  209.1677  681.4399  568.0905  949.8762  376.8278   477.835  764.7342  658.3575 1419.8212 -368.2051 1829.9446
  std. dev.        458.1412 1169.4548 2205.6923   173.424  150.6688   34.3845  117.3033  208.5463  208.2209  275.5025  228.3562  161.9501  283.5822  273.7267 1334.4647  443.9636

Location
  mean             560.6688  667.6284  741.5417  606.1004  603.1422  564.2834  557.9921   534.691  609.4623  552.3565  577.1097  588.9468  529.4444  614.2446  617.0796  607.1165
  std. dev.         163.052   216.231    36.373  188.7798  238.1878  138.6094  240.2282  233.9952   235.166   222.874  241.8592  225.7434  226.2957  204.3795   198.104  191.1114

Sales
  mean             130.2487  148.7026   25.9167   60.9806  200.0684    79.138  259.1645  105.7432  314.1503  125.9438  129.6003  240.4892  162.4968  518.3336   256.269  679.7185
  std. dev.         20.8536   86.2136    6.3437   15.5882   11.1644   11.5197   42.2644    9.4566   31.1851   20.1701    8.5265   13.7842   11.8038   44.8138  187.8523   87.4647

Marketing
  mean              29.8333   81.1238       100    6.0665   25.9974   11.8731   95.7597   13.3082   39.4974   46.4465   17.2636   28.3489   22.1278   71.2264   24.7842   95.4762
  std. dev.          4.1799   35.8454    7.1995    2.6961    3.0638    1.5618   16.4068    1.7883    5.3614    7.3583    2.5995    2.4729    2.9554    7.8854    8.8658   13.7677

COGS
  mean              97.5818   170.971  264.6667    22.576   81.8747    33.894  105.8163   43.5361   133.699    51.417   53.3206   96.2295   68.4279  235.6394   78.7576  277.7174
  std. dev.         13.4902   49.5186   19.5377    9.7476    4.6811    4.6301   18.1743    3.9908   19.3982    8.2362    3.9806    5.8102    6.4926   21.6283   30.8653     31.96

Total_Expenses
  mean              52.6459    110.55   132.125   18.6223   47.4093   43.4214  125.3643   31.7698   61.6669   75.1163   42.1256   45.6326   47.4805   98.6777   52.0103  131.6319
  std. dev.          3.6314    36.782     7.299    4.8111   11.1371    3.1882   16.5359    8.1915   12.4571    7.7511   10.4415    9.7219    8.2872    11.299    5.4968   20.0973

Profit
  mean             -28.5414 -167.4806    -457.5   22.3821   80.0434   -0.4593   25.6297    34.131  137.3143   -4.9351   37.9213  114.6165   51.9563  208.3365  146.5019  317.0927
  std. dev.         21.9268  100.7105   91.4754   12.0024    22.507    9.7454   10.3542   12.9154   33.6549    5.9995   18.2877   25.6577   16.0862   48.2476  232.5885   87.3812

Margin
  mean              30.0004   -24.522 -264.6667   37.0213  112.4575   43.4009   147.237   60.5388  174.6821   71.8541   73.2048  138.7306   90.4996  271.4841  172.3537  389.2549
  std. dev.         16.5178   83.2643   19.5377     8.445    7.9033     6.707   24.9968    5.4706   18.0773   11.0942    5.5933    8.7881    8.4679   33.2914  187.2426   67.1467

Time taken to build model (full training data): 305.71 seconds





Authors
•	Sandeep Modi - Initial work – 
Acknowledgments
•	I acknowledge that I did all the work! 
Thank you! 


