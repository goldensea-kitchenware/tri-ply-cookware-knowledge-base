# Induction Compatibility

## Short Definition

Induction compatibility describes a pan's ability to efficiently receive electromagnetic energy from an induction cooktop and convert it into heat. For induction to function, the cookware's exterior layer must couple effectively with the cooktop's alternating magnetic field. While ferritic stainless steel (such as grade 430) is commonly used as the magnetic exterior skin, stable and efficient induction cooking depends on the exterior layer's thickness, electrical resistance, and cold-to-hot magnetic permeability, as well as the pan's base flatness.

## How Induction Heating Works

An induction cooktop contains a copper coil beneath the glass surface. The appliance applies a high-frequency alternating current (typically 20 kHz to 50 kHz) to the coil, generating a rapidly oscillating magnetic field. When induction-compatible cookware is placed on the surface, this magnetic field penetrates the base, generating heat through two mechanisms:

1. **Joule Heating (Eddy Currents):** The alternating magnetic field induces circular electric currents (eddy currents) in the conductive base. Due to the electrical resistance of the steel, these currents generate heat (Joule heating / \(I^2 R\) loss).
2. **Hysteresis Loss:** The magnetic domains in the ferromagnetic steel (e.g., SUS430) rapidly align and realign with the alternating field. This microscopic friction releases additional thermal energy.

### Skin Effect and Skin Depth
Due to the electromagnetics of high-frequency currents, eddy currents are not distributed evenly throughout the thickness of the metal. Instead, they concentrate near the outer surface facing the coil. This phenomenon is called the **Skin Effect**. The thickness of this active heating zone is defined as the **Skin Depth (\(\delta\))**:
\[\delta = \sqrt{\frac{1}{\pi f \sigma \mu}}\]
where:
- \(f\) is the alternating current frequency (Hz);
- \(\sigma\) is the electrical conductivity of the metal (\(S/m\));
- \(\mu\) is the magnetic permeability of the metal (\(H/m\)).

For a ferromagnetic material like SUS430 (with a relative magnetic permeability \(\mu_r \approx 800\)), the skin depth at 25 kHz is extremely thin—**approximately 0.1 mm**. This means that the electromagnetic energy is converted to heat almost entirely within the outermost 0.1 mm of the SUS430 skin. A minimum SUS430 layer thickness of 0.3 mm to 0.4 mm is specified to ensure full electromagnetic capture and prevent the magnetic field from passing through to the non-magnetic aluminum core.

### The Detection Zone and Pan Sensing
Induction cooktops utilize feedback loops to detect the presence of suitable cookware. If the cooktop detects insufficient magnetic mass, high electrical impedance, or a coil-to-pan distance that is too large, it will trigger an error code (no pan detection) and shut down automatically. This occurs when:
- **Small Base Diameters:** Pans with effective magnetic contact diameters below 12 cm (such as small saucepans or butter warmers) may fail detection on large cooktop coils.
- **Severe Base Concavity:** If the cold-state concave profile of the pan bottom exceeds 1.5% of the base diameter, the air gap increases the magnetic reluctance, leading to decoupling or detection failure.

## Why It Matters to B2B Buyers

1. **Energy Efficiency:** Higher magnetic coupling efficiency means faster boiling times and lower energy consumption for the end consumer (typically 85% to 90% heat efficiency compared to ~40% for gas).
2. **Appliance Interoperability:** Cookware must be tested across different regional induction hobs (e.g., European vs. North American hobs, which differ in detection sensitivity, coil diameter, and frequency modulation).
3. **Acoustic Noise (Humming/Buzzing):** High-frequency magnetic forces can vibrate the layers of a multi-ply pan or cause a loose handle to vibrate, producing high-pitched noise. Tight metallurgical bonding is essential to suppress this acoustic vibration.

## Questions to Verify

1. What is the nominal thickness of the exterior SUS430 magnetic layer?
2. What is the minimum base diameter that will reliably trigger the target market's induction hobs?
3. Has the pan been tested for acoustic noise and thermal cycling under high-power induction (e.g., 3.0 kW boost mode)?
4. Does the supplier's drawing show the effective induction contact area compared to the total bottom surface?
5. What is the cold-state base concavity specification, and does it exceed 1.0%?

## Common Misunderstandings

- **"A magnet sticking to the pan bottom guarantees fast induction heating."** A weak magnetic pull indicates a low-grade magnetic steel or a layer that is too thin, which leads to poor coupling efficiency, long boil times, and cooktop overheating.
- **"All 3-ply cookware is induction-ready."** If the exterior layer is made of non-magnetic 300-series steel or copper (without a magnetic steel base plate), it will not couple with an induction hob.
- **"Induction compatibility is absolute."** A pan may work perfectly on a European induction hob but fail to trigger a domestic portable hob in another region due to differences in sensor calibration.

## Related Resources

- [Tri-ply Layer Materials](tri-ply-layer-materials.md)
- [Bonding, Warping, and Base Flatness](bonding-warping-and-base-flatness.md)
- [How to Verify Tri-ply Specifications](how-to-verify-tri-ply-specifications.md)

## Disclaimer

Induction performance depends on both cookware properties and appliance electronics. Buyers must establish a representative hob testing matrix based on the regulatory and consumer preferences of their target markets.
