---
title: "M 97, The Owl Nebula"
description: "A planetary nebula near Merak"
tags: ["deep-sky", "ursa-major", "nebula", "planetary-nebula", "emission-nebula", "messier-object"]

date: 2023-02-16

equipment:
    camera: ZWO ASI120MM Mini
    telescope: GSO 6" F/4
    mount: Celestron AVX

framing:
    ra: 11h14m51s
    dec: +55°01'35"
    rot: -86.12°
    width: 13.88'
    height: 10.32'
    pxscale: 0.71"/px

environment:
    location: Pittsburgh, PA
    bortle: 5
    moon: 30%

featured_image: "img/2023-02-16 m97 owl neb r2.png"

revisions:
  - image: "img/2023-02-16 m97 owl neb r2.png"
    name: Denoised
    date: 2024-04-05
  - image: "img/2023-02-16 m97 owl neb.png"
    name: Original
    date: 2023-02-16
---

What to do with a planetary {{<def "imaging train" />}} after the planets are out of sight? My main camera was out of commission, so I had to make due with the setup I was using: a high-magnification lens paired a camera with very small pixels, on an unguided mount that I never bothered to accurately {{<def "polar align" />}}. Not ideal for dimmer targets, but I figured since the camera I was using had low {{<def "read noise" />}}, I could just take a few hundred or thousand short exposures and still get something useful through the noise. So I looked up some potential targets, picked {{< def M />}} 97, found the nearest bright star with the help of my finder scope, and began hopping over, being careful to confidently identify the location of each frame I took on my way there. When I arrived, I decided to push my luck, since the 5-second exposures I used to find my way over looked very sharp, and managed to push all the way to 60 seconds with most of the frames still coming out looking good, which allowed for the resolution of fainter details.

**So what is it?** M 97 is a planetary nebula, a glowing cloud of ionized elements which previously made up the outer layers of a recently-dead average-sized star. A planetary nebula is essentially the equivalent of a supernova for stars which don't have enough mass. Although this particular example is rather spherical and symmetrical in shape, planetary nebulae come in a surprisingly wide variety of shapes, with the physics behind this variation being a subject of active research. M 97 was discovered by Pierre Méchain on February 16, 1781 -- meaning this image was, by sheer coincidence, taken precisely on the 242nd anniversary of its discovery. It is estimated to be about 8000 years old and two to three thousand light years away.

Captured with a ZWO ASI120MM Mini, a Tele-Vue 2x Barlow Lens, a set of Baader LRGB filters, and a GSO 6" F/4 mounted on a Celestron AVX. The luminance frames were {{<def stack>}}stacked{{</def>}} using DeepSkyStacker, and most of the remaining processing was in Siril: manually registering (not enough stars visible in the small FOV for automation) and stacking each RGB channel, aligning the channels and compositing them with luminance, RBF background extraction, and a histogram stretch. I ran it through Starnet++, and finished processing in GIMP by throwing some layer masks on a wavelet decomposition, making some tweaks to the saturation, brightness, and contrast, and re-adding the stars. The final image is a stack of 37x60s luminance, 9x60s red, 11x60s green, and 13x60s blue frames, calibrated with 20 dark and 500 bias per binning level, and 20 flat frames per filter. Luminance frames were taken at {{<def binning />}} 1, and RGB frames were taken at binning 2.

UPDATE April 5, 2024: added a new revision, deconvolved and denoised using BlurXTerminator, NoiseXTerminator, and ACDNR (on both luminance and chrominance).