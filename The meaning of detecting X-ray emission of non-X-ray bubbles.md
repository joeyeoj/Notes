![[NGC4151.png]]
Observation
- counts-position angle distribution
- radial profile in a particular region
- the spectrum of the extended emission
Model
- Cloudy (to fit the real spectrum)
	- "The dimensionless ionization parameter (Osterbrock & Ferland 2006) is defined as U = Q/(4πr2cnH), where nH is the hydrogen number density, r is the distance to the inner face of a model slab, c is the speed of light, and Q = ∫∞ 13.6eV Lν/hν is the emitting rate of hydrogen ionizing photons (s−1) by the ionizing source."
	- To produce both the hydrogen-like and helium-like neon and oxygen line emissions, two components are needed, a high-ionization phase (log U = 0.8, log NH = 20.0) and a low-ionization phase (log U =−0.25, log NH = 19.4).
	- "Obtain a constraint on the possible presence of the hot ISM by invoking a collisionally ionized component in the best-fit photoionization model."
Theory
**Emission mechanism**
* Emission Line Gas Morphologies
	* "There is clearly an overall morphological coincidence with the ionized gas bicone traced by [O iii] emission, as noted in previous X-ray studies (e.g., Ogle et al. 2000; Yang et al. 2001)."
* [O iii]-to-soft X-Ray Ratio of the HST-resolved Clouds
	* "Bianchi et al. (2006) studied a sample of eight Seyfert 2 galaxies, and suggested that the same kiloparsec-scale gas photoionized by the AGN continuum can simultaneously produce the observed X-ray and [O iii] emission."
	* "If the [O iii] and X-ray emission arise from a single photoionized medium, as discussed in Bianchi et al. (2006), this further implies that the ionization parameter does not vary significantly to a large radial distance and the density is approximately decreasing as r−2, as expected for a freely expanding nuclear wind based on mass conservation (Crenshaw et al. 2000; Bianchi et al. 2006)."
	* ![[OIII_Xray.png]]
* Spectral Fitting
	* By analysing the components of spectral fits, it will show which component is the dorminant.
* Kinematics of the Ionized Gas
	* Kaiser et al. (2000)
	* The gas is photoionized by the nuclear radiation, which will correspond to that there is no strong kinematic shocks or any strong shocks in the outflow.
**The impact of AGN outflow on the host galaxy ISM**
* The mass-loss rate and the kinematic power of the hot phase outflow
	* ![[massloss_rate_and_kinematic_power.png]]
	* Adopting Lbol = ηMdot_accrc^2 and η = 0.1 for the efficiency of the accretion disk (Shakura & Sunyaev 1973), this implies that the central engine of NGC 4151 is accreting at  Mdot_accr = 0.013 M yr−1. 
		* "Since the measured outflow rate is 160 times the accretion rate necessary to feed the active nucleus, there must be either significant entrainment of the host galaxy’s ISM while the nuclear outflow is expanding, or part of the gas fueling the nucleus is ejected before radiating, or a high fraction (over 99%) of the X-ray gas does not take part in the outflow and is illuminated by the AGN “in situ.”
			* "the grating spectra strongly indicate that the emission lines have outflow velocities of 200–300 km s−1 (e.g., Armentrout et al. 2007)." excluding the latter hypothesis.
			* "previous estimated NLR outflow rates in Seyfert galaxies (∼0.1–10 M yr−1) generally exceed the accretion rate by tenfold (Veilleux et al. 2005)."
	* "Loutflow/Lbol is in rough agreement with a two-stage feedback model recently proposed by Hopkins & Elvis (2010), which requires only 0.5% of the radiated energy to drive the initial hot outflow to efficiently shut down star formation in the host."
**********************************************************
radio/CO/UV
What can X-ray do?
#### Model:
<font  color="red">Get kT</font>
==Greene, 2014==
"Spectra were extracted from the clump, bubble, northern nucleus, and total non-nuclear regions, along with a background spectrum from the 2′ background region. The unbinned spectra were fit in Sherpa (Freeman et al. 2001) using Cash (1979) statistics. The spectral model for the clump, bubble, and total extended regions was an absorbed (Wilms et al. 2000) thermal plasma model (APEC) at the redshift of the host galaxy. The confidence intervals for the parameters are determined using the task conf within Sherpa, taking into account the presence of several variables in the fit."
**Direct proof:**
Using model to fit temperature T
**Undirect proof:**
Calculate the unabsorbed fluxes from the best-fit models. "While we are fitting a low total number of counts, the fact that the photons are all at very low energies rules out both high temperatures and large absorbing columns."
<font  color="red">Get X-ray luminosity</font>
L=4$\pi$ r$^2$ Flux (r is the distance between galaxies and us, Flux is the <font  color="purple">unabsorbed</font> flux.)
#### Theory:
<font  color="red">Explain why soft X-ray excess</font>
**Electron scattering**
"Electron scattering of the AGN continuum could provide X-ray photons"
Features:
- "scattering would not change <font  color="purple">the hard spectral slope</font> intrinsic to the AGN, so cannot explain the very soft extended X-rays." My understanding is that, the distribution of hard and soft X-ray is determined. So what is the typical spectral slope? 
	- From (Shemmer, et al, 2006, ApJ),
		- ![[Hard_spectral_slope.png]]
	- From (Ishibashi, et al, 2010, A&A),
		- ![[Xray spectrum.png]]
	* From (Brcgman, 1990, A&A)
		* ![[Spectral_slope.png]]
