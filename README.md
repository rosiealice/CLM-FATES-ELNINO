# CLM-FATES-ELNINO

Workflow for FATES ENSO runs. 

1. Download clone of FATES
git clone https://github.com/escomp/ctsm ctsm_may22
cd ctsm_may22
./manage_externals/checkout_externals 
cd cime/scripts

2. Make Case
 ./create_newcase --res f09_g16 --compset I2000Clm50Fates  --case FATES_1deg_v1 --run-unsupported 
./case.setup
./case.build


