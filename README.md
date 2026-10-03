# FJM_reproducibility


For reproducibility, we provide the 3D-printing CAD files and detailed experimental procedures in here.

The experimental hardware was custom-built by 3D-printing the attached STL files. The motor used was the XM430-W350-T, and the encoder used was the E6B2-CWZ3E. All motors and encoders were connected to an OpenCR microcontroller unit.

The hardware assembly procedure is as follows.

1. 3D-print all attached files.
- Print the “flexible-joint” part using an elastic TPU material.
- Print all other parts using PLA material.
- 40% infill is recommended for printing.

2. Connect the “link” and the “flexible-joint.”

3. Attach the motor to the assembly from Step 2.

4. Connect the “encoder-connect” part to the encoder.

5. Combine the assemblies from Steps 2 and 4.

6. Attach the “base” to the motor and encoder of the assembly from Step 5.

7. Connect all motors and encoders to the OpenCR microcontroller unit.
- Connect all motors to the TTL port of the OpenCR microcontroller unit.
- Connect all encoders to the digital pins and GND of the OpenCR microcontroller unit.
