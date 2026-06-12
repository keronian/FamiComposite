# FamiComposite
A Famicom Composite bypass adapter

This is a basic Famicom Composite bypass adapter, inspired by other compact designs, using the basic video circuit from [NESDev](https://www.nesdev.org/wiki/PPU_pinout#Composite_Video_Output), but with an additional optional spot for another 100µF decoupling capacitor.

Pin 22 of the PPU is used as a +5V here, as the reset pin of the PPU is tied to +5V in this system.
