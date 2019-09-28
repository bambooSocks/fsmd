# FSMD simulator
###### Build by Matej Majtan, Mihaela-Elena Nistor, Clifford Arnold III Rhodes

## Dependencies
The simulator is tested on Python 3.6.8 with the only dependency: ```xmltodict``` ([link](https://pypi.org/project/xmltodict/)).
## Executing
In order to run the simulator, run ```python3 fsmd-sim.py <max_iterations> <description_file> <stimuli_file>```. ```max_iterations``` and ```description_file``` are required in order to run the program. ```max_iterations``` describes the maximum amount of cycles the simulator should run through before terminating. ```description_file``` is an xml file which contains the structure of the simulated state machine. ```stimuli_file``` is also an xml file which contains additional information about given state machine as the values of inputs in given cycle and the information about the end state of the simulation. The ```stimuli_file``` is not required in order to run the simulator.
