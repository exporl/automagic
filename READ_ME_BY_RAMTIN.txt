The Automagic Toolbox included here is the "development" branch.

In addition, I included the possibility to choose interval thresholds for flagging artefactual components when performing ICLabel (the implementation on Automagic currently only allows to set a exclusion/inclusion > OR < threshold). Although my fix works, the automagic development tool will improve this in a more elegant fashion soon, which will be fully compatible with the GUI.

- \preprocessing\performICLabel modified to consider interval thresholds

- \settingsGUI.m replace string to doubles for ICLabel inputs (around line 530)

For any clarification please contact me at: ramtin.mehraram@kuleuven.be