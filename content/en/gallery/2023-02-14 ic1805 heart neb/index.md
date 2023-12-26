---
title: "IC 1805, The Heart Nebula"
description: "For Koi 🧡"
tags: ["deep-sky", "cassiopeia", "nebula", "diffuse-nebula", "emission nebula"]

draft: true

date: 2023-02-14

equipment:
    camera: Atik 383L+ Mono
    filters: 36mm Baader Ha
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

The Heart Nebula (also known as {{<def Sh2 />}}-190 or by its associated star cluster {{<def IC />}} 1805) is a {{<def ha>}}hydrogen alpha{{</def>}} emission nebula in the constellation Cassiopeia. It was discovered by

WeBo 1 is a {{<def "planetary nebula" />}} discovered serendipitously by University of Illinois professor Ronald F. Webbink while investigating a nearby star in the Digitized Sky Survey, a 1994 project by the Space Telescope Science Institute to publish a complete map of the night sky.{{% cite "https://ui.adsabs.harvard.edu/abs/2003AJ....125..260B/abstract" %}} WeBo 1 is noteworthy among other planetary nebula for its shape (a nearly mathematically perfect ellipse of ionized hydrogen, which gave a handful of other authors an excuse to add Lord of the Rings puns into papers researching similar objects{{% cite "https://ui.adsabs.harvard.edu/abs/2007AJ....134..846S/abstract" %}}), and the combination of stars at its core. While {{<def "binary star" />}}s are not uncommon{{% cite "https://ui.adsabs.harvard.edu/abs/2010ApJS..190....1R/abstract" %}} and are increasingly favored as an explanation for the more unusual forms which can be taken by planetary nebulae{{% cite "https://ui.adsabs.harvard.edu/abs/2017NatAs...1E.117J/abstract" %}}{{% cite "https://ui.adsabs.harvard.edu/abs/2009PASP..121..316D/abstract" %}}, this was at time of discovery one of only three planetary nebulae with a barium star at its core -- and the classification of one of them has since been contested.{{% cite "https://ui.adsabs.harvard.edu/abs/2012MNRAS.419...39M/abstract" %}} Barium stars are low-temperature red giants "contaminated" by heavier elements forged inside an aging companion star and shared through {{<def "stellar wind" />}} as it becomes a white dwarf;{{% cite "https://ui.adsabs.harvard.edu/abs/1988A%26A...205..155B/abstract" %}} WeBo 1 is a rare snapshot of this process in action.

<!-- <div class="overflow-scroll">

Date | Panel | Count | Flats
:---|:---|:---:|:---:
1/9/2023 | Top Right | 25 | 25
1/9/2023 | Bottom Right | 25 | 25
2/13/2023 | Bottom Left | 15 | 20
2/14/2023 | Bottom Left | 10 | 20
2/14/2023 | Top Left | 25 | 20

1/9: 90%
2/13: 44%
2/14: 33%

(90*(50/100) + 44*(15/100) + 33*(35/100))/3

</div> -->

This image is a 2x2 mosaic taken over three nights with 8 hours total exposure time (4 hours on Jan 9, 1 hour on Feb 13, 3 hours on Feb 14). Each quarter of the mosaic is made up of 25x300s Ha images taken at 0°C, and calibrated with 25 flat darks and 40 darks. The right panels used 25 flats, the left panels only used 20, and the 14th re-used the flats taken on the 13th since they were messed up. Stacked and calibrated with DeepSkyStacker, and stitched together, stretched and colorized with PixInsight (with assistance from plugins for BlurXTerminator v1, NoiseXTerminator, and StarNet++ v2).