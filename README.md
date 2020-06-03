# pisound-puredatapatches
pisound-puredatapatches is my humble contribution to the pi-sound ecosystem.


## monomearp
is an adaptaion of the arp-patch to use the monome as a sequencer.
It makles use of the excellent https://github.com/boqs/pd-grid which you need to compile on the pi yourself (easy)
you'll also need serialosc running in the background
watch out for this https://github.com/monome/serialosc/issues/51

### setup
expects a midi clock on the pisound DIN midi in, so the sequencer starts moving


### control
set the seq using the blokas control app
seq 0-4 focusses one of the 5 sequencers
seqXdiv is a sperate clock divider for each seq
see pd help files to understand how [step] works
more info here https://monome.org/docs/aleph/ops/ under the step section
