# SUT-Examples

This repository hold system under test for the demonstration of testing with OpenSBT with CARLA.

## Rover SUT

The `Rover` SUT is developed in the fortiss Mobility Labs and provided in the FMU format.
The SUT can be simulated with the Carla simulator by replacing the launch and share folders in the `rosco` application 
by the ones provided in the `rover/rosco` folder. An example where the Rover SUT is integrated and tested with OpenSBT is provided [here](https://git.fortiss.org/opensbt/opensbt-core/-/blob/main/doc/jupyter/06_Example_CARLA.ipynb).
