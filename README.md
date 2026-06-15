# REGFMA1 — Droop-Controlled Grid-Forming UDM for PSS/E 33/34/35

A user-defined model (UDM) replicating the REGFM_A1 model from the 
standard PSS/E library (available natively from PSS/E 36 onwards), 
backported for compatibility with PSS/E versions 33, 34, and 35.

## Background
REGFM_A1 is a generic droop-controlled grid-forming inverter model developed by Wei Du, Pacific Northwest National Laboratory.
This implementation was developed independently from the published model specification to make the model accessible to 
PSS/E 33–35 users.

## Files
- `dll/psse33/` — DLL compiled for PSS/E 33
- `dll/psse34/` — DLL compiled for PSS/E 34  
- `dll/psse35/` — DLL compiled for PSS/E 35
- `docs/`       — User guide (CON/VAR/STATE table, example DYR entry)

## Usage
1. Copy the appropriate DLL to your PSS/E working directory
2. Add the DYRE entry as described in the user guide

## Author
Abdul Rauf

Report issues: https://github.com/abdul-npcc/REGFMA1-PSSE-UDM/issues

## Disclaimer
This model is provided as-is for research and educational purposes.

## License
MIT License
