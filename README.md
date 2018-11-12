# write_all_complexes.py
Modified write_all_complexes.py of AutodockTools

## Overview
write_all_complexes.py in AutodockTools has a bug about output file names.
Official write_all_complexes.py outputs files numbered 0-255, don't correspond to the number (1-256) written in an Autodock docking log file.
My write_all_complexes.py writes correct numbered files (1-256).
