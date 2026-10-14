# Approaches to Cable Harness Design
I've designed several cable harnesses for RF, power and data-related applications, sometimes combining these aspects. As my systems typically require robust cabling (mechanically and electrically), my initial design considerations are:
* **Signal Type:** Are these signals discrete/single-ended or differential? How much voltage and current will be running through them?
* **Signal Integrity:** Will these signals need additional shielding for differential pairs or due to EMI sensitivity?
* **Physical Interface:** Is this a cable-to-board or board-to-board connection?
* **Mating Cycles:** Will this cable only need to be installed once, or will it constantly be unplugged and re-plugged (common in some test fixtures)?
* **Density:** Do the pin count and size constraints of the larger system conflict?
* **Availability:** I generally look for commonly-used connector series from Molex, JST, Amphenol, Samtec, or anything stocked by Digi-Key or similar vendors to counter potentially long lead-times.

** Prototype to Production
Oftentimes, crimpers for proprietary connector designs are cost-prohibitive for a short run of prototypes. Depending on the abundance of the cable connector, my first instinct is to look for pre-crimped leads or connector-to-leads assemblies to build a proof of concept. I start out documenting the pinout of each side on a simple spreadsheet, followed by an image or visual diagram of the cable. Once length and positioning are finalized, I create a formal assembly and drawing in SolidWorks for technician use and CM (contract manufacturer) quoting.
