# Readme

## Links

[Team Neural Network Github Repo](https://github.com/DiscoveryDNA/team_neural_network)
[Google Drive](https://drive.google.com/drive/folders/19LV8QSPFbsEvglt785RUDKcxHoOiQ5rX)

## Files

- alignment_VT61209.fa - fasta file of nucleotide alignment across 24 species.
- raw_VT61209.fa - raw sequences
- bcd
	- bcd_FlyReg.fm - the occurance of each letter in TFBS
	- bcd_FlyReg.png - What the Postion Weight Matrix of BCD Looks like
- occurance_bcd_VT61209.fa.csv - Using program to map presence of BCD across VT61209
- kvonClassification  - different ways to classifcy each enhancer region's function
	- classification_table3_21Aug2018.csv
	- classification_table2_24July2018.csv
	- classification_table1_24July2018.csv


## Understanding sequence ID

Example Fasta header:

`VT0847|1|MEMB005B|-|2607`

- VT0847: Region ID
- 1: positive presence of expression 
- MEMB005B: species ID
- -: read from the negative strand
- 2607: length of sequence in bp