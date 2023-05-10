# Repository to Verify Forward Kinematics of Kinova Gen3 Manipulator
The [`FwdKin.m`](FwdKin.m) contains the script to compute the forward kinematics from the Devanit-Hartenberg (DH) parameters of the manipulator.

The kinematic table for the conventional DH parameterization is found on page 204 of the [`Kinova-Gen-3_User-Guide`](Kinova-Gen-3_User-Guide.pdf) and the corresponding frame definitions are found on page 205 and shown below:

![DH Parameters](DH_Kinova.png "DH Parameter Frame Definitions")

The modified DH frame definitions are shown below:

![Modified DH Parameters](modDH_Kinova.png "Modified DH Parameter Frame Definitions")