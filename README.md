# Gradient Map

[![Twitter](https://img.shields.io/badge/Follow-Twitter?logo=twitter&color=white)](https://twitter.com/NullTale)
[![Discord](https://img.shields.io/badge/Discord-Discord?logo=discord&color=white)](https://discord.gg/CkdQvtA5un)
[![Boosty](https://img.shields.io/badge/Support-Boosty?logo=boosty&color=white)](https://boosty.to/nulltale)

GradientMap post effect for Unity Urp, controlled via volume profile </br>
Works as render feature or a pass for selective post processing [VolFx](https://github.com/NullTale/VolFx)

The concept is taken from graphic editors when an image a colored</br>
by gradient from their grayscale values ([gradietn map](https://www.bcit.cc/cms/lib04/NJ03000372/Centricity/Domain/299/p6_howto_use_gradient_maps%2018.pdf) in photoshop)

![_cover](https://github.com/NullTale/GradientMapFilter/assets/1497430/18cf6991-1486-49f8-bd38-099fe50ef500)</br>
> gradietn alpha - color of the original image

## Part of Artwork Project

* [Vhs](https://github.com/NullTale/VhsFx)
* [OldMovie](https://github.com/NullTale/OldMovieFx)
* [GradientMap]
* [ScreenOutline](https://github.com/NullTale/OutlineFilter)
* [ImageFlow](https://github.com/NullTale/FlowFx)
* [Pixelation](https://github.com/NullTale/PixelationFx)
* [Ascii](https://github.com/NullTale/AsciiFx)
* [Dither](https://github.com/NullTale/DitherFx)
* ...

## Usage
Install via Unity [PackageManager](https://docs.unity3d.com/Manual/upm-ui-giturl.html)</br>
Add `GradientMap` RenderFeature to the UrpRenderer
```
https://github.com/NullTale/GradientMapFilter.git
```

Gradients a support runtime blending and can be used for palette swapping,</br>
creating short fx events or static pulsing of light as in the example.

![_animation](https://github.com/NullTale/GradientMapFilter/assets/1497430/206d8a47-4285-4ccb-9ca0-124184576afc)
> example can be found in the project samples

#### GradientMap like effect from Cult of the Lamb

https://github.com/NullTale/GradientMapFilter/assets/1497430/84de70d6-fdfb-4b95-bf1c-afd46600bd98
