# Description

Intelligent Reflecting Surfaces (IRS) are smart surfaces that manipulate and enhance wireless signals. They can
adapt to improve signal quality and coverage, making them valuable in 5G and beyond.

The IRS in this project has been made for three scenarios as mentioned below:

1. **Single IRS Component (Stage-1):** Analyzes one IRS component between a transmitter (Tx) and receiver (Rx), calculating signal attenuation and phase.

2. **Multiple IRS Components (Stage-2):** Studies the impact of multiple IRS components in the Tx-Rx link.

3. **Tx & Rx between two-sided wall (Stage-3):** Simulates a complex scenario where Tx and Rx are between two walls, each with multiple IRS components.

**Inputs:** Users choose a stage and input parameters like wavelength, heights, and frequency in SI units (floats/integers).

**Outputs:** The tool calculates signal attenuation and phase analytically and using derived formulas. In Stage-1, it plots attenuation vs. reflection coefficient phase in 10-degree steps.
