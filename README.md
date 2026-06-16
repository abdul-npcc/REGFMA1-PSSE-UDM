# REGFMA1 — Droop-Controlled Grid-Forming UDM for PSS/E 33/34/35

A user-defined model (UDM) replicating the WECC REGFM_A1 model from the 
standard PSS/E library (available natively from PSS/E 36 onwards), 
backported for compatibility with PSS/E versions 33, 34, and 35.

## Background
REGFM_A1 is a generic droop-controlled grid-forming inverter model developed by Wei Du, Pacific Northwest National Laboratory.
This implementation was developed independently from the published model specification to make the model accessible to 
PSS/E 33–35 users.

## Benchmark Results
Voltage step down test

<img width="4770" height="1743" alt="STATES_Compare_10" src="https://github.com/user-attachments/assets/f65be0ef-b9f1-4174-8959-62a382db5447" />

<img width="4770" height="1743" alt="VARS_Compare_10" src="https://github.com/user-attachments/assets/4f9b1d42-2176-4533-843d-41b9a531226d" />


## Files
- `dll/psse33/` — DLL compiled for PSS/E 33
- `dll/psse34/` — DLL compiled for PSS/E 34  
- `dll/psse35/` — DLL compiled for PSS/E 35
- `docs/`       — User guide

## Usage
1. Copy the appropriate DLL to your PSS/E working directory
2. Add the DYR entry as described in the user guide. Sample .dyr files can also be found in the dll folders. 

## Author
Abdul Rauf

Report issues: https://github.com/abdul-npcc/REGFMA1-PSSE-UDM/issues

## Disclaimer
This model is provided as-is for research and educational purposes.

## License
MIT License
