# Intellipark-Python-Analytics-for-Data-Analysis
Intellipark Python Analytics for Data Analysis

# Intellipark-Analytics
For fleet and endurnace testing system level analysis, based on the asam-mdf standard.

This script decodes Intellipark signals using the CSS Electronics Python API, then identifies events of interest.
The current implementation of events.py looks for the following:

- Tractor park & unpark
- Trailer park & unpark
- Bobtail activation
- Anti-rollaway triggered by interlocks

Found events are then tallied into a PDF 

!! Note: event detection does not yet include failure mode analysis !!

