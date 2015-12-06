# Science-Affliction

INITIALIZATION TXT files are to be removed once there is actual content in a folder.
Their purpose is to have GitHub show folders that are "empty".


=========================================

Rendering guide lines for scene 2 to 4:


AO value = 0.1
AO distance = 10
----------------
(check for preset "Limited Global Illumination" since it might already be setup this way) 
Light Paths:
	Transparency:
		Min = 8
		Max = 8
	Bounces:
		Max = 8
		Min = 3
	Diffuse = 1
	Glossy = 4
	Transmission = 8
	Volume = 2
	Shadows = true
	Reflective Caustics = false
	Refractive Caustics = false
	Filter Glossy = 0
----------------
Shading:
	Backface Culling = true
	Depth of Field depends on shot / camera focus
	Ambient Occlusion = true
		Strength = 1
		Distance = .2
		Attenuation = 1
		Samples = 30