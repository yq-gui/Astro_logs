# Note of talks about galaxy & cosmology
##### From special seminar/informal talk/galaxy&cosmology seminar/lunch talk/etc.

## 2024 September
### Sept. 2 - Sept. 8
#### "A precise measurement of the supermassive black hole mass in the galaxy NGC 383 using molecular gas kinematics down to the circumnuclear disc" 
by **Hengyue Zhang** from **WISDON/UOxford** in  **Informal Talk**, 9.5
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

### Sept. 9 - Sept. 15
#### "Tensions on small scales: Too many galaxy-galaxy strong lenses in galaxy clusters?" 
by **Massimo Meneghetti** from **the National Institute of Astrophysics Italy (INAF)** in **Informal Talk**, 9.12
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


### Sept. 16 - Sept. 22

### Sept. 23 - Sept. 29
#### "Lyman-alpha Intensity Mapping with optical imaging surveys: Future prospects"
by **Dr. Pablo Renard** from **Tsinghua** in **Galaxy and cosmology seminar**, Sept. 25 
    - LSS statistics (2 points correlation fuction)
    - Lya forest: as light bluer than lya is redshift -- absorbed by HI IGM
    - PAUS-eBOSS/DESI

## 2024 October
### Sept. 30 - Oct. 6

### Oct. 7 - Oct. 13
#### "Investigating the link between the growth of supermassive black holes and their host galaxies with X-ray survays"
by **Qingling Ni** from **MPH** in **Lunch Talk**, 10.11
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
            - BHAR-sigma_1: tight correlation
        - relation between BH growth and central gas density
        - $\Sigma_1$ tightly correlated with influence radius $\sigma_{inf}$
    - AFN with different stellar population ages
        - D_{n}4000 indicator for stellar ages of galaxies
            - Young galaxy - low D_{n}4000; old galaxy - high D_{n}4000
        - sample construction: galaxies/AGNs with optical spectroscopic and X-ray coverage 
            - 4XMM
            - 22600 galaxies, 90 log Lx/M_stellar >32
        - BH growth/AGN fraction anti-correlate with Dn4000
        - for low accretion rate AGN ,AGN fraction increases with Dn4000, which is inverse with high accretion rate counterparts

### Oct. 14 - Oct.20
#### "Optimization of Tessellation-based Statistics: Void Statistics"
by **Yu Liu 刘雨** from **DoA THU** in **Galaxy and cosmology seminar**, 10.18
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

#### "Gravitational Lensing in the Kerr Spacetime: An Analytic Approach for Light and High-Frequency Gravitational Waves"
by **Torben Frost** from **PKU/KIAA** in **Lunch Talk**, 10.18
- Plebanski-Demianski metric
    - exact solution to Einstein's Eqn.
    - analytical methods
- GOALs: How can we detect effects of the spin using GL of light and high-f GWs?
- Kerr spacetime
    - Jacobi's Elliptic Functions
    - photon orbits 
- use celestial latitude and lognitude to distinguish different types of motion

### Oct. 21 - Oct.27 
#### (EPFL visit)
##### "Map the 3D Universe - From the Past to the Future, Bridging Theories and Observations" 
by **Jiaxi Yu 禹佳希** in 10.22
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

##### "Bright Galaxies and Luminous Red Galaxies Target Selection" 
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

##### "Early dark energy in the light of large scale structure data" 
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

##### "The impact of spectroscopic systematics on cosmological constrains" 
by **Shengyu He 何盛宇** in 10.22
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

#### "The influence of GC evolution on the specific frequency in dwarf galaxies" 
by **Elizabeth Moreno Hilario** from **DoA THU** in **Galaxy and cosmology seminar**, 10.23
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

#### "Galaxy cluster studies in the era of high-resolution X-ray spectroscopy" 
by **Congyao Zhang** in **UChicaga** in **Lunch Talk**, 10.25
- Why X-ray?
    - X-ray : 0.1-10keV
    - ICM,IGM,CGM
