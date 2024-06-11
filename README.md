# Admittance Control Simulation in Simulink

This repository contains Simulink models and MATLAB scripts for simulating admittance control systems. Admittance control is a method used in robotic systems to ensure smooth and compliant interactions with the environment.

## Contents

- **Simulink Models:**
  - **[AdmittanceControl.slx](AdmittanceControl.slx)**: Main Simulink model for admittance control simulation.
  
- **MATLAB Scripts:**
  - **[init_params.m](init_params.m)**: Script to initialize parameters for the simulation.
  - **[run_simulation.m](run_simulation.m)**: Script to run the Simulink model and collect data.
  - **[plot_results.m](plot_results.m)**: Script to plot the results of the simulation.

## Getting Started

### Prerequisites

- MATLAB and Simulink (for running the models and scripts)

### Usage

1. Clone the repository:
    ```bash
    git clone https://github.com/mincasurong/Admittance-Control-Simulink.git
    cd Admittance-Control-Simulink
    ```

2. Open MATLAB and run the initialization script:
    ```matlab
    init_params
    ```

3. Open `AdmittanceControl.slx` in Simulink, run the model to simulate the admittance control system.

4. To plot the results, run:
    ```matlab
    plot_results
    ```

## Admittance Control

Admittance control is a robotic control strategy where the robot adjusts its motion in response to external forces. It is particularly useful in applications where the robot interacts with dynamic and unpredictable environments.

### Key Features

- **Smooth Interaction**: Ensures smooth and compliant interactions between the robot and its environment.
- **Parameter Initialization**: Easy initialization of parameters through MATLAB scripts.
- **Result Visualization**: Plots the results of the simulation for analysis.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request for any improvements or additions.

## Acknowledgements

Special thanks to the contributors and the Simulink community for their continuous support and resources.
