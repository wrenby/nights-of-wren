---
title: "Westerhout 5, The Soul Nebula"
description: "Salvaged from subpar data"
tags: ["deep-sky", "cassiopeia", "nebula", "diffuse-nebula", "emission-nebula"]

date: 2022-07-22

equipment:
    camera: Fujifilm X-A5
    telescope: GSO 6" F/4
    mount: Celestron AVX
    guider: ZWO ASI120MM Mini

framing:
    ra: 2h54m59s
    dec: +60°25'16"
    width: 114.53'
    height: 75.45'
    pxscale: 1.68"/px
    rot: -17.85°

environment:
    location: Pittsburgh, PA
    bortle: 5
    moon: 39%

featured_image: "img/2022-07-22 w5 soul neb.png"
---

This one sat in my "to-do" pile for almost two years! While I had taken pictures of emission nebulae before, this was by far the dimmest I had attempted to date -- I drastically underestimated the exposure time required, to the point where the nebula could not be seen at all in any of the individual 90s frames! I trusted the process and let the camera roll, but at the end of two clear nights, I didn't have much to show for my patience. Although the coarse structure of the nebula was visible, the sheer level of noise made any details very difficult to tease out from light pollution and camera read noise, even with almost eight hours of integration time. I made three or four attempts before writing it off as unusably bad data, shelving it for years before I came back almost two years later for a challenge.

This image is a composite of 308 90-second subframes taken across two consecutive nights, processed in PixInsight. They were calibrated and registered with WBPP, using separate color channels and the "superpixel" demosaic strategy to reduce artifacting and save memory, then integrated with a 2x drizzle to make up for the loss in resolution. The processing workflow after that is fairly standard: ChannelCombination, BlurXTerminator, PhotometricColorCalibration, GradientCorrection, NoiseXTerminator, SCNR, a little stretching, StarNet2, more stretching, star recombination in PixelMath, then some final tweaks to curves, color balance, and the crop.