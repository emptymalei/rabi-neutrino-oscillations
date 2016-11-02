# Rabi

## TODO




## Structure of the repo:

The paper itself involves the following

```
├── main.tex  # The TeX file for the paper
├── assets    # The Figures for the paper
│   ├── akhmedovOscPlt.pdf
│   ├── castle-wall-1.pdf
│   ├── castle-wall-2.pdf
│   ├── castle-wall.pdf
│   ├── castlewall-profile.pdf
│   ├── interference-reduction-three-modes-neutrino.pdf
│   ├── interference-reduction-three-modes-rabi.pdf
│   ├── interference-reduction-three-modes.pdf
│   ├── interference-reduction.pdf
│   ├── interference.png
│   ├── legacy-rabiOscillationsNeutrinoCoincidence.pdf
│   ├── placeholder.jpg
│   ├── rabi-isospin-rotating-frame.ggb
│   ├── rabi-isospin-rotating-frame.pdf
│   ├── rabi-isospin-static-frame.ggb
│   ├── rabi-isospin-static-frame.pdf
│   ├── rabi-oscillations-energy-gap-change.eps
│   ├── rabi-oscillations-energy-gap-change.pdf
│   ├── rabiOscillationsNeutrinoCoincidence-single-frequency.pdf
│   └── resonance-freq-example-1-added-new-slow-perturbation-destruction-compare-rotating-field.png
└── ref.bib  # Reference
```

Other files are the supplementary materials