- Why X-ray spectroscopy
    - Bremsstrahlung + collisional excitation
    - strong emission line
    - get temperature, metallicity, velocity, ...
- methodology
    - Microcalorimeter
        - XRISM
- result
    - spectrum -- bubble
        - The power needed to inflate the bubbles is mostly sufficeient to offset radiativeg cooling in the core
    - sloshing : oscillations in the stratified asmosphere
    - Feedback v.s. mergers
        - which process is dominated at differnt radii?
        - observe X-ray at different radii, measure velocity turbulence
        - result
            - inner part(<~50kpc): AGN feedback
            - outer part(>~50kpc): Mergers
    - science drivers
        - gas thermodynamics
        - metal abundance
            - how galaxies enrich ICM
            - alpha - Fe
        - multiphase gas in the outskirts
        - non-thermal pressure and cluster cosmology
        - motion drivers and injection scales
        - penetrating filaments and connection with the cosmic web

## 2024 November
### Oct. 28 - Nov.3
#### "Constraints on the tensor-to-scalar ratio r via a likelihood-based, optimal lensing reconstruction" 
by **Sebastian Belkner** from **University of Geneva** in **Galaxy and cosmology seminar**, 10.30
- CMB lensing
    - CMB observation:  PICO, CMB-S4, AliCPT-1
    - power spectrum: B mode and E mode
    - measure primordial B model
    - method
        - deflection field alpha
        - primordial CMB X^{unl}
- tensor-to-scalar ratio r
- maximum a-posteriori(MAP) lensing reconstruction

#### "Finding QPE-like systems in MOCCA simulation" 
by **Huojun Li** in **Peking University** in **Lunch Talk**, 11.1

Quasi Periodic Eruptions
- MOCCA: MOnte Carlo Cluster simulAtor
    - cluster simulation
    - features: multiple stellar population
- Possible models for QPE
    - GLs
    - Mass transfer in EMRI system
    - disk acceration
- Model: 
    - formation channels
        - How are these systems formed?:  Hills mechanism
    - orbital evolution
        - gravitational wave radiation & dynamic tides


### Nov. 4 - Nov.10
#### "Breeding seeds to grow SMBHs in the cosmological contexts" 
by **Yangyao Chen 陈洋遥** from **USTC** in **Galaxy and cosmology seminar**, 11.6
- motivation : galaxies at high z
    - clumpy star formation at high z
        - strong lensing using JWST
        - small size, resolved structure
    - z~7 quenched galaxy (JWST)
    - z~5 little red dot (JWST)
    - **joining the discrete pieces of information to form a complete picture**
- the first star and BH 
    - EPS extension
    - how to model 
        - $M_v, Z_{IGM}$($<10^{-4}Z_{\odot}$ for pop-III), $J_{LW}$(flux of lyman-Werner background), $\gamma=\frac{\dot{V_V}}{V_V H(z)}$(halo accretion rate)
- modeling IGM enrichment
    - model:star formation+ SN bubble expansion
        - $R_{Bubble} = (E/\rho)^{1/5}t^{2/5}$
    - meshed grids
    - metallicity of gas inflow
    - results
        - z~5, IGM metallicity > $10^{-4}Z_\odot$, pop-III stars formation ends
    - question: only IGM, no AGN?
- modeling Lyman-Werner background
    - contribution of LW radiation
        - cosmic background
        - summation over individual sources over the past lightcone
    - both LW radiation and dynamical heating 
    - J_{JW} ~ 1: transtion for cooling rate (10^3K to 10^4K)
- IMF and evolution of pop-III stars
    - IMF 
        - is top-heavy
            - reason: rapid inflow + frequent mergers
        - but not infinite mass. mass of the dominant star is regulated by
            - $\frac{\eta L_{edd}}{c} = \frac{GM^2}{R^2}$
        - the dominant Pop-III star evolves, dies ,and seeds the first BH in the galaxy
    - evolution
        -  mass of a BH seed - initial mass of Pop-II star
        - pair-instability supernova: massive star explodes, and 2nd most massive star becomes central BH
