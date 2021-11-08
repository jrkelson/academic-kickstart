+++
date = "2020-06-01T00:00:00"
draft = false
tags = ["project", "methods", "triple oxygen isotopes"]
title = "Triple Oxygen Isotopes"
summary = "What are all those primes for anyway?"
math = true

[image]
image_preview = "featured.png"
preview_only = true


+++

<span style = "color:gray">
A dummie's guide to triple oxygen isotopes in carbonate.
</span>

Oxygen has one major isotope, <sup>16</sup>O, and two minor isotopes, <sup>17</sup>O and <sup>18</sup>O. A measurement of the abundance of <sup>18</sup>O is widely used in geochemistry ($\delta$<sup>18</sup>O) as a tracer for hydrologic processes.  It was long assumed that stuyding <sup>17</sup>O would not yield additional useful information because the fractionation would be about half that of <sup>18</sup>O, following a relationship that is predicted by mass-dependent (equilibrium) fractionation ($\theta$ = 0.529 for equilibrium fractionation, Luz and Barkan 2010):

{{< figure src="/img/TripleOprimer/path235.png" caption="Figure 1: Predicted relationship between $\delta$'<sup>18</sup>O and $\delta$'<sup>17</sup>O given equilibrium fractionation. $\theta$<sub>a-b</sub>  = ln(<sup>17/16</sup> $\alpha$<sub>a-b</sub>)/ln(<sup>18/16</sup> $\alpha$<sub>a-b</sub>), where $\alpha$<sub>a-b</sub> is the fractionation factor between two phases (like calcite-water). " width="300" >}}

Note that the axes of Figure 1 use “delta-prime” notation, a slight variation on the more familiar delta notation. This notation is used to remove the slight curvature in the relationship between $\delta$<sup>18</sup>O and $\delta$<sup>17</sup>O (Miller, 2002):

$\delta$’x = ln($\delta$x+1)       


$\delta$<sup>17</sup>O can deviate from this relationship if non-equilibrium fractionation occurs (i.e., $\theta$ ≠ 0.529).  Evaporation is an example of one such  fractionation process that carries $\theta$ = 0.5185 (Barkan and Luz, 2007). Yes, 0.5185 might seem about the same as .529, but with sufficiently high precision instruments this deviation can be measured. This deviation from the expected relationship between $\delta$'<sup>17</sup>O and $\delta$'<sup>18</sup>O is called ∆’<sup>17</sup>O, (analogous to the familiar d-excess), and is defined as:  

$\Delta$’<sup>17</sup>O = $\delta$'<sup>17</sup>O – $\lambda$ * $\delta$'<sup>18</sup>O

{{< figure src="/img/TripleOprimer/path236.png" caption="Figure 2: Schematic of $\Delta$'<sup>17</sup>O" width="300" >}}

Note that I've used $\lambda$ = 0.528, which is the empirically observed relationship in meteoric waters (Luz and Barkan 2010). The $\lambda$ notation expresses that it is an empirical relationship that may combine a number of different fractionations, as opposed to the $\theta$ used above that describes a single, well-defined fractionation (like the equilibrium fractionation, diffusion, or acid fractionation). ∆’<sup>17</sup>O is expressed in permille (with values that ranges from +0.10 to -0.2), or in per meg (with values that range from +100 to -200).

Thus, $\Delta$’<sup>17</sup>O can be used to identify evaporation of parent waters and carbonate minerals. Measuring $\Delta$’<sup>17</sup>O promises to be useful in terrestrial hydroclimate where d18O alone can be ambiguous.  Let’s consider the water bottle of Seattle tap water ($\delta$<sup>18</sup>O = -10 ‰) that I accidentally brought with me when I moved to in Michigan last fall.  If I let this water bottle sit with a lid off, it would evaporate and eventually reach a $\delta$<sup>18</sup>O= -6 ‰.  At that point, it would be impossible to distinguish my imported Seattle water from that of local Ann Arbor tap water using $\delta$<sup>18</sup>O analyses. $\Delta$’<sup>17</sup>O could be used to readily identify which water was evaporated; the Seattle water would have a $\Delta$’<sup>17</sup>O value that is about 0.10 ‰ lower than that of the Michigan water (evaporation experiments in Li et al., 2017). 

$\Delta$’<sup>17</sup>O has the potential to be useful in addition to the more familiar d-excess for two reasons. The first is the fractionation in oxygen isotopes is not very sensitive to temperature (i.e., Angert et al., 2004). The second is that carbonate minerals are widely preserved in the geologic record, where it is difficult to find co-occurring preservation of hydrogen and oxygen that would be necessary to calculate d-excess. Furthermore, the growth temperature can be directly measured from the same carbonate mineral (using clumps), allowing for a simultaneous estimate of environmental temperature and hydrologic processes. 

{{< figure src="/img/TripleOprimer/rect7101.png" caption="Figure 3: Schematic of $\Delta$'<sup>17</sup>O vs $\delta$'<sup>18</sup>O in waters" width="300" >}}

In studies of paleo-hydroclimate, we could use ∆’<sup>17</sup>O to parse out if changes in $\delta$<sup>18</sup>O were due to Rayleigh distillation (i.e., rainout over a mountain range) or due to evaporation. Other processes that cause kinetic fractionation could also be investigated (i.e., speleothems, as predicted in Guo and Zhou, 2019).  Note that ∆’<sup>17</sup>O should be independent of the starting $\delta$<sup>18</sup>O composition. It might even be possible to use the ∆’<sup>17</sup>O of carbonates to reconstruct the $\delta$<sup>18</sup>O of primary meteoric waters (i.e., lake carbonates in Passey and Ji, 2019).

Measuring ∆’<sup>17</sup>O in carbonate materials posed a technical challenge to isotope geochemists. Usually the isotopic composition of a carbonate mineral is determined by first digesting the CaCO<sub>3</sub> in phosphoric acid, then measuring the isotope abundances in the evolved CO<sub>2</sub> gas. However, <sup>13</sup>C-<sup>16</sup>O-<sup>16</sup>O interferes with the measurement of <sup>12</sup>C-<sup>17</sup>O-<sup>16</sup>O. So, CO<sub>2</sub> gas evolved from solid  CaCO<sub>3</sub> needs to be converted to O<sub>2</sub> for measurement. Passey et al. (2014) describe the acid digestion, reduction, and fluorination method which is currently in place at the University of Michigan.



