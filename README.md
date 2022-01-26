# git-hook-check-copyright

The script will check the year in the format ***YYYY*** or in the format 
***YYYY - YYYY*** in the first 3 lines **added** (A), **changed** (M), **renamed** (R) and **copied** (C) 
files added to the index. 
If the year does not match the current one, it will correct this by adding/changing to current year.

1. Put the file `pre-commit` to .ssh/hooks folder of your repository
2. Add them execution rights `$ chmod +x pre-commit`
