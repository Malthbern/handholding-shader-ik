# Handholding Shader IK

This shader allows two avatars to be holding hands, mainly designed for dancing.

A very simplistic [IK system](https://en.wikipedia.org/wiki/Inverse_kinematics) is reprogrammed within the shader code to control a fake arm of one avatar, which will be attracted towards a special light of another avatar.

![](https://github.com/hai-vr/handholding-shader-ik/raw/z-res-pictures/Documentation/demo_1.gif)

*This is not an animation!*

As it is a shader, the effect is not affected by lag: It will give the appearance of handholding from the perspective of everyone with shaders and particles enabled, no matter the delay between the two dancers.

## Avatar conversion guide

The process of converting two avatars for use with Handholding Shader IK may be challenging; head over to the [Conversion guide](GUIDE_conversion.md).

## Authors

This shader was created by **Haï~** ([twitter](https://twitter.com/vr_hai), [github](https://github.com/hai-vr)).

The editor script conversion tool was created by **Lyuma** ([twitter](https://twitter.com/lyuma2d), [github](https://github.com/lyuma)).

## Special thanks

As Haï~, I would like to thank:

- **Lyuma** for inspiring me to create this shader, for being overall awesome and being my dance partner.
- **d4rkpl4y3r** for teaching me the black light technique.