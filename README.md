# PDB_DSSP_Secondary_Structure
Handle DSSP secondary structure on a PDB file.

The code is in Python and Biopython package needs to be imported
You can get the DSSP columns "chain" and "secondary structure" in a two-column dataframe and then easily extract all the requested information.

### Important:
To get the information, you need to have the .pdb file of the protein (Download from RCSB.org)
and choose the protein name in the code in the format " ****.pdb "

You may also find three useful functions

#### 1. getNumberAndNamesOfChains():
Gives the number of the chains in the protein and their names (RCSB.org)

#### 2. getSS():
Returns a dataframe where each colums is a protein chain having the secondary structure information.

#### 3. getSSCount():
Returns a table in a dataframe format, with the secondary structure (ss) presence in the
whole protein with two options: real count and %presence.


The example shown in the jupyter notebook is for protein 1ADO.
