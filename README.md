# DBPFSP Data and Results Repository

This repository contains the experimental data and computational results for the paper:

**"The Distributed Bilevel Permutation Flow Shop Scheduling Problem"**

Authors: Fuli Xiong, Chengfei Xiang

## 📁 Repository Structure

```
DBPFSP/
├── Data/
│   ├──DBPFSP _instances/           # Full test instance set (445 instances)
│   ├── small_sampled_instances/        #  (45 instances)
│   └── big_sampled_instances/        #  (27 instances)
│
└── Result/
    ├── SPs/                    
    │   ├── Subproblem1.csv
    │   └── Subproblem2.csv
    ├── Small/                    
    │   ├── LBBD1-BS-T.csv
    │   ├── LBBD1-BS-TM.csv
    │   ├── LBBD1-BS-M.csv
    │   ├── LBBD2-BS.csv
    │   ├── LBBD3-BS.csv
    │   ├── BCH1-BS.csv
    │   ├── BCH3-BS.csv
    │   ├── MIBS-small.csv
    │   └── Scebario.csv  # Scebario extend
    │
    ├── Large/                    
    │   ├── GA.csv
    │   ├── VNS.csv
    │   ├── PSO.csv
    │   ├──WOA.csv
    │   ├── SA-TS.csv
    │   ├── TabuSerach.csv
    │   ├── pointer.pt  #surrogate model。
    │   └──  parameter tuning
    │
    │
    └── Managerial Implications 
        ├──  DPFSP.csv   # Single-level baseline
        ├── Pareto_results
        └── Coordinate_results
      
```
