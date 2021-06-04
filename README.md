# modifiedUpperLimbModel

Author: Yujun Lai (Robotics Institute (UTS:RI), University of Technology Sydney)

Email: yujun.lai@uts.edu.au

This model has been modified to update the original model to OpenSim 4.x convention (from the original SIMM model).

Changes
 * Inertial properties (and principal moments of inertia) for humerus, radius, and capitate are added.
 * MTUs are updated to the _Millard2012EquilibriumMuscle_ from the original _Schutte1993Muscle_ MTU model (Available parameters are transferred across to the new MTU).
 * Muscles for the thumb are removed.

The original model can be found [here](https://simtk.org/projects/up-ext-model). (Holzbaur et al. 2005)
