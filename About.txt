# Dark Matter Profile Comparison Code

This Mathematica code generates a comparative analysis of five widely used dark matter density profiles: **Hernquist**, **NFW (Navarro-Frenk-White)**, **Burkert**, **Isothermal**, and **Einasto**. The goal is to visualize and compare their main properties — density, gravitational potential, and velocity curves — in a clear format.

### What the Code Does

1. **Defines the Profiles**
The code first sets up mathematical expressions for each dark matter model, describing how the density changes with distance from the galactic center. Each profile has distinct characteristics:

- **Hernquist** and **NFW** are commonly used for their simplicity and good fit to simulations.

- **Burkert** has a flat density core, making it suitable for dwarf galaxies.

- **Isothermal** assumes a constant temperature, leading to a different drop in density.

- **Einasto** is more flexible, with a tunable parameter that allows for better fit to high-resolution simulations.

2. **Calculate Gravitational Potentials and Velocity Curves**
For each profile, the code calculates:

- The **gravitational potential**, which determines how stars and gas move under the influence of dark matter.

- The **circular velocity curve**, which shows how fast objects orbit at different distances (important for galaxy rotation studies).

3. **Generate Comparison Plots**
The code produces three high-quality plots, all on the same radial scale for easy comparison:

- **Density Profile (Log-Log Scale)**: Shows how density drops with distance.

- **Gravitational Potential**: Illustrates the strength of the dark matter attraction at different radii.

- **Velocity Curve**: Displays predicted orbital velocities, crucial for matching observations.

### Why this is useful
This code is valuable for students studying dark matter halos, as it provides a quick way to compare different theoretical models. By adjusting parameters (such as scale radius or density), users can test how these profiles behave under different conditions, helping to interpret data from real-world galaxies.

### How to use
Simply run the code in Mathematica to generate the plots. The default settings use normalized units, but you can modify the parameters (e.g. `rs`, `rho0`) to match specific galaxies or simulations.

This code was developed as part of a computational astrophysics study.
