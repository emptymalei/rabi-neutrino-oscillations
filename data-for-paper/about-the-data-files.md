## About the Data Files

### Structure of this folder

```
.
├── about-the-data-files.md
├── interference
│   ├── paper-interference-a1-a2-0.0001-0.01-k1-k2-1.-0.1.csv
│   ├── paper-interference-a1-a2-0.0001-0.01-k1-k2-1.-10..csv
│   ├── paper-interference-a1-a2-0.0001-0.05-k1-k2-1.-0.1.csv
│   └── paper-interference-a1-a2-0.0001-0.05-k1-k2-1.-10..csv
├── interference-higher-order
│   ├── first2modes-a1-1e-4-k1-1-a2-0.032-k2-0.1.csv
│   ├── first2modes-a1-1e-4-k1-1-a2-0.1-k2-10.csv
│   ├── first3modes-a1-1e-4-k1-1-a2-0.032-k2-0.1.csv
│   ├── first3modes-a1-1e-4-k1-1-a2-0.1-k2-10.csv
│   ├── full-a1-1e-4-k1-1-a2-0.032-k2-0.1.csv
│   ├── full-a1-1e-4-k1-1-a2-0.1-k2-10.csv
│   ├── interference-data-12-07-09.zip
│   ├── rabi-one-a1-1e-4-k1-1-a2-0.032-k2-0.1.csv
│   ├── rabi-one-a1-1e-4-k1-1-a2-0.1-k2-10.csv
│   ├── theory2-a1-1e-4-k1-1-a2-0.032-k2-0.1.csv
│   ├── theory2-a1-1e-4-k1-1-a2-0.1-k2-10.csv
│   ├── theory3-a1-1e-4-k1-1-a2-0.032-k2-0.1.csv
│   └── theory3-a1-1e-4-k1-1-a2-0.1-k2-10.csv
├── plots-pub
│   ├── interference-reduction-slide-with-legend.pdf
│   ├── rabiOscillationsNeutrino-higher-orders-long-wavelength.pdf
│   ├── rabiOscillationsNeutrino-higher-orders-short-wavelength.pdf
│   └── rabiOscillationsNeutrinoCoincidence-single-frequency.pdf
├── plots-pub.py                                             
└── single-frequency
    ├── paper-single-frequency-simple-a1-0.0001-k1-0.9999.csv
    ├── paper-single-frequency-simple-a1-0.0001-k1-0.99998.csv
    ├── paper-single-frequency-simple-a1-0.0001-k1-0.99999.csv
    ├── paper-single-frequency-simple-a1-0.0001-k1-1.csv
    ├── paper-single-frequency-simple-theory-prob-a1-0.0001-k1-0.9999.csv
    ├── paper-single-frequency-simple-theory-prob-a1-0.0001-k1-0.99998.csv
    ├── paper-single-frequency-simple-theory-prob-a1-0.0001-k1-0.99999.csv
    └── paper-single-frequency-simple-theory-prob-a1-0.0001-k1-1.csv
```

All the data files contain two columns, the first of which is the coordinate for the horizontal axis for whatever that means, the second of which is the coordinate for the vertical axis. It would be easier to use the data if we transpose the data after loading them.



Run 

````term
ipython plots-pub.py
````

to reproduce the plots.