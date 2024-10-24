## Sept. 2 - Sept. 8
### "A precise measurement of the supermassive black hole mass in the galaxy NGC 383 using molecular gas kinematics down to the circumnuclear disc" 
by **Hengyue Zhang** **from WISDON/U of Oxford** in 9.5
- WHy care SMBH
    - M_BH-$\sigma$
    - M_BH-M_bulge
    - M_BH-M_*
- Weighing SMBH
    - Stellar kinematics
    - Megamaser kinematics
    - Molecular gas kinematics
- $\left(\frac{V_c}{\sigma_e}\right)^2\approx\left(\frac{R}{R_{SOI}}\right)^{-1}$
$\left(\frac{V_c}{c}\right)^2\approx\frac{1}{2}\left(\frac{R}{R_{Schw}}\right)^{-1}$

- Method: ALMA CO(2-1) emission line
    -FWHM: angular resolution of 0.050′′ × 0.024′′ (≈ 16 pc × 8 pc)
- Dynamical forward modeling
    - Stellar light
    - +M/L
    - +BH
    ==> mass profile
    ==> circular velocity curve
    - +gas distribution
    - +PA, inc
    ==> MCMC minimization $\chi^2$ ($\log(M_{BH}/M_\odot)$, $\sigma_{gas}$, PA, inc, $M/L_i$, $M/L_o$)

## Sept. 9 - Sept. 15
### "Tensions on small scales: Too many galaxy-galaxy strong lenses in galaxy clusters?" 
by **Massimo Meneghetti from the National Institute of Astrophysics Italy (INAF)** in 9.12

- In CDM paradigm: many small structures
    - missing satellite, too-big-too-fail, cusp-core problems
- Strong lensing mass modeling
    - galaxy-scale halos $\rho_{subhalo}(r) = \frac{\rho_0}{(1+r^2/r_{core}^2)(1+r^2/r_{cut}^2)}$
    - Determine Redshift: MUSE integral field spectrograph or VIMOS at VLT
- galaxy-galaxy strong lensing in galaxy clusters
    - GGSL: cluster galaxies lensing other galaxies in the cluster background
- simulation
    - gas radiative cooling
    - star formation
    - supernavae explosions, AGB stars, ...
    - metal enrichment
    - mass accretion onto central BHs
    - energy feedback from AGN
    ==> galaxy formation model (sub-grid)
- reconstruction
    - multi ray traceing
    - rusults
        - low GGSL probability in silumation：too few GGSL events are expected from LCDM
        - inconsistency in compactness and radial distribution: rotational vilocity is low in simulation, observation galaxies are more compact
- Feedback
    - low efficient feedback - surpress star formation - more compact - large GGSL prob.
    - but still unable to make galaxies compact enough


## Sept. 16 - Sept. 22


## Sept. 23 - Sept. 29
### "Lyman-alpha Intensity Mapping with optical imaging surveys: Future prospects"
by **Dr. Pablo Renard** from **Tsinghua** in Sept. 25
    - LSS statistics (2 points correlation fuction)
    - Lya forest: as light bluer than lya is redshift -- absorbed by HI IGM
    - PAUS-eBOSS/DESI

## Sept. 7 - Oct. 13
### "Investigating the link between the growth of supermassive black holes and their host galaxies with X-ray survays"
by **Qingling Ni from MPH** in 10.11
- coevolution (or not) of black holes and galaxies
    - M_BH - M_bulge
    - SFR - z
- methodology
    - utilizing X-ray survey fields with extensive multiwavelength data
- "universal" relation between BH growth and M_stellar or SFR
    - BH growth - host-galaxy compactness
        - motivation: BG "monsters": Too high M_BH, don't follow the M_BH - M_bulge relation
        - sample construction: star-forming galaxies sample (COSMOS )
            - z<0.8, logM_stellar>10.2
            - ~6000 SF galaxies, 200 X-ray detections
            - Sigma_1 corelates with M_stellar
        - relation between BH growth and sigma_1 is significant compared to M_stellar or SFR  
            - BHAR : long time BH growth 
            - BHAR - sigma_1: tight correlation
        - relation between BH growth and central gas density
            - 
        - sigma_1 tightly correalted with influence radius $\sigma_{inf}$
    - AFN with different stellar population ages
        - D_{n}4000 indicator for stellar ages of galaxies
            - Young galaxy - low D_{n}4000; old galaxy - high D_{n}4000
        - sample construction: galaxies/AGNs with optical spectroscopic and X-ray coverage 
            - 4XMM
            - 22600 galaxies, 90 log Lx/M_stellar >32
        - BH growth/AGN fraction anti-correlate with Dn4000
        - for low accretion rate AGN ,AGN fraction increases with Dn4000, which is inverse with high accretion rate counterparts

