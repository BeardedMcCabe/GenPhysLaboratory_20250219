(triple-beam-balance-overall)=
# || Triple Beam Balance

Here is an overview of how to use a triple beam balance for 0.1 gram precision mass measurements.

## The Apparatus


The instrument illustrated in {numref}`triplebeambalance_Fig01` is a **triple beam balance** that can be used to determine the ***mass of an object***. The left-hand side has a platform where the object whose mass you seek to measure can be placed. The weights can slide along the balance beam scales to determine mass values, and there is a magnetic damper to bring the balance to rest more quickly. This works thanks to two knife-edges on bearings. One is the main pivot point from which the platform and sliding masses are calibrated. The second knife-edged point of contact is between the platform and the beam which allows the object in question to be *placed anywhere on the metal pan*, but have a constant distance from the main pivot point. 

```{figure} IntroductionFigures/tbb_001_v02.png
:name: triplebeambalance_Fig01
:width: auto
:align: center

Triple beam balance.
```

## Theory

The triple beam balance is a type of mechanical balance used to determine the **mass** of various objects that works on the principle that equal masses will be pulled downwards by gravity with equal force. Thus if two equal masses are suspended by a string around a pulley, they balance each other ({numref}`triplebeambalance_Fig06`-A). If the two masses are suspended from the opposite ends of a balance beam, we add another dimension, length ({numref}`triplebeambalance_Fig06`-B). This length is measured from the pivot point of the beam to where the masses are suspended. The downward pull (torque $\tau$, a force that tends to produce torsion or cause rotation around the pivot or axis of rotation) on each side is equal to $\tau = \text{mass} \times \text{gravity} \times \text{length}$. If the torque produced on each side is equal, the weights are balanced. If we increase the mass on one side, then to stay balanced, that same side would need to become shorter (see empty triple beam balance in {numref}`triplebeambalance_Fig06`-C). 

With the triple beam balance, as you add an object to the pan, we cannot change the length of the left-hand side of the beam. We can, however, slide the masses farther from the pivot point to increase the distance from the pivot, thus increasing the torque until it balances the torque of the object.



```{figure} IntroductionFigures/tbb_006_balance_v03.png
:name: triplebeambalance_Fig06
:width: auto
:align: center

Triple beam balance theory. A) Equal masses around a pulley have same downward force. B) Equal masses at equal length balanced by equal torques. C) Triple beam balance has a shorter side that must be made up for by larger mass to stay at balance. If additional mass is then added, sliding masses must move farther from the pivot point to balance torques.
```




(reading-the-triplebeambalance-scale-help)=
## Balance Beam Scales

The three balance beams allow for adjustable lengths of three different masses. The scale on each beam has been set so that the length of the mass, from the pivot point, will produce a specific torque that will counterbalance a specific mass on the opposite side platform. This allows the user to "read" the mass counterbalanced.

There are three measurement scales ({numref}`triplebeambalance_Fig03`), the $0-500\,\text{g}$ and $0-100\,\text{g}$ scales for coarse values, and the $0-10\,\text{g}$ scale for finer values with a precision down to $0.1\,\text{g}$.


```{figure} IntroductionFigures/tbb_003_scales_v03.png
:name: triplebeambalance_Fig03
:width: auto
:align: center

Mass scales on a triple beam balance.
```


(triple-beam-balance-preparation)=
## Preparing the Triple Beam Balance

Before taking measurements, the balance must be **zeroed** to ensure accurate readings. Over time and handling, the balance will eventually lose its calibration and no longer be at factory set balance or "zero." This zero point can be reestablished by using the "zero adjust" knob ({numref}`triplebeambalance_Fig02`-left). This knob is on a threaded rod which allows you to twist it outwards, increasing its length from the pivot point, or twist it inwards, shortening it. This very small shift in length will add or subtract torque from the left side of the balance. The "zero" point is read by the indicator attached to the end of the right-hand side of the balance arm ({numref}`triplebeambalance_Fig02`-right).