- How BH seed grows to SMBH
    - lessons from hydro:  
        - galaxy@highz are 
            - dynamically hot, turbulent motion, vertically thicken
            - only thick disk, no thin disk
    - dynamical hotness
        - distorts AM distribution
    - effect of fast assembly on BH accretion and feedback
        - super eddington inflow: turbulent accretion disk
    - Nuclear burst in the SN-freee nucleus
        - gas depltion <==> star foramtion + feedbacks+ BH accretion

#### "small-scale kinematical fluctuation" 
by **Zehao Zhong** from **NAOC** in **Lunch Talk**, 11.8
- BG
    - dynamical models
        - dynamics dominanted DM Halo, can use M_{dyn} - M_\ast to get DM only mass.
        - Spherical models (Virial Theorem), asisymmetrical models (JAM), triaxial models (Schwarzschild)
    - Inconsistency of model and obs
        - model: central symmetric
        - obs: small scall fluctuation
- Method
    - 180 degree self reduction
        - determine whether the galaxy is central symmetric
        - parameter $\eta$
    - obs. sample: SAMI survey DR3
        - more dwarf galaxies
    - simulation
        - TNG50 mock IFS survey (considering different distances, selection effects, PSF, measurement uncertanties)
- result
    - central asymmetry
        - observation
            - $\eta$ and $\Sigma_\ast$ has loglineal reverse relation
        - simulation
            - same trend with same slope

### Nov. 11 - Nov.17
#### 'Two bridges in galaxy ecosystem: "star - interstellar medium interaction" and "observation - theory/simulation connection"'
by **Tao Jing 荆韬** from **DoA THU** in **Galaxy and cosmology seminar**, 11.13
- galaxies as data points -> galaxy ecosystem
    - AGN, jets/winds, gas, star fomation, cooling, ISM, CGM
- Criss-cross nebula
    - data: highly spatial resolved 1000 au in MaNGA data
    - shork model + precursor-like region
    - psf and projection effect: bias the line ratio based temperature and density estimator
- gas rich quenched region
    - random forest : which determine quenching both for GPQR and GRQR

#### "Halo response to baryonic mechanisms at small scles"
by **Haonan Zheng** from **PKU&KIAA** in **Lunch talk**, 11.15
- BG
    - simulation
        - a tool to study the formation & evolution of DM halos and galaxies
        - EAGLE
        - Millennium: universal resolution: 10^8 M_\odot
        - APOSTLE: local group zoom-in, resolution: 10^6M_\odot
        - VVV: multi-zoom, resolution: 10^{-6}M_\odot
    - halo properties under baryonic impoacts
        - halo abuncance 
        - baryonic effect on matter distribution & star formation
    - dark mini-halos
    - VVV L3-pilot
        - dark matter(DM), non-radiative gas(NR), reionization & cooling(RI)
        - reionization : RI lose ~30% of mass and less concentrated

### Nov. 18 - Nov.24
#### "Halo response to baryonic mechanisms at small scles"
by **Niu Li** from **DoA THU** in **Galaxy and cosmology seminar**, 11.20
- BG
    - dust attenuation

#### "On the formation, evolution and the environment of low surface brightness galaxies in TNG100"
by **Luis Enrique Perez-Montano** from **ZJU** in **Informal Talk**, 11.21
- BG
    - LSBG
        - brightness mu > 22 mag/as
        - observation limit due to low brightness: z<0.1
        - important properties
            - angular momentum: 
            - spin parameter: $R\propto \lambda$, $\Sigma\propto \lambda^{-2}$
            - for LSBG, $\lambda >0.06$
        - Evironment
            - "relative" isolation
        - late-type morphology
    - Cosmological Simulation
        - sample: LSBGs in illustrisTNG
- Results
    - LSBG  .... than HSBG
        - is less massive and more extended 
        - has higher spin parameter and retention factors
        - has less massive SMBH with lower accretion rates
    - Evolution:
        - stellar mass history: no significant difference
        - z~2, spin, angular momentum and size become different
    - "giant" low surface brightness
        - giant: in term of HI distribution, $R_{HI} > 50 kpc$
        - 
    - Environment
        - halo concentration index
            - variation in size is due to variation in the spin parameter
        - LSBGs within groups
            - usually satellite
        - large-scale structure
            - central elliptical LSBG closer to nodes
            - spiral satellite lSBG away from nodes

