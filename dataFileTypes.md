## Dmitry Smirnov’s data acquisition info: 
 
The experimental data (spectra) are acquired by a spectrometer (#1 HRS750, #2 IsoPlane,  Teledyne Princeton Instruments). The spectrometers are (almost) fully automated and controlled via the LightField software (Teledyne Princeton Instruments). LightField automatically saves the acquired data and all experiment settings (spectrometer settings) in one file. 
https://www.princetoninstruments.com/products/software-family/lightfield
 
LightField saves files in *.SPE format (whatever it means). 
 
 
DS’ file- / folder- name convention:
 
Folder name:
PI name_Experiment ID_Magnet system-Instrument_Start date
 
      Dmitry Smirnov_P19401-E011-DC_SCM3-HRS750_02-12-2023
      Sufei Shi _none_B114-IsoPlane_02-12-2023
 
File name:
Type of the experiment: PL, Ra(man), Re(flectance), Tr(ansmittance)
Sample short name: ****
Magnetic field: ***T (or from to )
Temperature: ***K
Light source:  SC, 532nm, 785nm, …  - Power: ***mW or uW, or percentage
Central frequency / wl/energy: ***cm-1, nm, eV
Slit: value: *** um
Acq.time: ***min or sec
Objective NA: ***NA
Other: gate voltage, pressure, …
  
PL_WSe2-MoSe2_00.0T_to_05.2T_ 10K_633nm-100uW_720nm_30um_2min_0.65NA.SPE
Ra_CsPr_30T_7.2K_532nm-2mW_550cm-1_30um_3x2min_0.82NA.SPE
Re_InSe_0T_5K_SC-20%_600meV_50um_5sec_ 0.65NA_Gate Sweep -10V to +20V.SPE
