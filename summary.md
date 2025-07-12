This project investigates the behavior of two computational models of neurons: the Hodgkin-Huxley (HH) model and the Morris-Lecar (ML) model. The project is divided into two main parts.

The first part focuses on the HH model. It explores the model's response to different types of input currents, such as impulse and step currents. It also investigates the effect of changing the model's parameters, such as the conductances of the ion channels, on the neuron's excitability.

The second part of the project compares the HH model with the ML model. It analyzes the differences in their phase portraits and how they respond to input currents.

The project uses Python to implement the models and run the simulations. The results are visualized using matplotlib.

The codebase includes the following files:

- `models.py`: This file contains the implementation of the Hodgkin-Huxley and Morris-Lecar models.
- `hw_5_cs_sina_q_1_2_1.py`: This script simulates the HH model's response to impulse and step currents and finds the minimum current required to elicit an action potential.
- `hw_5_cs_sina_q_1_2_2.py`: This script investigates the effect of changing the sodium, potassium, and leak conductances on the HH model's behavior.
- `hw_5_cs_sina_q_1_2_3.py`: This script examines the effect of changing the membrane capacitance and ion channel conductances on the cell's excitability.
- `hw_5_cs_sina_q_1_2_4.py`: This script explores the subthreshold behavior of the HH model in response to step and impulse currents.
- `hw_5_cs_sina_q_2_1.py`: This script compares the phase portraits and responses of the HH and ML models.