#### "On the role of the structural bimodality of galaxy quenching in the local universe"
by **Bingxiao Xu** from **PKU/KIAA** in **Lunch Talk**, 11.22
- BG
    - galaxy quending and feedback
        - gas removal or SFE suppresion or starvation
        - external or internal
        - environment or starburst or BH or mass
    - predictors of quiescence of galaxies
        - most sensitive: $\Sigma_1$ and central velocity dispersion $\sigma_0$
    - quenching boundaries in different environment
        - low density : boundary has weak mass dependency
        - high density: boundary has strong mass dependency
        - strong redshift evolution for low density area
- RESULTS   
    - bimodality of SF galaxies of $\Sigma_1$ - $M_\ast$ plot
        - quenching boundary
    - QG all lies above the quenching boundary
        - quenching boundary of SF galaxyes are universal
    - questions:
        - why so many low-mass compact SF gals
        - why are compact (extended) gals so easy(difficult) to quench

### Nov. 25 - Nov.31
#### "Five parameters are all you need"
by **Paulo Montero-Camacho** from **Peng Cheng** in **Galaxy and cosmology seminar**, 11.27
- BG
    - universe can be explained by 6 parameters
        - baryons $\Omega_b$, matter $\Omega_m$, Hubble parameter $H_0$, amplitude of primordial power spectrum $A_s$, tilt of promordial power spectrum $N_s$, optical depth to reionization $\tau$
- Method
    - 21cmFAST
        - optical depth to reionization $\tau$
        - rescaling as function of cosmology
            - get $\alpha$&$\beta$ for each simulated $x_{\rm HI}$
    - symbolic regression
        - evolutionary algorithm
    - inference
        - data: PlanckDR3 + quasar dampling wings
        - methods: "age-dependent human mortality" reionization scenario
- Future Work
    - The Gompverse
        - robustness of universality
        - impact on evolving dark energy
        - revisiting mnu constrait
- summary
    - tanh is not good.. replace it with Gompertz

#### "Galaxy clusters as dark matter laboratories"
by **Benedikt Diemer** from **UMaryland** in **Informal Talk**, 11.29
- BG
    - Cosmological simulation
        - what is DM? What is gravity?
    - Density profile
        - scale radius
        - outer radius 
    - Initial peaks
        - log\rho - log r profile
        - fast accrection to low accrection (inside to outside)
    - cusp-core controversy
    - splashback radius
- results
    - observation of clusters -- density profile
        - r\rho(r) - r
        - dlog\rho/dlog r
        - boths shows splashback radius in simulation (different from NFW)
    - mass accretion rate matters
        - high MAR, steep radius profile
    - profiles depend on
        - accretion rate(dynamical), halo age(concentration), power spectrum slope(cosmology)
        - fitting: $\rho \propto \exp\left[-\frac{2}{\alpha}\left(\frac{r}{r_s}\right)^\alpha-\frac{1}{\beta}\left(\frac{r}{r_t}\right)^\beta\right]$ (better than NFW, Einasto ...)
    - observation:
        - survey: ACT, SDSS+Legacy Survey, DES, HSC, KiDs
    - DM Simulation
        - Pipeline
            - halos in DM-only simualtion
            - +forward model(baryonic effects)
                - WLs, satellite, BCG, SZ effect
            - +halo properties(mass, accretion rate, density profile)
        - are stellar halo connected to dark halos?

#### "The research of dark matter halo with galaxy-galaxy lensing method"
by **Weiwei Xu** from **NAOC** in **Lunch talk**, 11.29
- BG
    - DM and galaxy
    - Lensing
        - SL: easily visible distortion
        - WL: distortion much smaller
        - ML: no distortion, but brightness changes
    - weak lensing
        - convergence $\kappa$ + shear $\gamma$
        - galaxy-galaxy lensing: average density profile
