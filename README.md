////////////////////////////////////////////////////////////////////////////////
//
// MatrixPilot
//
// Firmware for Bill Premerlani's IMU based UAV Dev Board
//

Welcome to the MatrixPilot codebase. This code currently supports three board types, the UDB4 and UDB5 from SparkFun, and the AUAV3 from Arsov RC Technology.

Projects for the three boards are provided for both the traditional Microchip MPLAB-8 and and the new MPLAB-X Integrated Development Environments (IDE).

The main project files are in the MatrixPilot directory.

MPLAB version 8:
    MatrixPilot-udb4.mcp
    MatrixPilot-udb5.mcp
    MatrixPilot-auav3.mcp

MPLAB-X:
    MatrixPilot-udb4.X
    MatrixPilot-udb5.X
    MatrixPilot-auav3.X

Similarly, the RollPitchYaw directory contains project files for an IMU test and demonstration program.

The Tools directory contains numerous programs to support MatrixPilot setup and operation.

To configure MatrixPilot for your plane, edit the configuration files in the ./Config directory.

For developers, there is also a makefile based build system (build-all.bat) and a project generator (Tools/Build/proj_gen.bat), which are *nix compatible.

For more info about how to configure and use this autopilot firmware, go to:

   http://code.google.com/p/gentlenav/
