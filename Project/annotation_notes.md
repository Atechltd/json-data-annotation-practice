# Annotation Notes

## Issues Found
- Incorrect line_total calculation (400 → 500)
- Incorrect grand_total based on wrong line_total

## Fix Applied
- Recalculated line_total = quantity × unit_price
- Recalculated grand_total including tax

## QA Steps
1. Verified source values
2. Identified mismatches
3. Corrected dependent fields
4. Validated final JSON consistency
