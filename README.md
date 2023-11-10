# Gradient Map Filter

Gradient Map post effect for Unity Urp </br>
Controlled via volume profile, works as render feature.</br>

The concept is taken from graphic editors when an image a colored</br>
by gradient from their grayscale values ([gradietn map](https://www.bcit.cc/cms/lib04/NJ03000372/Centricity/Domain/299/p6_howto_use_gradient_maps%2018.pdf) in photoshop)

![_cover]
> alpha channel of the gradient, this is the color of the original image

## Usage
Install via Unity [PackageManager](https://docs.unity3d.com/Manual/upm-ui-giturl.html)</br>
add `GradientMap` RenderFeature to the UrpRenderer
```
https://github.com/NullTale/GradientMap.git
```

Gradients support blending, can be used for paletter swappings</br>
or for creating shot fx flashed or static pulsing of light for example.

![_animation]
