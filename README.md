# Preparation

Um die elektrischen Eigenschaften vom Cr2O3 zu tunen, wurden drei elliptisch segmentierte Targets hergestellt:
- 0.01%-CuO in Ellipse
- 0.01%-ZnO in Ellipse
- 1%-ZnO in Ellipse

The position of the laser spot on the target was varied → this should yield different doping concentrations in the plasma (❓[[open questions#PLD]])

## Contacts

The samples were contacted with a stacking of Ti, Al and Au with thicknesses of 30nm each.
The resistivity was determined by the van-der-Pauw method for all c- and r-oriented samples and on selected samples of m- and a-orientation (because there were basically non-conductive at RT).
Hall effect mesaurements (→ $n$, $\mu$) were conducted for selected samples, yielding no information about charge carrier concentration or mobility due to low conductivity.

# Crystal growth

## growth rates

No significant dependence of growth rate on $y$ was observed. (*no image shown*).

A more significant influence comes from (i) energy absorption of the chamber window and (ii) degradation of the target surface due to repetition of processes. (`🖼️2-growthrate_vs_process`)
- for **0.01%-CuO**: the growthrate goes down after each process, but after cleaning the laser entrance window, it goes up again due to higher laser energy density;
- for **0.01%-ZnO**: the same is observed
- the "initial" growthrate with fresh window is ~6 pm/pulse. Note that 40k pulses are applied, so during growth, the window gets coated and so the growthrate goes down → 6 pm/pulse is kind of average over a 40k-pulses process (less pulses would yield higher growth rate, as seen for the pulse number variation series)
- for **1%-ZnO**: the window was cleaned after every process, but several other effects explain the observed changes in growthrate:
	- all but the first processes were done with 30k pulses; so for the first process with 40k pulses there is already during the process more coating of the window, s.t. the growthrate is lower for the whole process
	- the second process is done at $y$ equal to 6mm, whereas process 1, 3 and 4 are done at $y$ values equal to 3, 4, 2mm, resp. For smaller $y$ the total ablated target area is reduced → so target degradation due to laser pulsing influences the transfer coefficient (❓) in this regime 
	- this can also be understood by looking into process numbers 1, 5 and 6, which all were produced at $y$ equal to 3mm and with 40k, 30k and 30k pulses, resp. (note that the first process should have a higher growthrate when corrected from 40k pulses to 30k pulses). A clear decrease in growth rate is observed when not changing the Laser position on the target.
		- As can be seen in (`🖼️target_ZnO_1percent`), tracks are forming and thus the plasma dynamics will probably change (❗not systematically observed, e.g. no attention was payed on tilt of plasma plume) and thus reduce growth rate
- for **Temp. Series on 0.01%-ZnO**: several explanations convolute here:
	- no window cleaning for processes 1 to 3 influences reduction of growth rate
	- $y$ was always 6mm and so track carving took place (`🖼️target_ZnO_0.01percent`), thus reducing the growth rate as also observed for the 1%-ZnO-doped target
	- finally, the growth temperature was continuously reduced, thus (probably) also influencing film growth

As a conclusion, for repoducible growth rates one should
1. clean the laser entrance window highly frequently because Cr2O3 absorbs much laser energy,
2. care when producing thick films in single processes because the window gets also more coated,
3. change the ablation position on the target uniformly or (in the use-case of radially segmented targets) frequently renew the target surface by grinding.

## Structure

### targets

- for **1%-ZnO**-target
	- almost no reflexes for *r*-orientation; (02.4)-reflection is only observed for 1 out of 6 samples
	- it is not showed in the out-of-plane lattice overview

(`🖼️2-lattice_vs_growthrate`)

First consider the *m*- and *a*-oriented samples:
- for every target, increasing growth rate leads to a higher deviation of the lattice constants from bulk values
- The CuO-target exhibits the smallest slope, whereas the other targets show stronger dependence on growth rate
- note that for the 1%-ZnO-doped target, the repeated processes (laser spot position not varying radially (→ target degradation)) differ in growth rate and cover the whole lattice constant range; other process parameters stayed constant

For *r*-oriented samples:
- only the 0.01%-doped targets are investigated, because for the 1%-ZnO-doped target, the *r*-oriented samples were almost amorphous (`🖼️2-amorphous_r`)
- the dependence of lattice constant on growth rate is less pronounced compared to *m*- and *a*-oriented samples.
- overall, the lattice constants are here less deviating from bulk value

For *c*-oriented samples:
- the prior trend is not observed
- one could even argue for a reversed trend, where higher growth rates yield less deviation from bulk value

### temp var
(`🖼️2-tempVar_xrd`)

As mentioned above, different processes influence the growth of the thin films from the temperature series.
- no reliable statements can be made about tempertature dependence

There is no clear trend observable for the lattice constants.
- the lattice constants also do not correlate clearly with the crystallinity

The crystallinity increases (decreases) for higher temperatures for *c*-orientation (*r*-orientation)


# Room-temp. resisitivity
## targets
process properties:
- $y$
- order
- growth rate
- growth temperature

internal properties:
- thickness
- omega-FWHM
- lattice constants
### y-dependence

Because we wanted to vary $y$ to achieve different dopant incorporations to observe different effects on electric properties, we can look into $\rho$ vs. $y$ (`🖼️2-rho_vs_composition-dependence`)
- for each of the 3 targets, $y$ does not seem to influence $\rho$ systematically (no intra-target effect)
- for *r*-oriented samples, there seems to be less spread of the obtained values → some physical property must be more constant for *r*-orientation
- for $y$ equal to 3 for 1%-ZnO-doped samples: same $y$-value yields $\rho$ of 1 order of magnitude difference 

To get insight into the processes determining the resistivity, consider other effects:

### d-dependence
(`🖼️2-rho_vs_thickness-dependence`)
(`🖼️2-rho_vs_growthrate-dependence`)

For c-oriented samples, there seems to be an increase in conductivity with *higher thicknesses* for the 0.01%-doped targets. For r-orientation, however, this trend is less pronounced – if existent at all. The behavior is also visible when looking into the growth-rates.

> [!question] outlier?
For the 1%-doped target (when ignoring the outlier of high meas. uncertainity), the trend is interrupted by 2 outliers of thickness of 150nm. Interestingly these outliers align, even though they were fabricated at different $y$-values. (the same observation is done for the growth rates). So one can not argue these are real outliers, leaving the question why the $\rho$ vs. $d$ dependence is not observed here.

For the temperature series of the 0.01%-ZnO-doped target, higher thicknesses also yield lower resistivities. But note that this effect may overlap with the change in growth temperature, so in general one can not conclude whether temperature or thickness or growth rate is the determining factor. However, the observation that for the other targets, thickness / growthrate was crucial, suggests a similar behavior here.

### order dependence
(`🖼️2-rho_vs_order-dependence`)

Because the non-controlled effects of sample prepatation were (i) insufficient window cleaning and (ii) target track carving, (both influencing the growth rate) checking the dependence of $\rho$ on manufacturing order gives the same insight as looking into thickness dependence.

In fact, for the 0.01%-CuO doped target, the "jumps" in resistivity correspond to the same "jumps" in growthrate after window cleaning.
Here it is also visible how this effect is less pronounced for *r*-oriented samples.

For the 1%-ZnO-doped target, no further reaching conclusion can be drawn, because the changes in $\rho$ correspond to the changes in growth rate for this batch.

### lattice
(`🖼️2-rho_vs_lattice-dependence`)

We observed a dependence of $\rho$ on $d$ and because we observe a relation between thickness and out-of-plane lattice constants, it seems reasonable to look into $\rho$ vs. *a* and *c* for r- and c-oriented samples, resp.
The o-o-p lattice constant is determined by the peak-position in 2\theta-\omega-scans. For *r*-oriented samples, one measures the *r*-plane distance, which can be converted into *a* by assuming the bulk (literature) ratio of *a* to *c*.

For *c*-oriented samples, there is no dependence on the $c$-constant observable.
- note that for *c*-oriented samples, there was also no correlation between $d$ and $c$ observable (🖼️`2-lattice_vs_d`❓)

For *r*-oriented samples, there also seems to be no dependence of $\rho$ on $a$.

### omega
(`🖼️2-rho_vs_omega-dependence`)

**For *c*-oriented samples, one can observe better conductivity for less crystalline samples.**
- this result is even better than the thickness dependence because the two repeated processes now fit into the trenf (for *d*-dependence they were outliers)

For *r*-oriented samples, this trend is not observed; for the temperature-series of 0.01%-ZnO-doped it even seems to be inverse.

## contact var
(`🖼️2-contacts`)

- For *c*-oriented samples, three different contact types were tested with different growth temperatures: Titanium-aluminum-gold, Titanium-aluminum-gold annealed at 200 °C and Titanium-gold
- for *r*-oriented samples, two differnt contact types were testet with different growth temperatures: Ti-Al-Au and Ti-Au

For both orientations, contact types do not substantially influence the conductivity. For *r*-oriented samples, TiAlAu yields slightly better contacts (lower series resistance and lower error during measurement)

Note that the samples which were contacted with TiAlAu and TiAu were produced in the same process, respectively.


# Temperature dependent resistivity
(`🖼️2-TdH`)

For every target, there were T-dependent $\rho$-measurements done for *c*-oriented thin films
- the samples with lowest *y*-value were chosen → presumably most doping content
- they all exhibit an Arrhenius-like behavior: $\log(\rho) \sim \exp(E/kT)$ with some activation energy $E$.
- neglect the vertical offset, which stems from the choice of samples
- there seem to be two linear regimes (above 100K and below 100K) in Arrhenius-plot
	- this means that there is a dependence:
	- $\rho\sim r_1e^{E_1/kT}+r_2e^{E_2/kT}$ ^[if E_1 is larger than E_2, then the second exp-term is larger for certain temperature, but if r_2 is smaller than r_1, then there is a regime where the whole second part of the sum is larger, and a regime where the first part is larger → this gives this kink in the log(rho) vs. 1/T plot (Arrhenius)]

(`🖼️2-TdH_activation`)
Fitting those curves yields:
- for pure/1%-ZnO/0.01%-ZnO:
	- ~30meV activation energy for the *low temperature* regimes
	- 50-60meV for the *high temperature* regime
- for the CuO-doped target:
	- 50meV activation energy for the *low temperature* regime
	- 80 meV for the *high temperature* regime

> [!question] data question
> To really compare the samples, I should pick some samples with identicla $\rho$ at room temperature and then measure temperature-dependent (?)
