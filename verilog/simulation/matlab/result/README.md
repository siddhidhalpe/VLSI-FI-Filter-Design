# Results and Observations

## Input Signal
An impulse input signal was applied to the FIR filter using the testbench.

## Output Response
The FIR filter produced a finite-duration output corresponding to the filter coefficients.
The output values gradually settle to zero, confirming FIR behavior.

## Functional Verification
- The shift-register structure correctly delays input samples.
- Each delayed sample is multiplied by its corresponding coefficient.
- The accumulated sum produces the filtered output.

## Observation
- Output is stable and bounded.
- No feedback is present, ensuring stability.
- The filter follows theoretical FIR characteristics.

## Conclusion
The FIR filter design behaves as expected based on DSP theory and RTL implementation.

