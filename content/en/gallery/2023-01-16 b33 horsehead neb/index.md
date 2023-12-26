---
title: "B 33, The Horsehead Nebula"
description: And LBN 953, The Flame Nebula
tags: ["deep-sky", "orion", "nebula", "diffuse-nebula", "emission-nebula", "reflection-nebula"]

date: 2023-01-16

equipment:
    camera: Atik 383L+ Mono
    filters: 36mm Baader RGB
    telescope: GSO 6" F/4
    mount: Celestron AVX
    guider: ZWO ASI120MM Mini

framing:
    ra: 05h40m50s
    dec: -02°17'21"
    rot: -86.24°
    width: 86.41'
    height: 66.09'
    pxscale: 3.26"/px

environment:
    location: Pittsburgh, PA
    bortle: 5
    moon: 100%

featured_image: "img/2023-01-16 b33 horsehead neb.png"
# draft: true
---

On the leftmost edge of Orion's belt lies the triple star system Alnitak, just in front of the of the Orion B molecular complex and next-door neighbor to some of its finest residents: The Horsehead Nebula, discovered by in 1888 by Williamina Fleming, and the Flame Nebula, discovered in 1786 by William Herschel. Both lie at a distance of approximately 400 {{<def parsec>}}parsecs{{</def>}}.{{% cite "https://ui.adsabs.harvard.edu/abs/2014ApJ...786...29S/abstract" %}}

The Horsehead Nebula (also known as {{<def B>}}Barnard{{</def>}} 33) is one of the most recognizable nebulae in the night sky due to its resemblance to the silhouette of a horse, stylized similarly to knight in chess. An intrusion from the large dusty region {{<def LDN />}} 1630 into the {{<def "HII region" />}} {{<def IC />}} 434, it's an example of an object called a pillar or elephant trunk, pockets of interstellar matter whose exterior density affords them a resistance to erosion caused by {{<def "stellar wind" />}}, similar to hoodoos in geology.{{% cite "https://ui.adsabs.harvard.edu/abs/2009AJ....137.3685B/abstract" %}}{{<todo this citation has more to give />}} Along with NGC 2023,{{% cite "https://ui.adsabs.harvard.edu/abs/1996ApJ...468..269D/abstract" %}} the Horsehead Nebula's proximity to Earth makes it an ideal sandbox to study *photodissociative regions*: borders of nebulae where most of the incoming heat comes from high-energy UV radiation, but unlike HII regions are cold and dense enough to remain electrically neutral.{{% cite "https://ui.adsabs.harvard.edu/abs/2017A%26A...606A..29P/abstract" %}}

The Flame Nebula (also known as {{<def LBN />}} 953, {{<def Sh2 />}}-277, and sometimes by its associated star cluster {{<def NGC />}} 2024) is the primary star-forming region of Orion B. It owes both its high rate of star formation and its unique shape to the turbulent interplay between its desire to collapse under its own gravity and the outwards push of stellar wind from hundreds of newly-formed stars.{{% cite "https://ui.adsabs.harvard.edu/abs/2017A%26A...599A..99O/abstract" %}} NGC 2024 is often used as a laboratory to study solar system formation, since an estimated as 85-95% of its stars have accompanying protoplanetary disks.{{% cite "https://ui.adsabs.harvard.edu/abs/2000AJ....120.1396H/abstract" %}} Recent Hubble data suggests that many of these systems may be destined for disintegration, scattered and worn apart by the intense radiation of the surrounding stars before they can survive to form planets.{{% cite "https://science.nasa.gov/missions/hubble/hubble-finds-flame-nebulas-searing-stars-may-halt-planet-formation" %}}

This image is a {{<def stack />}} of just 35 minutes of total exposure time, with each R/G/B filter contributing 25x30s exposures taken at -10°C with {{<def binning />}} 2, each calibrated with 25 flats and no dark or bias frames. The lack of darks and biases was actually a surprise to me as I write this (Dec 17); I'm taking some new ones right now and hoping they can still perform all right on the older data. Expect a revision soon! Stacked and calibrated in DeepSkyStacker, and stretched in Siril, with star removal provided by StarNet++ v2.

<!--
Potential sources:

horsehead dust evolution: https://ui.adsabs.harvard.edu/https://ui.adsabs.harvard.edu/abs/1982ApJ...261..636T/abstract/2020A%26A...639A.144S/abstract
horsehead kinematics: https://ui.adsabs.harvard.edu/abs/2018AJ....155...80B/abstract

photodissociation region: any region of interstellar space dense and cold enough to remain electromagnetically neutral, where the thermodynamics and chemistry is dominated by UV radiation from massive stars
- PDR Mechanics in Orion B (approachable): https://ui.adsabs.harvard.edu/abs/2017A%26A...606A..29P/abstract

PDR in NGC 2023 (hugely influential paper, but very technical): https://ui.adsabs.harvard.edu/abs/1996ApJ...468..269D/abstract

stars in NGC 2024: https://ui.adsabs.harvard.edu/abs/2000AJ....120.1396H/abstract
- people really like talking about protoplanetary disks in this guy:
  - https://ui.adsabs.harvard.edu/abs/2015ApJ...802...77M/abstract
  - https://ui.adsabs.harvard.edu/abs/2020A%26A...640A..27V/abstract

gas and dust in Orion B: https://ui.adsabs.harvard.edu/abs/2001ApJ...556..215M/abstract
-->