First, place the scale on a level surface, and make sure all the sliding masses are at their zero value:
  - coarse scales $(0-500\,\text{g}$ and $0-100\,\text{g})$: the sliding masses should be in their left-most notched position
  - fine scale $(0-10\,\text{g})$: the sliding mass should be lined up with the $0\,\text{g}$ line

Then, **zero the balance** by twisting in or out the "zero adjust" knob until the line on the beam is aligned to the indicator. Allow a few seconds for the beam to settle between adjustments.

```{figure} IntroductionFigures/tbb_002_zero_v02.png
:name: triplebeambalance_Fig02
:width: auto
:align: center

How to zero the triple beam balance with the zero adjustment knob.
```


## How to Read Triple Beam Balance

See {numref}`triplebeambalance_Fig04` for an example mass measurement of an object. The **precision** of the scale is $0.1\,\text{g}$, the smallest printed increment. It is possible to approximate the position between the smallest increments, however, this number is *estimate*, not an explicitly read value.

To measure:

1. Ensure the triple beam balance has been **zeroed** as decribed in {numref}`triple-beam-balance-preparation`
2. Place the object whose mass we want to determine on the metal pan. ***Notice*** the *zero-line* indicator on the beam is now higher than the zero line on the metal frame.
3. Slide each of the three scale masses right or left until both of the *zero-line* indicators are aligned.
4. Read and add together the mass values from each of the three beams (e.g. {numref}`triplebeambalance_Fig04`).
    - If the fine scale mass is between the $0.1\,\text{g}$ divisions, you can *estimate* the hundreths position, but be mindful that this is an estimate, not a direct reading.
5. Estimate uncertainty:
    - Any uncertainty in the mass measurement (usually noted throughout the manual as $\delta m)$ will generally be on the order of the smallest increment due to the precision of the equipment; for the triple beam balances used here, that would be $0.1\,\text{g}$.
    - However, if you are ***less*** *confident* in the mass reading (e.g. you can slide the smallest mass left and right more than $0.1\,\text{g}$ while still being convinced the *zero-line* indicators are aligned), then you can estimate the mass uncertainty to be larger than the precision of the instrument.

```{admonition} Zero Check
:class: warning
For successful use of the triple beam balance, periodically check the zeroing of the balance between trials.
```

```{figure} IntroductionFigures/tbb_004_example_v02.png
:name: triplebeambalance_Fig04
:width: auto
:align: center

Example mass value **as read** from scales of $387.9\,\text{g}$. The hundredths place is estimated, bringing it to an estimated $387.91\,\text{g}$.
```



## Web Simulation & Example

Use the following online resources to review and test yourself on whether you are reading the mass scales correctly.

### ● Ohaus Tutorial (Manufacturer)

[Triple Beam Balance Tutorial - OHAUS](https://us.ohaus.com/en-us/tutorials/triple-beam)

```{figure} IntroductionFigures/tbb_007_WebExample_v01.png
:name: triplebeambalance_Fig_WebExample01
:width: auto
:align: center

Simulation example: [Triple Beam Balance Tutorial - OHAUS](https://us.ohaus.com/en-us/tutorials/triple-beam).
```

### ● Video Tutorial

<div style="text-align: center;">
  <iframe
    width="80%"
    height="315"
    src="https://www.youtube.com/embed/BAf6HoVK6JI"
    title="YouTube video"
    frameborder="0"
    allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"
    referrerpolicy="strict-origin-when-cross-origin"
    allowfullscreen>
  </iframe>
  <figcaption>Triple beam balance demonstration video. *Yes audio*</figcaption>
</div>

If embedding is broken, follow: <a href="https://www.youtube.com/watch?v=BAf6HoVK6JI" target="_blank" rel="noopener noreferrer">
https://www.youtube.com/watch?v=BAf6HoVK6JI
</a>
