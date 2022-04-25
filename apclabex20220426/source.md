[//]: # (Title of presentation)
class: middle
background-image: linear-gradient(rgba(0, 0, 0, 0.6), rgba(0, 0, 0, 0.75)), url( images/magnetar.jpg )

.boxtitle3.noborder.fgtransparent.pushfront[
# .fsize120[.blue[**Galactic population of high-mass X-ray binaries**]]
]

<hr>
<br>

## .center.blue[**LabEx meeting #28**]
### .center.bluelight[2022-04-26]



[//]: # (Introduction)
---
class: center, middle
background-image: linear-gradient(rgba(0, 0, 0, 0.6), rgba(0, 0, 0, 0.85)), url( images/magnetar.jpg )


[//]: # (.abs-layout.p-m.top-31.left-0.width-100.oc-bg-white.center.white[)
## .white[Idea]

<hr>

.rect.round-lg.border.line-2.width-93.dark.gray[

a) Study progenitor properties and expected parameters distributions
<br>
b) Compare them to observations of the entire population of HMXBs<br>
in the Galaxy (> 100 objects)
<br>
c) Use it to predict the evolution and prospects of GW detections
<br>
]



[//]: # (Methods. Overview)
---
class: top
background-image: url( images/binary-evolution-stages.svg )

.boxtitle3[
# **Binary evolution channel**
]



[//]: # (single vs binary: differences)
---
class: top
background-image: url( images/binary-evolution-first-stages.svg )

.boxtitle3[
## **Methods I: pop. synth.**
]

.abs-layout.p-m.top-20.right-25.width-30[

.card.gradient.indigo[

.center[
#### Initial binaries from initial functions of each binary parameter

Salpeter IMF, uniform mass-ratio, Sana period distribution

]
]

<br>

.card.gradient.indigo[

.center[
#### Evolve until first SN event

Using `COMPAS`, information at core-collapse is obtained

]
]

<br>
<br>
<br>

.card.gradient.indigo[

.center[
#### Interpolate binary configuration at core-collapse

Match properties just before with detailed simulations just after

]
]
]

.abs-layout.p-m.top-20.right-3.width-20[

<br>

.card.gradient.orange[

.center[
##### rotation not important during these stages thanks to very efficient angular momentum transport
]

]

<br>

.card.gradient.orange[

.center[
##### BH/NS prescriptions for masses and spin periods
]

]
]



[//]: # (single vs binary: differences)
---
class: top
background-image: url( images/binary-evolution-second-stages.svg )

.boxtitle3[
## **Methods II: detailed models**
]

.abs-layout.p-m.top-20.left-15.width-30[

.card.gradient.indigo[

.center[
#### Grid of binaries with `MESA`

Sample the space of masses, periods and eccentricities with "initially" non-rotating stars

]
]

<br>

.card.gradient.indigo[

.center[
#### Detailed mass-transfer evolution with stable/unstable cases

Using our prescription to start and evolve during a common-envelope phase

]
]

<br>
<br>
<br>

.card.gradient.indigo[

.center[
#### Weighting of parameters

Connecting initial conditions with this grid using an interpolation method, to estimate distributions of parameters

]
]
]