## Oct. 14 - Oct.20
### "Optimization of Tessellation-based Statistics: Void Statistics"
by **Yu Liu from THU** in 10.18
- BG
     - LSS : a highly non-Gaussian density field
     - Non-Gaussian Statistics
        - compared to 2PCF, can have higher-order infomation
    - initial condition reconstruction
        - such as BAO, primodial non-Gaussianities
    - Cosmological N-body simulation
        - need to deal with non-lineal problem
- Tessellation in Cosmology
    - basic concept from stochastic and computational geometry
        - AREPO
    - Two ways
        - Delaunay Tessellation
            - in 2D : circumsphere of triangle can't contain 4th point
            - in 3D: (reasonal extension)
        - Voronoi Tessellation
            - nearest to a point - belong to this point
- DT void statistics (Delaunay-based)
    - DT: Delaunay Triangulation
    - allowed to overlap
        - small DT void v.s. large DT void
        - resulting in an increase of tracer number
- New optimzed DT void method: subsampling 
    - small errorbar, larger void size
    - better performence in BAO
        - Alcock-Paczynski parameter is important 
        - CosmoGAME fitting model
            - CosmoGAME fitting model v.s. Galaxy De-wiggled Model
                - BAO position is the same
                - Bias is smaller(as expected)
            - more powerful than parabolic fitting
                - uncentainties is 20% smaller
                - also ~20% better than galay BAL measurements
- DT void statistics (Voronoi-based)
    - void don't overlap
- Discussion
    - Tessellation can 
        - reduce the uncertainties of DTFE Minkowski functions
        - reduce the uncertainties of Betti curves
        - reduce the artifacts in DTFE fields

### "Gravitational Lensing in the Kerr Spacetime: An Analytic Approach for Light and High-Frequency Gravitational Waves"
by **Torben Frost from PKU and KIAA** in 10.18
- Plebanski-Demianski metric
    - exact solution to Einstein's Eqn.
    - analytical methods
- GOALs: How can we detect effects of the spin using GL of light and high-f GWs?
- Kerr spacetime
    - Jacobi's Elliptic Functions
    - photon orbits 
- use celestial latitude and lognitude to distinguish different types of motion

## Oct. 21 - Oct.27
### "Map the 3D Universe - From the Past to the Future, Bridging Theories and Observations" 
by **Jiaxi Yu禹佳希** in 10.22
- the Universe v.s. Cosmology
    - Big bang Moment - Dark Era with the First light - Matter-dominated Era - $\Lambda$-dominated Era (the Era of Dark Energy)
- Cosmology
    - Begining of cosmology: 1915
        - General relativity 1915
        - Friedmann equations 1922
        - the expanding universe ~1930
    - The Dark Era of Cosmology: 1940-1970s
        - The first light: CMB
        - Debates on the law of the universe
        - the discovery of Dark Matter - the invisible mass
    - The matter-dominated Era: 1970-2000
        - The "first-galaxy" moment 1970s: little constrain of $\Omega_m$ ~ 0.01-1
        - Early Redshift Surveys 1980-1990s
            - Galaxy halo connection
        - The galaxy-dark matter relation 1970s
        - the standard cosmology?
            - the Einstein-de-sitter universe 1932: $\Omega_m$=1
            - a $\Lambda$-cold dark matter universe 1984: $\Omega_\Lambda$ >0, $\Omega_m$<0.5 
            - 1998:$\Lambda$CDM
                - galaxy&clusters :$\Omega_m$<0.5 
    - The $\Lambda$-dominated Era: 2000-2020
        - precise cosmolgy by CMB satellites: 1990 v.s. 2010s
        - many parameters well constrained within 1%
        - poorly constrained dark energy
            - How to constrain?
            1. BAO baryon Acoustic Oscillations
                - angular distance is different between Einstein-de-sitter and time-evolving dark energy 
                - standardised candle SNIa
                - has improved very much now
                - futural goals: higher redshifts, more precise, more infomation
            2. P(k) full-shape modelling
                - power spection
    - The cosmological pipeline
        - Who are observed: QSOs, galaxies
        - How th describe them: 2PCF, covariance matrices
        - what is the science: cosmo parameters
            - 2.3 sigma of varying of $\Lambda$ for 20 years

### "Bright Galaxies and Luminous Red Galaxies Target Selection" 
by **Aurelien Verdier** in 10.22
- Observatory
    - Visible and Infrared Survey Telescope for Astronomy (VISTA) in Chile
    - 4-metre Multi-Objuect Spectroscopic Telescope(4MOST)
    - VISTA for Photometric Survey
    - 4MOST for Spectroscopic Survey
