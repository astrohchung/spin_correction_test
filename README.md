## Note:
- 'kinematic-corrections.py' from commit 'fead868' of https://github.com/kateharborne/kinematic_corrections is used for this code.
- 'mg_lambdaR_e_calc.py' from commit '0774f16' of https://github.com/marktgraham/lambdaR_e_calc is used for this code

## How to run this example:

- git clone https://github.com/astrohchung/spin_correction_test
- enter the directory
- git submodule add https://github.com/kateharborne/kinematic_corrections
- change the permission of './kinematic_corrections/kinematic-corrections.py' file to executable.
- cd kinematic_corrections
- chmod 777 kinematic-corrections.py

- git submodule add https://github.com/marktgraham/lambdaR_e_calc
- cp ./lambdaR_e_calc/mg_lambdaR_e_calc.py g18corr.py
- enter g18corr.py and commenting out line 5: 'from cap_display_pixels import display_pixels'

- open and run spin_correction_test.ipynb

