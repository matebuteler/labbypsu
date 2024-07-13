# LabbyPSU

An easy-to-make, space-efficient, DIY, powerful lab power supply for the hobbyist.
Made from parts most people have laying around (that would otherwise turn into e-waste).
![3D render of the power supply](images/BLT%20view.png)
![3D render of the power supply, section view](images/Section%20View.png)

# Specs
Specs depend on the hardware you use to build it, but a typical build is expected to output up to 38V on its output, depending on the buck converter (the xl4005 gives you 35V max) The PCB can handle up to 8A of current on a 35um copper sheet! That equals 89% of the maximum current output the Xl4005 can handle, but I doubt the RCA cables will be happy carrying 8 or 9 amps. The PSU is designed to give you a single voltage and current controlled output, on the 0-38V and 0-8A range.

# Concept
We all have old power bricks laying around, right? Well, just put them in series, hook them up to a DC-DC regulator, and you've got a heavy duty PSU. And banana cables are hard to get, so just throw in some old RCA cables you may have laying around (each cable has two lanes, bridge them so that you can lower the resistance!)