- Type of Galaxies
    - Bright galaxies (BG)
        - bright: r<19
        - close: $0<z<0.5$
    - Luminous red galaxies (LRG)
        - $0.5<z<1.2$
    - Emission Line galaxies(ELG), QSO, Lyman-alpha forest, lyman-break galaxies(LBG), laman-alpha emitters(LAE)
- 4MOST can do multiple spectroscopic experiments
    - Cosmological Redshift Survey(CRS)
        - survey ID :S08
        - 4 experiments : BG, LRG, ELG, QSO
    - 100 experiments in total
- Photometric systematic
    - possible bias
        - weather
        - galacitic dust
        - stellar density
    - need to coreect the data
        - lineal regression
        - random forest
- Results
    - angular clustering
    - higher constrain on sigma_8 than DESI

### "Early dark energy in the light of large scale structure data" 
by **Rafaela Gsponer** in 10.22
- Motivation: Hubble Constant
    - Three steps to the Hubble Constant
        - Cepheids within the LMC
        - Galaxies hosting Cepheids and Type Ia supernovas
        - Distant galaxies in the expanding universe hosting Type Ia supernovas
    - Hubble tension
        - tension between indirect (CMB, ~67) and direct (type Ia, 73~) measurements
- Modifying the early universe
    - Toy model: Early Dark Energy (EDE)
        - want to decrease rs (CMB measure $\theta$, $\theta=r_s/D$ where D is distance from us), then will has larger H0
        - CMB v.s. EDE
            - using EDE, allow H0 is larger recently compared to early time, can explain hubble tension
    - Methods
        - Galaxy clustering
            - BAO: characteristic length of clustering (~150Mpc)
                - Alcock-Paczynski AP effect
            - Redshift Space Distortion
    - Modelling the full power spectrum
        - large scales: 
            - Perturbation theory
                - perfect fluid, no viscosity, no pressure
            - **EFTofLSS (Baumann2012, Carrasco 2012)**
                - introducing cut off scale $k_\Lambda$
        - small scales 
            - N-body simulations
                - computationally expensive, limited box size
- Results
    - Constraint on EDE
        - using Planck, BOSS, SHoES, Pantheon, ext.BAO, etc.
        - detection of non-zero EDE at the 5$\sigma$ level
        - more and more LSS data will leave pressure on EDE 
### "The impact of spectroscopic systematics on cosmological constrains" 
by **Shengyu He何盛宇** in 10.22
- Fitting apparoaches: 
    - direct fitting
        - Full-modelling and Calssical ShapeFit (SF) to correaltion function and power spectrum
    - compressed fitting
        - isolated BAO peak
        - RSD: f $\sigma_8$
- Cosmological inference
    - Bayesian statistics
    - $\chi^2$ statistics
    - MCMC sampling: MontePython, emcee
- Spectroscopic systematics
    - Redshift uncertainty: small inaccuratcies in measuring redshifts
    - Redshift catastrophics: significant difference in redshift measurement from true value

### "The influence of GC evolution on the specific frequency in dwarf galaxies" 
by **Elizabeth Moreno Hilario** in 10.23
- Introduction
    - Globular Clusters
        - dense self-gravitating systems
        - $10^6 M_\odot$
        - $10^4$ to $10^6$ stars
        - absent in the thin disc
        - memory of asembly history of galaxies
        - usually metal-poor
    - Specific frequency 
        - a number of clusters per unit galactic luminosity $S_N$
        - large both in dwarf and giant galaxies, but small in the middle
    - possible mechanisms
        - GC formation efficiency
        - star formation quenching 
        - GC disruption as a function of 
- Methodology
    - Dynamical evolution
        - Internal dynamics
            - 2-body relaxation
            - evaporation
            - stellar evoltuion
        - Galactic environment
            - cluster formation region shocks
            - galactic tidal field
    - Cosmological Simulations
    - Tidal Tensor
    - N-body Simulation with **nbody6++**
        - 24 simulations
        - different number of patricles
- Results
    - Different mass of GC has different mass loss
        - massive and dense GC has longer lifespan
        - dynamical mass loss after 1-2Gyr
    - Dissolution time
        - the less massive the host galaxy is, the less effective its GC disrupt
- Conclusion
    - the more massive the host galaxy is, the more effective its globular clusters disrupt
    - the fractions of mass that after 12 Gyr still belong to the GC systems in each swarf are larger for the less massive galaxies
