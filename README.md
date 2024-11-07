# Instrumentation Ampifier using INA128

This project designs an INA128-based instrumentation amplifier to amplify small differential signals with low noise and high input impedance, suited for medical and sensor uses. Gain is optimized with precision resistors, with testing confirming accuracy and reliability.

## A Glance at the Instrumentation Ampifier

Instrumentation amplifiers are high-precision differential amplifiers widely used to amplify small differential signals, especially in medical devices, sensor data acquisition, and industrial measurement systems. The INA128 is a preferred choice in these applications due to its low noise, high input impedance, and strong common-mode rejection. This report presents the design and implementation of an instrumentation amplifier using the INA128, detailing its operating principles, key benefits, and potential enhancements for improved performance across diverse applications.

## Block Diagram of the Instrumentation Ampifier

![block diagram](https://github.com/user-attachments/assets/9852a175-4bf6-455f-8d56-fb33a53e75af)

# Instrumentation Ampifier Performance Parameters

![parameters](https://github.com/user-attachments/assets/dce01d5f-e8df-4efb-9030-0654e1f90db5)

## Future work

1. Noise Reduction: Investigate methods for further reducing noise, such as adding filtering components or shielding techniques, to improve signal clarity, especially in low-amplitude applications.

2. Power Efficiency: Explore low-power design techniques for battery-operated systems, making the amplifier more suitable for portable medical devices or remote sensors.

3. Temperature Stability: Implement temperature compensation to improve the amplifier’s stability across varying environmental conditions, ensuring consistent performance.

4. Bandwidth Expansion: Increase bandwidth to accommodate a wider range of signal frequencies, which would be beneficial for dynamic applications in industrial and biomedical fields.

5. CMRR Improvement: Enhance the Common-Mode Rejection Ratio (CMRR) to further reduce the effect of noise from external sources, boosting overall signal integrity.

6. Component Optimization: Use higher-precision or custom resistors to allow for more accurate gain adjustments and further minimize drift over time.

7. Enhanced Calibration: Incorporate self-calibration features to adjust gain or offset values dynamically, improving accuracy in long-term, high-precision applications.

These future enhancements would make the amplifier more robust and adaptable across various demanding applications.

## References

1.	https://masteringelectronicsdesign.com/wp-content/uploads/2009/08/instrumentation_amplifier_1.png
2.	http://www.ti.com/lit/ds/symlink/ina128.pdf
