```
├── README.md
├── data
│   ├── plots.ipynb  # The code for the plots
│   ├── assets
│   │   └── writing-paper-rabi-neutrino
│   │       ├── akhmedovConditionDeviationPlt.png
│   │       ├── akhmedovOscPlt.png
│   │       └── castle-wall-matter-profile-0.8-0.88.png
│   ├── castle-wall
│   │   ├── probAkhmedovRabiTheoryList-0.003Pi.csv
│   │   ├── probAkhmedovRabiTheoryList-0.02.csv
│   │   ├── probAkhmedovRabiTheoryList-0.03Pi.csv
│   │   ├── probAkhmedovRabiTheoryList-0.04.csv
│   │   ├── probAkhmedovRabiTheoryList-0.08.csv
│   │   ├── probAkhmedovRabiTheoryList-0.1.csv
│   │   ├── probAkhmedovRabiTheoryList-0.2.csv
│   │   ├── probAkhmedovRabiTheoryList-0.4.csv
│   │   ├── probAkhmedovRabiTheoryList-0.5.csv
│   │   ├── probAkhmedovRabiTheoryList-0.6.csv
│   │   ├── probAkhmedovRabiTheoryList-0.8.csv
│   │   ├── probAkhmedovRabiTheoryList-1..csv
│   │   ├── probAkhmedovRabiTheoryList-3\ Pi.csv
│   │   ├── probAkhmedovRabiTheoryList-3.0649052682562883Pi.csv
│   │   ├── probAkhmedovRabiTheoryList-3.065Pi.csv
│   │   ├── probAkhmedovRabiTheoryList-3Pi-divied-by-2.csv
│   │   ├── probAkhmedovRabiTheoryList-3Pi.csv
│   │   ├── probAkhmedovRabiTheoryList-4Pi.csv
│   │   ├── probAkhmedovRabiTheoryList-Pi-divied-by-250.csv
│   │   ├── solAkhList-0.003Pi.csv
│   │   ├── solAkhList-0.02.csv
│   │   ├── solAkhList-0.03Pi.csv
│   │   ├── solAkhList-0.04.csv
│   │   ├── solAkhList-0.08.csv
│   │   ├── solAkhList-0.1.csv
│   │   ├── solAkhList-0.2.csv
│   │   ├── solAkhList-0.4.csv
│   │   ├── solAkhList-0.5.csv
│   │   ├── solAkhList-0.6.csv
│   │   ├── solAkhList-0.8.csv
│   │   ├── solAkhList-1..csv
│   │   ├── solAkhList-3\ Pi.csv
│   │   ├── solAkhList-3.0649052682562883Pi.csv
│   │   ├── solAkhList-3.065Pi.csv
│   │   ├── solAkhList-3Pi-divied-by-2.csv
│   │   ├── solAkhList-3Pi.csv
│   │   ├── solAkhList-4Pi.csv
│   │   └── solAkhList-Pi-divied-by-250.csv
│   ├── castle-wall-1.pdf
│   ├── castle-wall-2.pdf
│   ├── castle-wall.pdf
│   ├── castlewall-profile.pdf
│   ├── data
│   ├── interference
│   │   ├── interference-three-modes-interferencePyGridLines.csv
│   │   ├── interference-three-modes-interferencePyUpperFrameTicks.csv
│   │   ├── interference1-three-modes-k1-1-k2-0.1-a1-0.0001-a2-0.01.csv
│   │   ├── interference1-three-modes-k1-1-k2-1oPi-a1-0.0001-a2-0.01.csv
│   │   ├── interference1-three-modes-ks1-1-k2-1oPi-a1-0.000035-a2-0.0083666.csv
│   │   ├── interference1-three-modes-ks1-1-k2-1oPi-a1-0.0001-a2-0.01.csv
│   │   ├── interference1-three-modes-ks1-1-k2-1oPi-a1-0.0001-a2-0.0141421.csv
│   │   ├── interference2-three-modes-k1-1-k2-0.0001-a1-0.0001-a2-0.01.csv
│   │   ├── interference2-three-modes-k1-1-k2-1o10000Pi-a1-0.000035-a2-0.0083666.csv
│   │   ├── interference2-three-modes-k1-1-k2-1o10000Pi-a1-0.0001-a2-0.0141421.csv
│   │   ├── interference2-three-modes-k1-1-k2-1o1000Pi-a1-0.0001-a2-0.01.csv
│   │   ├── interference2-three-modes-k1-1-k2-1o1000Pi-a1-0.0001-a2-0.0141421.csv
│   │   ├── interference3-three-modes-k1-1-k2-0.0001-k3-1o1000Pi-a1-0.0001-a2-0.01-a3-0.01.csv
│   │   ├── interference3-three-modes-k1-1-k2-1o10000Pi-k3-1o5432-a1-0.000035-a2-0.0083666-a3-0.0083666.csv
│   │   ├── interference3-three-modes-k1-1-k2-1o10000Pi-k3-1o5432-a1-0.0001-a2-0.0141421-a3-0.0141421.csv
│   │   ├── interference3-three-modes-k1-1-k2-1o1000Pi-k3-1o543-a1-0.0001-a2-0.01-a3-0.01.csv
│   │   ├── interference3-three-modes-k1-1-k2-1o1000Pi-k3-1o543-a1-0.0001-a2-0.0141421-a3-0.0141421.csv
│   │   ├── interference3-three-modes-k1-1-k2-1o1000Pi-k3-1o543-a1-0.0001-a2-0.0141421-a3-0.0141421qvalues-data-list-each-modes.csv
│   │   ├── paper-interference-a1-a2-0.0001-0.01-k1-k2-1.-0.1.csv
│   │   ├── paper-interference-a1-a2-0.0001-0.01-k1-k2-1.-10..csv
│   │   ├── paper-interference-a1-a2-0.0001-0.05-k1-k2-1.-0.1.csv
│   │   ├── paper-interference-a1-a2-0.0001-0.05-k1-k2-1.-10..csv
│   │   ├── paper-interference-theory-amplitude-2016-10-18.csv
│   │   ├── rabi-interference-three-modes-interferencePyGridLines.csv
│   │   ├── rabi-interference-three-modes-interferencePyGridLinesZeros.csv
│   │   ├── rabi-interference1-three-modes-k1-1-a1-0.0001.csv
│   │   ├── rabi-interference1-three-modes-k1-1-k2-1oPi-a1-0.0001-a2-0.0141421.csv
│   │   ├── rabi-interference1-three-modes-k1-1-k2-1oPi-a1-0.0001-a2-0.05.csv
│   │   ├── rabi-interference1-three-modes-k1-1-k2-1oPi-a1-0.0001-a2-0.141421.csv
│   │   ├── rabi-interference2-three-modes-k1-1-k2-1o1000Pi-a1-0.0001-a2-0.0141421.csv
│   │   ├── rabi-interference2-three-modes-k1-1-k2-1o1000Pi-a1-0.0001-a2-0.05.csv
│   │   ├── rabi-interference2-three-modes-k1-1-k2-1o1000Pi-a1-0.0001-a2-0.141421.csv
│   │   ├── rabi-interference3-three-modes-k1-1-k2-1o1000Pi-k3-1o543-a1-0.0001-a2-0.0141421-a3-0.0141421.csv
│   │   ├── rabi-interference3-three-modes-k1-1-k2-1o1000Pi-k3-1o543-a1-0.0001-a2-0.05-a3-0.05.csv
│   │   ├── rabi-interference3-three-modes-k1-1-k2-1o1000Pi-k3-1o543-a1-0.0001-a2-0.141421-a3-0.141421.csv
│   │   ├── sol10List-a1-0.000035-k1-1.csv
│   │   ├── sol11List-a1-a2-0.000035-0.01-k1-k2-1-0.01.csv
│   │   ├── sol12List-a1-a2-0.00001-0.000141421-k1-k2-1-0.01.csv
│   │   ├── sol12List-a1-a2-0.000035-0.000264575-k1-k2-1-0.01.csv
│   │   ├── sol12List-a1-a2-0.000035-0.00035-k1-k2-1-0.01.csv
│   │   ├── sol12List-a1-a2-0.000035-0.02-k1-k2-1-0.01.csv
│   │   ├── sol12List-a1-a2-0.0001-0.000447214-k1-k2-1-0.01.csv
│   │   ├── sol14List-a1-a2-0.00001-0.00774597-k1-k2-1-0.01.csv
│   │   ├── sol14List-a1-a2-0.000035-0.0144914-k1-k2-1-0.01.csv
│   │   ├── sol14List-a1-a2-0.000035-0.015-k1-k2-1-0.01.csv
│   │   ├── sol14List-a1-a2-0.0001-0.0244949-k1-k2-1-0.01.csv
│   │   ├── sol15List-a2-0.00447214-k2-0.01.csv
│   │   ├── sol15List-a2-0.0083666-k2-0.01.csv
│   │   ├── sol15List-a2-0.0141421-k2-0.01.csv
│   │   ├── theory10List-a1-0.000035-k1-1.csv
│   │   ├── theory11List-a1-a2-0.000035-0.01-k1-k2-1-0.01.csv
│   │   ├── theory12List-a1-a2-0.00001-0.000141421-k1-k2-1-0.01.csv
│   │   ├── theory12List-a1-a2-0.000035-0.000264575-k1-k2-1-0.01.csv
│   │   ├── theory12List-a1-a2-0.000035-0.00035-k1-k2-1-0.01.csv
│   │   ├── theory12List-a1-a2-0.000035-0.02-k1-k2-1-0.01.csv
│   │   ├── theory12List-a1-a2-0.0001-0.000447214-k1-k2-1-0.01.csv
│   │   ├── theory14List-a1-a2-0.00001-0.00774597-k1-k2-1-0.01.csv
│   │   ├── theory14List-a1-a2-0.000035-0.0144914-k1-k2-1-0.01.csv
│   │   ├── theory14List-a1-a2-0.000035-0.015-k1-k2-1-0.01.csv
│   │   ├── theory14List-a1-a2-0.0001-0.0244949-k1-k2-1-0.01.csv
│   │   ├── theory15List-a2-0.00447214-k2-0.01.csv
│   │   ├── theory15List-a2-0.0083666-k2-0.01.csv
│   │   └── theory15List-a2-0.0141421-k2-0.01.csv
│   ├── interference-reduction-three-modes-neutrino.pdf
│   ├── interference-reduction-three-modes-rabi.pdf
│   ├── interference-reduction-three-modes.pdf
│   ├── interference-reduction.pdf
│   ├── interference.pdf
│   ├── rabiOscillationsNeutrinoCoincidence-single-frequency-1.pdf
│   ├── rabiOscillationsNeutrinoCoincidence-single-frequency.pdf
│   ├── single-frequency
│   │   ├── paper-single-frequency-simple-a1-0.0001-k1-0.9999.csv
│   │   ├── paper-single-frequency-simple-a1-0.0001-k1-0.99998.csv
│   │   ├── paper-single-frequency-simple-a1-0.0001-k1-0.99999.csv
│   │   ├── paper-single-frequency-simple-a1-0.0001-k1-1.csv
│   │   ├── paper-single-frequency-simple-theory-prob-a1-0.0001-k1-0.9999.csv
│   │   ├── paper-single-frequency-simple-theory-prob-a1-0.0001-k1-0.99998.csv
│   │   ├── paper-single-frequency-simple-theory-prob-a1-0.0001-k1-0.99999.csv
│   │   └── paper-single-frequency-simple-theory-prob-a1-0.0001-k1-1.csv
│   ├── sol10PList.csv
│   ├── theory10List.csv
│   └── writing-paper-rabi-neutrino.ipynb
├── outline.tex
├── rabi_neutrino_oscillations-0.10.1.pdf
├── rabi_neutrino_oscillations-0.10.1.zip
├── rabi_neutrino_oscillations-0.9.1.pdf
├── rabi_neutrino_oscillations-0.9.1.zip
├── rabi_neutrino_oscillations-0.9.2.pdf
├── rabi_neutrino_oscillations-0.9.2.zip
├── rabi_neutrino_oscillations-0.9.3.pdf
├── rabi_neutrino_oscillations-0.9.3.zip
├── rabi_neutrino_oscillations-0.9.4.pdf
├── rabi_neutrino_oscillations-0.9.4.zip
├── rabi_neutrino_oscillations-0.9.5.pdf
├── rabi_neutrino_oscillations-0.9.6.pdf
├── tikz-plot.tex
└── PITCHME.md   # Preserved for an elevator speech version of the work.
```


