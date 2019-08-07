# Multi-Input-Promoters
Mathematica codes for the model fitting in "Predicting transcriptional output of synthetic multi-input promoters" by Zong, et al.


David Zong worked with three repressors, the ligands for which are ribose, trehalose, and IPTG.  
In addition, David worked with an activator, the ligand for which is arabinose. [AND gates involving arabinose use the hybrid promoter.]
There are three spreadsheets:

 (1) Single Input Gates
 (2) 2-input AND gates
 (3) 3-input AND gates

 Here is information from David about each:

SIG
  The spreadsheet is called SIGresults. Each sheet in the excel file is one replicate of one gate. 
  There are 4 gates and 3 replicates of each gate. For each sheet, the first column is the concentration of inducer in mM, 
  the second column is the mean expression normalized to beads, and the third column is the RCV. 
  The first 12 rows is the induction curve. The last 6 rows is the cross induction with the three remaining inducers in the set. 
  For example the sheet for Ara would have cross induction for IPTG, Rib, and Tre with no Ara in rows 13, 14, 15. 
  This is followed by cross induction for IPTG, Rib and Tre with max Ara in rows 15, 17, 18.
  I kept these cross inductions alphabetical, so for example if the primary inducer is IPTG, 
  then the cross inducers are Ara, Rib and Tre in that order. 

 2-INPUT AND
 The sheets on the excel document are organized by replicates. 
 The title of the sheet indicates identy and replicate of the gate. 
 For instance AraIPTG_R1 is the first replicate of the Ara IPTG gate.
 The first and second columns are the concentrations of each inducer. 
 The name of the sheet indicates which column is which inducer. 
 So for AraIPTG_R1, the first column is the concentration of Arabinose and the second column is the concentration of IPTG. 
 The 3rd and 4th columns are the mean and RCV.
 
 3-INPUT AND
 The formatting of the set is mostly the same as the 2 input set, except this time there is a third input concentration.
 Each sheet in the spreadsheet represents a slice at a concentration of trehalose. 
 This is indicated by the name of the sheet: Tre10 for 10 mM, Tre00 for 0 mM, Tre 01 for 0.1 mM.
 The first column is the concentration of arabinose in mM, the second column is the concentration of ribose in mM. 
 The 3rd and 4th are the mean and RCV of the measurement.

