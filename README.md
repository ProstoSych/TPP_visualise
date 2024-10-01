# Protein Solubility Curve Predictor
This is a standalone .exe application for predicting and visualizing protein solubility curves. It allows you to interactively adjust theoretical curve parameters and fit experimental data, providing insights into the behavior of protein solubility under different conditions. The application dynamically calculates the fit using R² scores for both control and treatment datasets.

# Features
Theoretical Protein Solubility Curve Visualization:

Adjust the theoretical curve parameters using sliders.
View the predicted protein solubility curves based on adjustable parameters:
A: Curve parameter
B: Treatment-related parameter
T<sub>d</sub>: Temperature of denaturation
K: Weight of two curve components
ΔT<sub>d</sub>: Temperature difference
The theoretical curve is displayed dynamically as you adjust the sliders.
# Fitting Experimental Data:

Load your experimental data to compare with theoretical predictions.
The program fits the experimental data using curve fitting and calculates the R² score for each fit.
Visualize both the experimental data points and the fitted curves.
# Real-Time Interactive Adjustment:

After loading experimental data, adjust the sliders to see how different parameter values affect the fit of the theoretical model to the experimental data.
R² scores are dynamically updated as you modify the sliders.

# Built-In Equation Visualization:

The application displays the equations used for the theoretical model next to the sliders as a visual reference.
# How to Use the Application
Step 1: Run the Application
The program is provided as a standalone .exe file. Simply double-click on the executable to launch the application. No installation of Python or other dependencies is required.

Step 2: Adjust Theoretical Curve Parameters
Once the application opens, you will see sliders on the left side. You can use these sliders to adjust the parameters that define the shape of the theoretical protein solubility curves.

A: Curve shape parameter
T<sub>d</sub> (B): Temperature of denaturation of control sample
ΔT<sub>d</sub> (T): Temperature difference parameter
K: Weight of two components in the curve
B: Treatment parameter
As you modify the sliders, the plot of the theoretical solubility curves will update in real-time.

Step 3: Load Experimental Data
To load experimental data:

Click the "Load Experimental Data" button.
Select a CSV file that contains your experimental data.
The CSV file should have the following structure:

csv
TEMPERATURE,CONTROL,TREATMENT
310,0.5,0.6
315,0.55,0.65
320,0.6,0.7
...
TEMPERATURE: List of temperature values in degrees of Kelvin.
CONTROL: Measured values for the control group.
TREATMENT: Measured values for the treated group.
Step 4: View and Compare Experimental Data
Once your data is loaded:

The experimental points will be plotted on the graph.
The application will automatically fit the theoretical model to the experimental data using non-linear curve fitting.
Both the fitted curves and the experimental data points will be displayed, and the R² values will be calculated to show how well the theoretical model fits the data.
Step 5: Adjust Parameters After Loading Data
After loading experimental data, you can continue adjusting the sliders to further refine the fit of the theoretical model. As you adjust the parameters, the R² values will update in real-time, allowing you to see how different parameter combinations improve or worsen the fit.

Step 6: Close the Application
When you are done using the application, you can close it by clicking the "X" button in the window or using the appropriate shortcut for closing programs on your system.

Requirements
Since this is a standalone executable file, you do not need to install Python or any external libraries. Simply download the .exe file and run it on your Windows machine.
