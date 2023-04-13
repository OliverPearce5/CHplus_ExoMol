# CHplus_ExoMol
Data and files associated with the line list calculations of 12CH+ for the ExoMol Project.
---
1) ### 12C1H+_states.txt and 12C1H+_transitions.txt:
The respective States and Transitions file, in ExoMol format, that comprise the line list.

2) ### Modified_LEVEL16.f:
The LEVEL16 code that was modified here due to errors with the initial form of the code. The LEVEL_input_CH+.txt file runs correctly with this modified version but not with
the original LEVEL16 code.

3) ### LEVEL_input_CH+.txt and LEVEL_output_CH+.txt & fort.8:
The respective input and output files for the (modified) program LEVEL16 used in this study. The input file contains the PECs and (T)DMs, LEVEL_output is the main output
file which contains energy levels and other data, fort.8 contains transition information including Einstein coefficients and frequencies. Note that these raw output files
are incorrect in many places due to the neglecting of Lambda-doubling, which is corrected for in the States and Transitions file.

4) ### MARVEL_Transitions.txt and MARVEL_Energies.txt:
The MARVEL_Transitions file documents all observed literature transitions for the relevant states of CH+, and is formatted as input file for MARVEL. The subsequent Energies
file lists the empirical energy levels determined via the MARVEL algorithm.

5) ### Partition_Function.pf:
The temperature-dependent partition function for CH+ up to 10,000K.

6) ### Lambda_Doubling_Energies.txt:
The manually-calculated Lambda-doubling corrections for each v,J level within the A1Pi state. 
