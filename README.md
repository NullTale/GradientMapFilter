# Gradient Map
Dev by NullTale<br>
[![Itch](https://img.shields.io/badge/Web-Itch?logo=Itch.io&color=white)](https://nulltale.itch.io)
[![Twitter](https://img.shields.io/badge/Twitter-Twitter?logo=X&color=red)](https://twitter.com/NullTale)
[![Tg](https://img.shields.io/badge/Tg-Telegram?logo=telegram&color=white)](https://t.me/nulltalescape)<br>
[![Asset Store](https://img.shields.io/badge/Asset%20Store-asd?logo=Unity&color=blue)](https://assetstore.unity.com/packages/vfx/shaders/fullscreen-camera-effects/270020)

FOR NON COMMERCIAL USE ONLY - version is no longer supported and cannot be used in commercial purposes
read the license, official release only on the [AssetStore](https://assetstore.unity.com/packages/vfx/shaders/fullscreen-camera-effects/270020)

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
* [Outline](https://github.com/NullTale/OutlineFilter)
* [Flow](https://github.com/NullTale/FlowFx)
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
