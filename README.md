# Subsurface-Scattering-for-Unity-URP
A simple shader graph subgraph that creates a subsurface scattering like effect. 
Relatively performant, theoretically should work fine on mobile, and easy to use in your own shaders. 

![image](https://github.com/CiaranSimpson/Subsurface-Scattering-for-Unity-URP/assets/43167249/4669f09f-4695-47df-8864-73697ede96c7)


Allows for variable thicknessa along mesh using a thickness map and masking.
Currently the resulant scattering colour cannot vary along surface.

Also included is a premade shader using this subgraph, so if you dont know how to use shader graph you can just use that.

It uses the scenes main light primarily - additional lights will not create scattering effect. 
