## process
### encode sex, district and smoker using one-hot done
#### effect
Encoded Data:
      sex_female  sex_male  smoker_no  smoker_yes  region_northeast  \
0            1.0       0.0        0.0         1.0               0.0   
1            0.0       1.0        1.0         0.0               0.0   
2            0.0       1.0        1.0         0.0               0.0   
3            0.0       1.0        1.0         0.0               0.0   
4            0.0       1.0        1.0         0.0               0.0   
...          ...       ...        ...         ...               ...   
1333         0.0       1.0        1.0         0.0               0.0   
1334         1.0       0.0        1.0         0.0               1.0   
1335         1.0       0.0        1.0         0.0               0.0   
1336         1.0       0.0        1.0         0.0               0.0   
1337         1.0       0.0        0.0         1.0               0.0   

      region_northwest  region_southeast  region_southwest  
0                  0.0               0.0               1.0  
1                  0.0               1.0               0.0  
2                  0.0               1.0               0.0  
3                  1.0               0.0               0.0  
4                  1.0               0.0               0.0  
...                ...               ...               ...  
1333               1.0               0.0               0.0  
1334               0.0               0.0               0.0  
1335               0.0               1.0               0.0  
1336               0.0               0.0               1.0  
1337               1.0               0.0               0.0  

## Breakthrough!
### by visualising the relation between data, the truth is about to come out
