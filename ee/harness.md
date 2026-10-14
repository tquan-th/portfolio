# Approaches to Cable Harness Design
I've designed several cable harness for RF, power and data-related applications, sometimes combining these aspects. As my systems typically require robust cabling (mechanically and electrically), my initial design considerations are:
* **Signal Type:** Are these signals discrete/single-ended or differential? How much voltage and current will be running through them?
* **Signal Integrity:** Will these signals need additional shielding for differential pairs or due to EMI sensitivity?
* **Physical Interface:** Is this a cable-to-board or board-to-board connection?
* **Mating Cycles:** Will this cable only need to be installed once, or will it constantly be unplugged and re-plugged (common in some test fixtures)?
* **Density:** Do the pin count and size constraints of the larger system conflict?
* **Availability:** I generally look for commonly-used connector series from Molex, JST, Amphenol, Samtec, or anything stocked by Digi-Key or similar vendors to counter potentially long lead-times.
