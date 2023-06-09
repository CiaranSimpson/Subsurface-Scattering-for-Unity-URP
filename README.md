# Subsurface-Scattering-for-Unity-URP
A simple shader graph subgraph that creates a subsurface scattering like effect. 
Relatively performant, theoretically should work fine on mobile, and easy to use in your own shaders. 

![image](https://github.com/CiaranSimpson/Subsurface-Scattering-for-Unity-URP/assets/43167249/2cba28c3-02cb-44a1-baea-99d49d3c69c0)

Allows for variable thicknessa along mesh using a thickness map and masking.
Currently the resulant scattering colour cannot vary along surface.

Also included is a premade shader using this subgraph, so if you dont know how to use shader graph you can just use that.

It uses the scenes main light primarily - additional lights will not create scattering effect. Effects will also vary significantly depending on material settings and mesh used - the  heads I built the shader for look good with it but I'm yet to get decent results with a regular sphere.