### Data

For 0.10.1 tag, the data used are all in the `data` folder.


Single frequency (Fig.1)

Theory

```
single-frequency/paper-single-frequency-simple-theory-prob-a1-0.0001-k1-0.9999.csv
single-frequency/paper-single-frequency-simple-theory-prob-a1-0.0001-k1-0.99998.csv
single-frequency/paper-single-frequency-simple-theory-prob-a1-0.0001-k1-1.csv
```

Numerical


```
single-frequency/paper-single-frequency-simple-a1-0.0001-k1-0.9999.csv
single-frequency/paper-single-frequency-simple-a1-0.0001-k1-0.99998.csv
single-frequency/paper-single-frequency-simple-a1-0.0001-k1-1.csv
```

Destruction effect (Fig.2)

```
interference/paper-interference-a1-a2-0.0001-0.01-k1-k2-1.-0.1.csv
interference/paper-interference-a1-a2-0.0001-0.01-k1-k2-1.-10..csv
interference/paper-interference-a1-a2-0.0001-0.05-k1-k2-1.-0.1.csv
interference/paper-interference-a1-a2-0.0001-0.05-k1-k2-1.-10..csv
interference/paper-interference-theory-amplitude-2016-10-18.csv # the data for the gridlines, which are the predictions of amplitudes using Rabi formula
```


Castle wall (Fig.4)

```
castle-wall/solAkhList-0.4.csv
castle-wall/probAkhmedovRabiTheoryList-0.4.csv
```


#### Using Data in Python

A transpose is used to counter the difference between python and Mathematica. For example,

```
theory1List = np.transpose( np.genfromtxt( 'single-frequency/paper-single-frequency-simple-theory-prob-a1-0.0001-k1-0.9999.csv', delimiter=",") )
```

So that we can simply plot out the list

```
plt.plot(theory1List[0][0::4],theory1List[1][0::4],'r-',\
         markersize=ftsz*0.4, linewidth=2, fillstyle='full',\
         markeredgecolor='red', markeredgewidth=0.0)
```

The full verions of the code is included in `plot.ipynb`.