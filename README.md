# Methylation Ordinal Forest model

## Input Data
Cleaned EWAS data in RDS format as follows:
     
                            cg02259047  cg17219656  cg26325880   cg01393939  ...          Age
        203219640023_R02C01  1.1270981  1.72554591  1.85541417  2.024850385  ... -3.456120317
        203751380069_R05C01  0.6536236  0.87276404  0.63364731  0.762567801  ... -0.036666328
        203219670151_R02C01  0.3353336  0.13273578  0.17724279 -4.626511028  ... -2.515312637
                ...             ...         ...         ...         ...      ...      ...
        203219730077_R03C01  0.8494915  1.63697624  1.08265519  1.913063000  ... -3.876467807
        203219750029_R06C01 -1.1927775 -0.44772475 -1.14141743  0.117283903  ...  0.146419954
        203219730215_R03C01  1.4234505  0.45588187  1.03046787 -0.657871295  ...  0.353748672
        203219730145_R01C01  1.2058798  1.25743310  0.73559757  0.665376128  ... -1.302085921

Input data dimensions must be 24 columns of CpG and 1 column of Age, each row represents sample, and there is not limit on amount of sample.


## Name of CpGs are: 
                    "cg17219656" "cg02259047" "cg26325880" "cg01393939" "cg21759874" "cg03544399"
                    "cg09595050" "cg19277182" "cg21655710" "cg26565580" "cg10129063" "cg24477583" 
                    "cg02979491" "cg11282100" "cg04403861" "cg09958418" "cg07341914" "cg02937343"
                    "cg01174708" "cg20064370" "cg14197071" "cg27366810" "cg13451733" "cg18592384" 

When missing CpG, using 0 instead as input data.
