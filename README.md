# IsSheReady.sh

PROG:
		DX2's Pre Installation Checker & Prepper
		( I know!... I really need to work on my app/script 
		names!)
LANG:
		BASH

CALL:
		This script is called everytime a new 66MHz script 
		is being insalled to check and see if the system is 
		still set up the same way, and using the same 
		shortcuts and directory structure.

INST:
		execute the INSTALL.sh script

DESC:
	CHECKER:
		In sequence, it will
			- check to see if "$BOOEYSAYS" exists or not
				- also:	- $BOOEYSBIN
							- $BOOEYSBACKUPS
							- $BOOEYSFILES
							
			- Use the functions to check if tye DIRs exists

	PREPPER:
		- If functions doesn't exist, they will be created 
		and set up to point to their asskgned DIR.		
		- Use the function's name to create the 
		directories.
		- Create the .66mhz_aliases file

		- give the user the option to clone repos
		
# Booey-s-Typo-Fuxor-er
