# unity-enhanced-foliage

In this package you will find two shader solutions for non terrain leaves and grass movement. With this solution based in the Standard Surface Shader, you can implement your texture with an workflow similar to the unity standard shader, controling metallic and smoothness values of the material to create, for example, a wetness effect in the leaves. The vertex movement part of the shader was taken from [here](https://forum.unity3d.com/threads/shader-moving-trees-grass-in-wind-outside-of-terrain.230911/). Thanks, GambinoInd.

You can also control the behaviour of the leaves by changing values of the variables in the "CustomWind" script that must be
inside of any game object in your scene. This script is not a type of "wind zone", it just controls the global variables
of the shaders so you do not have to do this manually in all instantiated prefarbs.

Unfortunately I could not develop any solution for the bark movement using the same concepts of these two shaders, but for now 
it is a good solution for custom trees and grass. The package contain a example scene with the original setup to help you understand 
how scripts work.

**You are free to do whatever you want _except sell it_.**

![enhanced foliage for unity 5](https://github.com/lukasRodrigues/unity-enhanced-foliage/blob/master/efsetup.jpg?raw=true)

![enhanced foliage for unity 5](https://github.com/lukasRodrigues/unity-enhanced-foliage/blob/master/unity_enhanced_foliage_free_shader.png?raw=true)

![unity 5 move grass and leaves outside terrain](https://github.com/lukasRodrigues/unity-enhanced-foliage/blob/master/enhanced_foliage.png?raw=true)

![unity 5 transparent leaves with global fog](https://github.com/lukasRodrigues/unity-enhanced-foliage/blob/master/enhanced_foliage_2.png?raw=true)
_With some post process like global fog and antialiasing._
