# Data Source Note

## File
Phnom_Penh_NASA_POWER_2015_2025_source_table.csv

## Source
NASA POWER monthly API (presumed parameter: PRECTOTCORR_SUM)
Approximate location: 11.56° N, 104.93° E (Phnom Penh, Cambodia)

## Important limitations
- The provided CSV contains ONLY the numeric table (YEAR + 12 months + ANN).
- The NASA parameter name, spatial metadata, and UNITS header are NOT included.
- The unit is presumed to be millimeters but CANNOT be confirmed from the table alone.
- This is a GRIDDED model/reanalysis product, not an on-site rain gauge.
- Confirm parameter, location, and units from the full NASA download header before publication.

## References
- API docs: https://power.larc.nasa.gov/docs/services/api/temporal/monthly/
- Parameter dictionary: https://power.larc.nasa.gov/docs/tutorials/parameters/
