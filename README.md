**Note: Mac only.**

## Using AutoR1
1. Name R1 project 'R1.dbpr'
2. Run R1 initial setup to generate all standard views
3. Copy 'AutoR1.app', 'start.command' and 'R1.dbpr' project file to the same directory
4. Double click 'start.command'



## Overview
- Create input groups

  Groups amp channels based on their input setting (e.g A1, A2, D1, D4 ). Inputs are taken from the ArrayCalc snapshot. Required for the DS10 D1/D2 info on the overview page.

- Create SUBarray LR groups

  Adds addition sub groups for L and R sides. Required for the Meter page.

- Create fallback controls

  Adds fallback controls to all group pages and the overview page.

- Create DS info

  Enables/disables ds info (D1/D2 pri/sec readouts on Overview, channel info on Meter page)

- Remove meter view

  Removes the meter page

- Create meters view

  Creates a meter for each channel in the project grouped by the standard/ArrayCalc grouping

- Remove all views and groups

  Deletes all views and groups including those generated by R1 and everything generated by AUTOR1. Use this is if something goes wrong and R1 won't open the project.



## Notes
- templates.r2t

Load this as a template file in R1 to modify generated controls
