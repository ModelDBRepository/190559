Model files in the NEURON simulation environment from the paper

"The possible consequences for cognitive functions of
external electric ﬁelds at power line frequency on
hippocampal CA1 pyramidal neurons" Rosanna Migliore, Giada De
Simone, Xavier Leinekugel and  Michele Migliore. European Journal of Neuroscience (2016),
doi:10.1111/ejn.13325 

Usage:
------
Auto-launch from ModelDB or:
Compile the mod files with mknrndll (mswin or graphical mac) or
nrnivmodl (unix/linux)).  Start the simulation by (unix/linux) typing
on the command line:
nrngui mosinit.hoc

or (mac os x) drag and dropping the mosinit.hoc file on the nrngui
icon or (mswin) double clicking on the mosinit.hoc file.  

After selecting the external electric field amplitude (no field or 40 V/m at 50 Hz)
click on "run simulation" to reproduce the somatic membrane potential as in fig1B.hoc.  

Depending on the processor and round-off errors, spike times may be different from what shown in the paper.


Questions on how to use this model should be directed to
rosanna.migliore@cnr.it