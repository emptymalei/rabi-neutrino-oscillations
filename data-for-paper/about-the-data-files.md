## About the Data Files

### Structure of this folder

```
data-for-paper
├── about-the-data-files.md
├── castle-wall
│   ├── probAkhmedovRabiTheoryList-0.4.csv                                 # Rabi formula
│   └── solAkhList-0.4.csv                                                 # Theory
├── interference
│   ├── paper-interference-a1-a2-0.0001-0.01-k1-k2-1.-0.1.csv              # Numerical: A_1=1e-4,A_2=1e-2, k_1=1, k_2=0.1
│   ├── paper-interference-a1-a2-0.0001-0.01-k1-k2-1.-10..csv              # Numerical: A_1=1e-4,A_2=1e-2, k_1=1, k_2=10
│   ├── paper-interference-a1-a2-0.0001-0.05-k1-k2-1.-10..csv              # Numerical: A_1=1e-4,A_2=5*1e-2, k_1=1, k_2=10
│   ├── paper-interference-theory-a1-a2-0.0001-0.01-k1-k2-1.-0.1.csv       # Rabi formula: A_1=1e-4,A_2=1e-2, k_1=1, k_2=0.1
│   ├── paper-interference-theory-a1-a2-0.0001-0.01-k1-k2-1.-10..csv       # Rabi formula: A_1=1e-4,A_2=1e-2, k_1=1, k_2=10
│   └── paper-interference-theory-a1-a2-0.0001-0.05-k1-k2-1.-10..csv       # Rabi formula: A_1=1e-4,A_2=5*1e-2, k_1=1, k_2=10
└── single-frequency
    ├── paper-single-frequency-simple-a1-0.0001-k1-0.9999.csv              # Numerical: A_1=1e-4, k_1=1-1e-4
    ├── paper-single-frequency-simple-a1-0.0001-k1-0.99998.csv             # Numerical: A_1=1e-4, k_1=1-2*1e-5
    ├── paper-single-frequency-simple-a1-0.0001-k1-1.csv                   # Numerical: A_1=1e-4, k_1=1
    ├── paper-single-frequency-simple-theory-prob-a1-0.0001-k1-0.9999.csv  # Rabi formula: A_1=1e-4, k_1=1-1e-4
    ├── paper-single-frequency-simple-theory-prob-a1-0.0001-k1-0.99998.csv # Rabi formula: A_1=1e-4, k_1=1-2*1e-5
    └── paper-single-frequency-simple-theory-prob-a1-0.0001-k1-1.csv       # Rabi formula: A_1=1e-4, k_1=1
```


All the data files contain two columns, the first of which is the coordinate for the horizontal axis for whatever that means, the second of which is the coordinate for the vertical axis. It would be easier to use the data if we transpose the data after loading them.