- Data
    - shear measurement: SDSS, DECaLS, CSST
- results
    - c-M relation
        - c: concentration $c=r_{\rm vir}/r_s$
        - usually: r decrease with M
        - first detection of upturn tendency
    - R_SP vs. M $\nu$
        - Rsp propto M, nu, but no relation with z

## 2024 December
### Dec.2 - Dec.8

### Dec.9 - Dec.15
#### "Cosmological constraints from DESI Y1 Data"
by **Wenshuo Xu and Siyi Zhao** from **DoA THU** in **Galaxy and cosmology seminar**, 12.11
- DESI
    - dark energy spectroscopic instrument
    - spectroscopic: 5000 fibers
    - science goals
        - dark energy
        - gravity theory
        - neutrino mass
        - primordial non-gaussianty
- methodology
    - power spectrum
        - primordial non-gaussianity, BAO, RSD, neutrino mass
    - baryon acoustic oscillation
        - standard ruler
            - 2PCF: BAO peak
            - Power spectrum: BAO wiggles
        - 3D standard ruler
            - observables: $\alpha_{||}$,$\alpha_{\perp}$
        - BAO from galaxy and quasar clustering
            - template fitting
            - PS =  non-wiggle components + wiggles + residual
            - due to non-linear gravitational evolution
                - damping in 2PCF is different
        - BAO from Ly$\alpha$ forest
            - Neutral hydrogen
    - full-shape analysis
        - board-band power spectrum
        - observed redshift = hubble flow + peculiar velocity
        - anisotropic clustering
        - standard compression 
            - $\alpha_{||}$,$\alpha_{\perp}$: wiggles
            - $f\sigma_8$: amplitude
            - m,n : slope
        - shapefit
        - full-modeling
        - ==> non-linear power spectrum for observations
            - constrain compressed parameters: $\alpha_{||}$,$\alpha_{\perp}$,$f\sigma_8$,$m$,$n$
            - constrain cosmological parameters: $\Omega_m$,$H_0$,$A_s$,$n_s$
- cosmological constraints from DESI-Y1 data
    - BAO does not directly constrain $H_0$
        - $\Omega_m$ v.s. $H_0 r_d$
        - has redshift dependence
    - However, can use Full-shape analysis+BAO+BBN prior on $\Omega_b h^2$ + $n_{s10}$ to break the degeneracy
        - get $\Omega_m$,$H_0$,$\sigma_8$
        - $H_0$ & $\sigma_8$ tension
    - neutrino mass
        - affect
            - cosmic radiation history: CMB, BAO
            - structure growth
    - modified gravity
        - perturbed FRW metric
            - $\Phi$,$\Psi$
        - perturbed Eistein's eqution
            - $\mu$, $\Sigma$
    - primordial non-gaussianity (PNG)

#### "Dark Matter under the gravitational lens"
by **Jeremy Lim** from **HKU** in **Informal Talk**, 12.12
- BG
    - two pillars in modern physics
        - general relativity
        - standard model
    - candidates of DM
        - axions
        - WIMPs
        - ...
    - problems of cosmological simulation using WIMP
        - over-predict number of satellite galaxies
        - cusps-cores problem
    - cosmological simulation using ultra-light particles as dark matter
        - particles mass ~$10^{22}\rm eV$
        - same parge-scale structure
        - supression of low-mass halos
        - density perturbation (not smooth) due to wave coherence
        - flat density at center
- Lensing geometries
    - depending on
        - surface mass distribution of lens and its distance
        - actual position of source and its distance
    - cusp configurations
        - smoothly-varying density profile
            - R_{cusp} ~ 0
    - massive v.s. ultra-light DM
        - tangential critical curve between massive DM and ultra-light DM is very different
            - ultra-light: density modulation
- Lensing Anomalies
    - VLBI: different position and magnification of images compared to what massive DM model predicts
    - in simulation: ultra-light DM with different realisation

### Dec. 16 - Dec. 22