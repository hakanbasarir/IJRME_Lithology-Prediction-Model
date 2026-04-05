# Data Access Notice

Raw MWD data is confidential per agreement and cannot be shared publicly.

## To use your own data:
1. Format your Excel/CSV file with columns matching `template.csv`
2. Update the filename in the main script:  
   `data = pd.read_excel('your_file.xlsx')`
3. Ensure input/output column names match your dataset

## Expected schema:
| Column | Unit | Description |
|--------|------|-------------|
| `ROP` | m/h | Rate of Penetration |
| `thrust` | kN | Drill thrust force |
| `torque` | Nm | Rotational torque |
| `penetration_rate` | m/min | Instantaneous penetration |
| `mud_pressure` | bar | Flushing pressure |
| `lithology_label` | int (1-6) | Target lithology class |
