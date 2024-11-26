# Buck_Converter
Creating a Buck Converter in Simulink to get desired output voltage
# Buck Converter Simulation

## Project Description
  This Simulink project demonstrates the design and simulation of a buck converter circuit. 
  The buck converter steps down the input voltage while stepping up the current. The main components of the circuit include:
- A pulse generator to control the switching of the transistor.
- A DC voltage source as the input voltage.
- A MOSFET transistor acting as a switch.
- A diode to allow current flow in one direction.
- An inductor to store and release energy.
- A capacitor to smooth out voltage ripple.
- A resistor as the load.
- A voltage measurement block to measure the output voltage.
- A scope to display the output voltage waveform.

## Input Values
  Here are the input values used in the simulation:
- **Input Voltage (Vi)**: 48V
- **Output Voltage (Vo)**: 18V
- **Load Resistance (R)**: 10 ohms
- **Switching Frequency (f)**: 40,000 Hz

## Tools Used
- MATLAB Simulink

## Results
- The simulation provides a detailed analysis of the buck converter's performance, including the output voltage waveform, inductor current, and capacitor voltage.


## How to Use
1. Clone this repository to your local machine.
2. Ensure you have MATLAB and Simulink installed.
3. Open the Simulink model file (`buck_converter.slx`).
4. Run the simulation and observe the output voltage waveform on the scope.

## Files Included
- `buck_converter.slx`: The Simulink model file.
- `README.md`: Project description and details.
- Optional: Detailed documentation in the `docs` folder.

## Author
- Jayesh Verma
- [LinkedIn](https://www.linkedin.com/in/jayeshv45/)
- [GitHub](https://github.com/Jayeshv45)
