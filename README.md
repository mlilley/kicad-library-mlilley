# kicad-library-mlilley

Custom KiCad parts library

## Install

1. `mkdir -P <your-custom-library-path>` (ex: `mkdir -P /Users/mike/Documents/kicad/libraries`)
2. `git clone https://github.com/mlilley/kicad-library-mlilley.git <your-custom-library-path>/kicad-library-mlilley`
3. KiCad > Preferences > Manage Symbol Libraries > + > `mlilley`, `/Users/mike/Documents/kicad/libraries/kicad-library-mlilley/symbols/mlilley.kicad_sym` > Ok
4. KiCad > Preferences > Manage Footprint Libraries > + > `mlilley`, `/Users/mike/Documents/kicad/libraries/kicad-library-mlilley/footprints/mlilley.pretty` > Ok

## Add New Downloaded Parts

> KiCad really need to get their shit together; adding parts is a massive fail.

1. Download
2. Footprint
   1. KiCad > Tools > Edit PCB Footprints
   2. Right-click 'mlilley' library > Import Footprint 
   3. Browse to desired .kicad_mod file
3. Symbol
   1. KiCad > Tools > Edit Schematic Symbols
   2. Right-click 'mlilley' library > Import Symbol
   3. Browse to desired .kicad_sym file (or use Options > .lib if legacy symbol)
   4. Right-click symbol graphic > Symbol Properties
   5. Update footprint and prefix with 'mlilley:', to link to the correct imported footprint

## Parts

Part / Footprint

* TS5A22364DGSR / SOP50P490X110-10N

