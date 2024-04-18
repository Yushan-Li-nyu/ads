Applied Data Science Academic Project 2024

**BELOW CONTENTS MIGHT BE DELETED IN FUTURE!**
**JUST FOR US TO UNDERSTAND THE STRUCTURE!**
**PLEASE READ CAREFULLY!**


# Format and Rules of files:
1. understand the structure of files, standardize procedure
2. build own branch, and merge to main everytime. DO NOT render on main directly
3. name the files as concise as possible, also, all lowercase, connect words with '_' e.g. 'data_processing' instead of 'dataProcessing'

# Structure of files:
bin/ # currently nothing inside, but might be used for easy click to run codes in the future

data/
----raw/
--------original zipcode shapefiles
--------NYPD arrest data & dictionary
----processed_data/
--------zipcode_bk # (both shapefiles and csv files)

results/ # currently empty, obviously, we have no results yet ":)"

src/ # any editable codes
----data_processing/
--------crime.ipynb
--------lighting.ipynb
--------zipcode_cleaning.ipynb
----models/ # currently empty
----visualization/ # might be combined with models

README.md
