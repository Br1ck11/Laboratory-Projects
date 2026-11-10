# Advanced Physics Lab Reports

Reports from the M.Sc. advanced laboratory course in physics at the University of Bonn.
Each experiment was carried out and written up in a team of two by
Ben Nam-Soo Weihrauch and Christian Gottschlich.

| Report | Topic | Key result |
|---|---|---|
| [MOT.pdf](MOT.pdf) | Magneto-optical trap for ⁸⁵Rb | (1.3 ± 0.3) × 10⁶ trapped atoms |
| [Laser_Gyroscope.pdf](Laser_Gyroscope.pdf) | Passive ring-laser gyroscope | Cavity finesse ≈ 7 × 10⁴, scale factor within 1σ of theory |
| [Nuclear_Gamma_Gamma_Correlation.pdf](Nuclear_Gamma_Gamma_Correlation.pdf) | γ–γ angular correlation of ⁶⁰Co | A₂₂ = 0.098 ± 0.004 |
| [LinearAccelerator.pdf](LinearAccelerator.pdf) | 25 keV electron beamline | Emittance εₓ = 4.13 ± 0.05 mm·mrad |
| [ATLAS_Analysis.pdf](ATLAS_Analysis.pdf) | W-boson mass from ATLAS data | m_W = 80.83 ± 0.08 (stat.) GeV |

## Magneto-optical trap

We aligned the horizontal cooling beams of a vapour-cell trap and locked the cooling
and repump diode lasers by polarization spectroscopy. We then characterised the trap:
atom number, cloud size, loading time (1.79 ± 0.10 s) and optimal laser detuning
(−8.5 MHz, about 1.4 Γ).

## Passive ring-laser gyroscope

We locked counter-propagating 1064 nm beams to a 1 m ring cavity with the
Pound–Drever–Hall technique, measured the finesse by cavity ringdown, and calibrated
the Sagnac scale factor on a rotation table. An Allan-deviation analysis shows the
setup is limited by technical noise and the lock-in effect, so Earth's rotation could
not be resolved.

## γ–γ angular correlation

We calibrated a fast–slow coincidence chain with two scintillation detectors and
measured the angular correlation of the ⁶⁰Co 4–2–0 cascade. Accidental coincidences
were measured and subtracted angle by angle, and the data were corrected for detector
misalignment. Isotropy and the 2–1–0 hypothesis are both excluded.

## Electron beamline

We calibrated the corrector magnets of a 25 keV electron beamline, centred the beam in
four quadrupoles by beam-based alignment, and measured the transverse emittance with
quadrupole scans and the multi-screen method. The calibration showed that the control
system under-reported kick angles by 14–55 %.

## ATLAS analysis

We calibrated the electromagnetic calorimeter on Z → ee decays
(m_Z = 91.18 ± 0.01 GeV) and extracted the W-boson mass with the Jacobian-peak method
and Monte Carlo templates. The result is limited by systematic uncertainties
(+0.41 / −0.81 GeV) and agrees with the world average.

## Notes

- Schematics credited to the lab manuals in the reports belong to their original authors.
- Analysis was done in Python (NumPy, SciPy, Matplotlib).
