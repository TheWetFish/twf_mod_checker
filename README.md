# twf_mod_checker
Script to check for common issues with in-development Starsector mods and provide useful feedback


Brainstormed functionality to add
referencing a ship system in ship_data.csv that did not exist (in ship_systems.csv)
malformed json
references to things that do not exist
xeno
Typoes
illegal data type
illegal input (input outside of the mandatory enumerated list)
"references to things that do not exist" & "missing mandatory fields" could be usefully broken down a lot
variant file names don't matter.  mission file names do
expected files missing (mod_info.json)
non-unique keys reused by multiple mods (mod incompatibility warning)


user usage
specify mod directory location
assume starsector-core folder from relative mod directory.  Include override in settings file to instead specify starsector-core location
