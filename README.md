# cr_b2n_preFactor
Translation of the gsmcalibtarget step (phase calibration on the gsm skymodel) from the MASTER branch.

- parset "b2n_gsmcal_QUICK_Pre-Facet-Cal.parset" 

Just a couple of steps for the test. Runs without crashing, but its correctness is not verified yet. 

- parset "b2n_gsmcal_Pre-Facet-Cal.parset"

The translation in the whole parset. SHOULD run without crashing (testing).


Main changes:

-> skymodel for the target field: it has to be a sourcedb file to run NDPPP

-> adapting the maps


