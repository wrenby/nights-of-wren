---
title: "IC 1805, The Heart Nebula"
description: "For Koi 🧡"
tags: ["deep-sky", "cassiopeia", "nebula", "diffuse-nebula", "emission nebula"]

date: 2023-02-14

equipment:
    camera: Atik 383L+ Mono
    filters: Baader Ha
    telescope: GSO 6" F/4
    mount: Celestron AVX
    guider: ZWO ASI120MM Mini

framing:
    ra: 02h32m39s
    dec: +61°22'52"
    rot: -88.20°
    width: 149.18'
    height: 119.42'
    pxscale: 1.63"/px

environment:
    location: Pittsburgh, PA
    bortle: 5
    moon: 63%

featured_image: "img/2023-02-14 ic1805 heart neb.png"
---

The Heart Nebula (also known as {{<def Sh2 />}}-190 or by its associated star cluster {{<def IC />}} 1805) is a large {{<def "HII region" />}} in the
constellation Cassiopeia. It was discovered by William Herschel in 1787, although the full extent of the nebula he had seen was not known until much later --
with the equipment available at the time, he was only able to see the bright knot at the bottom left of the Fish Head Nebula, labelled {{<def NGC />}} 896 in
the annotations overlay. Other small patches of the nebula were discovered over time until they were eventually stitched together into the one we now know as the Heart Nebula -- likely within a few decades of the widespread adoption of [photographic plates](https://en.wikipedia.org/wiki/Photographic_plate#Astronomy) in the late 19th century, but I've been unable to track down an exact citation if one exists.

The heart nebula is both illuminated and shaped by the radiation from just a few young stars in {{<def Melotte />}} 15, the star cluster at its core, burning with an intensity capable of stripping away electrons from the surrounding atoms. When these stripped electrons are eventually recaptured by another atom, they release excess energy in the form of photons as they cascade down through the energy levels to their ground state. More often than not, this series will include the {{<def "hydrogen alpha" />}} transition, responsible for the deep red color which dominates most nebulae.{{% cite "https://books.google.com/books?id=ndd2DQAAQBAJ&pg=PA343#v=onepage&q&f=false" %}}

<!-- {{<todo>}} [absent microquasar](https://apod.nasa.gov/apod/ap040916.html) {{</todo>}} -->

This frame contains my fiancée's favorite celestial object, an easily-missed ringlike structure at the top called WeBo 1. WeBo 1 is a {{<def "planetary nebula" />}} discovered serendipitously by University of Illinois professor Ronald F. Webbink while investigating a nearby X-ray star in the Digitized Sky Survey, a 1994 project by the Space Telescope Science Institute to publish a complete map of the night sky.{{% cite "https://ui.adsabs.harvard.edu/abs/2003AJ....125..260B/abstract" %}} WeBo 1 is noteworthy among other planetary nebula for its shape (a nearly mathematically perfect ellipse of ionized hydrogen, which gave a handful of other authors an excuse to add Lord of the Rings puns into papers researching similar objects{{% cite "https://ui.adsabs.harvard.edu/abs/2007AJ....134..846S/abstract" %}}), and the combination of stars at its core. While its {{<def "binary star" />}}s are not uncommon{{% cite "https://ui.adsabs.harvard.edu/abs/2010ApJS..190....1R/abstract" %}}, and are increasingly favored as an explanation for the more unusual forms which can be taken by planetary nebulae{{% cite "https://ui.adsabs.harvard.edu/abs/2017NatAs...1E.117J/abstract" %}}{{% cite "https://ui.adsabs.harvard.edu/abs/2009PASP..121..316D/abstract" %}}, this was at time of discovery one of only three planetary nebulae with a barium star at its core -- and the classification of one of them has since been contested.{{% cite "https://ui.adsabs.harvard.edu/abs/2012MNRAS.419...39M/abstract" %}} Barium stars are low-temperature red giants "contaminated" by heavier elements forged inside an aging companion star and shared through {{<def "stellar wind" />}} as it becomes a white dwarf;{{% cite "https://ui.adsabs.harvard.edu/abs/1988A%26A...205..155B/abstract" %}} WeBo 1 is a rare snapshot of this process in action.

This image is a 2x2 mosaic taken over three nights with 8 hours total exposure time (4 hours on Jan 9, 1 hour on Feb 13, 3 hours on Feb 14). Each quarter of the mosaic is made up of 25x300s Ha images taken at 0°C, and calibrated with 25 flat darks and 40 darks. The right panels used 25 flats, the left panels only used 20, and the 14th re-used the flats taken on the 13th since they were messed up. Stacked and calibrated with DeepSkyStacker, and stitched together, stretched and colorized with PixInsight (with assistance from plugins for BlurXTerminator v1, NoiseXTerminator, and StarNet++ v2).

***This is a false-color image***: although it has been processed to look somewhat similar to its real-life colors, its final appearance is the result of only a single channel of {{<def narrowband />}} data cloned into all three color channels, with intensity curves altered after the fact to create a pink/red color balance. The chosen color is brighter than it would appear to a traditional color camera in order for it to pop more on a matte metal print gifted to my fiancée.