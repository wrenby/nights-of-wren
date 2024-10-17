---
title: "NGC 2147, The Monkey Head Nebula"
description: "A bright emission nebula just off Orion's club"
tags: ["deep-sky", "orion", "nebula", "diffuse-nebula", "emission-nebula"]

date: 2024-02-05

equipment:
    camera: Atik 383L+ Mono
    filters: Baader SHO
    telescope: GSO 6" F/4
    mount: Celestron AVX
    guider: ZWO ASI120MM Mini

framing:
    ra: 06h09m50s
    dec: +20°33'12"
    rot: -80.41°
    width: 74.73'
    height: 52.71'
    pxscale: 1.63"/px

environment:
    location: Pittsburgh, PA
    bortle: 5
    moon: 37% # probably wrong

featured_image: "img/2024-02-05 ngc2174 monkey head neb.png"

---

Article coming soon!

<!-- also see images from 2023-11-18, 2024-02-03, and 2024-02-04 -->


<!-- SHO color palette, with LRGB stars.

STAR LAYER: The luminance and 2x2 RGB layers were initially processed separately -- since the CIEL\*a\*b\* color space is nonlinear, attempting to apply the luminance mask in the linear phase would result in severe discoloration. Each one was run through GradientCorrection, and a few rounds of GeneralizedHyperbolicStretch, with RGB also  SpectrophotometricColorCalibration between the two. After replacing the RGB image's L channel with the luminance data with ChannelExtraction and ChannelCombination, I used BlurXTerminator and StarNet2 to create a clean star mask, which I stretched a bit more before setting it aside for use at a later stage.

TODO: redo bxt on stars

NEBULA LAYER: The Ha data came from nights with wildly varying rotations, so the two nights had to be combined manually LinearFit to match night 4 to night 1. Generated a starless mask using StarNet2, HistogramStretch, MorphologicalTransform, and Convolution. Combined using PixelMath, using the mask as a way to restrict the influence to the nebula region.


DynamicCrop, GradientCorrection, BlurXTerminator, GeneralizedHyperbolicStretch, StarNet2,
TODO: CloneStamp to mask some StarNet2 artifacts, more stretching, LinearFit to match SII, ChannelCombination, NarrowbandNormalization, BackgroundNeutralization, NoiseXTerminator -->