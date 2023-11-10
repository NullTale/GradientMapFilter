# Gradient Map Filter

Gradient Map post effect for Unity Urp </br>
Controlled via volume profile, works as render feature.</br>

The concept is taken from graphic editors when an image a colored</br>
by gradient from their grayscale values ([gradietn map](https://www.bcit.cc/cms/lib04/NJ03000372/Centricity/Domain/299/p6_howto_use_gradient_maps%2018.pdf) in photoshop)

![_cover](https://github.com/NullTale/GradientMapFilter/assets/1497430/18cf6991-1486-49f8-bd38-099fe50ef500)</br>
> alpha channel of the gradient, this is the color of the original image

## Usage
Install via Unity [PackageManager](https://docs.unity3d.com/Manual/upm-ui-giturl.html)</br>
add `GradientMap` RenderFeature to the UrpRenderer
```
https://github.com/NullTale/GradientMapFilter.git
```

Gradients a support runtime blending, can be used for paletter swappings</br>
for creating short fx flashed or static pulsing of light as in the example.

![_animation](https://github.com/NullTale/GradientMapFilter/assets/1497430/206d8a47-4285-4ccb-9ca0-124184576afc)
> example can be found in the project samples
