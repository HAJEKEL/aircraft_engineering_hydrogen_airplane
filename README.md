### README.md for Aircraft Engineering Hydrogen Airplane

---

# Aircraft Engineering Hydrogen Airplane

This repository contains MATLAB scripts for the weight estimation and bending analysis of an aircraft designed to use hydrogen fuel. The primary focus is on the wing, tail, and fuselage components.

## Files

- `aircraft_engineering_weight_estimation_wing_tail.m`: Script for estimating the weights of the wing and tail of the aircraft.
- `aircraft_engineering_bending_fuselage.m`: Script for analyzing the bending of the fuselage.

## aircraft_engineering_weight_estimation_wing_tail.m

This script calculates various weights and dimensions related to the aircraft's wing and tail, including:

- Constants such as distance from nose to wing, optimal center of gravity position, and gravitational acceleration.
- Load calculations for passengers, luggage, crew, and attendants.
- Fuselage, propulsion, cargo floor, bulkhead, wing, and tail dimensions.
- Initial and iterative weight estimations for maximum takeoff weight (MTOW), maximum zero fuel weight (MZFW), and operating empty weight (OEW).
- Calculation of forces and moments acting on the aircraft.
- Determination of lift forces, maximum deflection, and pitch moment.

The script includes a comprehensive iterative process to refine weight estimations and ensure accurate calculations.

## aircraft_engineering_bending_fuselage.m

This script focuses on the bending analysis of the aircraft's fuselage. Key features include:

- Calculation of weights and forces acting on the wing and tail using various formulas.
- Determination of maximum moments, slopes, and deflections for a cantilever beam representing the fuselage.
- Analysis of the distribution of weights and lengths along the fuselage.
- Plotting of weight distributions to visualize the forces acting on different sections of the fuselage.

The script uses engineering principles and formulas to ensure precise analysis of the bending effects on the fuselage structure.

## Usage

1. **Clone the repository**:

   ```bash
   git clone git@github.com:HAJEKEL/aircraft_engineering_hydrogen_airplane.git
   cd aircraft_engineering_hydrogen_airplane
   ```

2. **Run the scripts** in MATLAB:
   - Open MATLAB and navigate to the repository directory.
   - Run `aircraft_engineering_weight_estimation_wing_tail.m` to perform weight estimations.
   - Run `aircraft_engineering_bending_fuselage.m` to analyze the bending of the fuselage.

## Contributing

Contributions are welcome! Please feel free to submit a pull request or open an issue for any bugs or suggestions.

## License

This project is licensed under the MIT License.