- "<font  color="purple">the scattering efficiency</font> is too low to account for the observed luminosity."
	Known <font  color="red">infrared luminosity</font>
	$\downarrow$
	"Assume that the intrinsic UV luminosity is ∼twice that of the infrared bump"
	$\downarrow$
	Get <font  color="red">UV luminosity</font>: $vfv[2000Å]\sim10^{-5}cm\sim UV$
	$\downarrow$
	"Assuming that all UV emission is due to electron-scattered light from the nucleus places an upper limit on the electron-scattering efficiency of <font  color="red">3%</font> (much less so if there is a contribution from dust)."
	$\downarrow$
	"electron scattering is wavelength independent and dust scattering is negligible at X-ray wavelengths"
	$\downarrow$
	given <font  color="red">the luminosity of the north nucleus</font>
	$\downarrow$
	Calculate <font  color="red">an upper limit to the scattered X-ray luminosity</font>/<font  color="red">LX/L[O III]</font>
	$\downarrow$
	Compare with the observed X-ray luminosity(non-nucleus)
**Superwind**
- Theory: $L_{\rm bol}$-->$L_{\rm mech}$-->$L_{\rm X}$ (Based on the thermal gas temperature)
(Leitherer & Heckman, 1995, ApJS)
[https://articles.adsabs.harvard.edu/pdf/1995ApJS...96....9L](https://articles.adsabs.harvard.edu/pdf/1995ApJS...96....9L)
![[Lmech.png]]]
(Heckman, et. al, 1996, ApJ)
[https://articles.adsabs.harvard.edu/pdf/1996ApJ...457..616H](https://articles.adsabs.harvard.edu/pdf/1996ApJ...457..616H)
![[LxfromLmech.png]]
- Grimes et al. (2005), ApJ
$f_{\rm X}/f_{\rm FIR}\approx 10^{−4}$, $kT ≈ 600–800 eV$ (In starburst galaxies over a wide range in mass, including ULIRGs)
**********************************************************
## The scale of X-ray emission and the physics behind
#### 怎么判断X-ray emission也是泡泡的形态？
##### 非X-ray泡泡的形态是怎么判断的？
###### M82
![[M82_optical.png | Optical image by DSS.]]
==Weiß, et al, 1999, A&A:==
From the observation of $^{12}$CO, pointing out the position of the supernova remnant 41.9+58 (SNR 41.9+58), there are two bubble-like structures that are symmetrical about the SNR.
![[M82_12CO.png | The figure is from Shen & Lo, 1995, ApJ. The contour levels' unit is Jy beam$^{-1}$ km s$^{-1}$ (Jy: Jansky, the unit of flux density).]]
![[M82_pv.png | The slice is centred on SNR 41.9+58.]]
The pv-diagrams show that the left side of the center is receding from us because its velocity is much higher than the center. The right side is the opposite. One offset does not correspond to only one velocity, because there is thickness of CO in our sight (==method==, I think spectral lines are necessary).
From the morphology and the dynamic characteristic -- velocity, there are bubbles observed by CO molecular lines around SNR 41.9+58.
###### SDSS J135646.10+102609.0
![[SDSSJ135646.10+102609.0_optical.png | Optical image by PanSTARRS DR1 (from bands z and g).]]
##### X-ray
###### M82
==Weiß, et al, 1999, A&A:==
![[M82_Xray.png | Integrated 12CO(J = 1 → 0) line emission of M 82 (greyscale). The contour map represents the diffuse X–ray emission without the strongest point–source in the core of M 82 as observed by the ROSAT HRI. The three X-ray point–sources are marked with a star, the position of SNR 41.9+58 by a cross; the centre of M 82 (2.2 μm peak) is indicated by a filled box.]]
The center of M82 is different from SNR 41.9+58, (Weiß, et al, 1999, A&A) hold the view that the CO bubbles are generated from SNR 41.9+58, which means that the center of CO bubbles is SNR 41.9+58. From the above figure, we can see that the center of X-ray emission is also SNR 41.9+58.
1. X-ray emission is likely from a specific position, which is identical to the source of CO bubbles, SNR 41.9+58. --source
2. X-ray emission in the smaller scale has two bubble structures, which is almost symmetric to SNR 41.9+58. --morphology
3. ==Velocity seems does not have been detected. I think it is necessary.==
But from the initial figure (Bregman, et al, 1995, ApJ), I think the morphology is not clear to be bubbles.
![[M82_Xrayinitial.png | X-ray image by ROSAT HRI.]]
###### 突然感觉也不需要非要认定X-ray emission是泡泡的形态。。我只是研究泡泡在X-ray会有什么表现，由此可以得到什么东西
###### SDSS J135646.10+102609.0
![[SDSSJ135646.10+102609.0_Xray.png | X-ray image by Chandra 0.3-8 keV.]]
#### 怎么界定X-ray bubble的边界？
Now I hold the view that I just need to define the scale of X-ray emission.
From the observed X-ray image. Compare the X-ray intensity with the background. 
##### X-ray emission的尺度大于[O III]泡泡的尺度
###### 为什么X-ray emission的尺度会大于[O III]泡泡的尺度，可以用于解释的机制有哪些？
bpt diagram
###### 不同机制在观测量上会有什么区别？
##### X-ray emission的尺度与[O III]泡泡的尺度相当
##### X-ray emission的尺度小于[O III]泡泡的尺度
