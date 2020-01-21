# Patterns in life's use of enzymatic reaction classes across domains and levels of biological organization

Collection of jupyter notebooks which perform various tasks relevant to the enzyme project. 

**Enzyme Commission (EC) numbers:** A 4-digit numerical scheme used to classify enzymes based on the reactions they catalyze, wherein each digit represent a progressively finer classification of the enzyme. For example:

EC 1.1.1.1 = alcohol dehydrogenase, whose digits refere to the following enzyme groups:

EC 1 are oxidoreductases (enzymes involved in the transfer of electrons)
EC 1.1 are oxidoreductases acting on CH-OH electron donors
EC 1.1.1 are oxidoreductases acting on CH-OH electron donors with NAD or NADP as electron acceptors
EC 1.1.1.1 are specific instances of ECs in the 1.1.1 category

**EC 1** = oxidoreductases\
**EC 2** = transferases; involved in transferring functional groups between molecules\
**EC 3** = hydrolases; involved in cleaving bonds via hydrolysis reactions (using H2O to cleave a bond)\
**EC 4** = lyases; involved in cleaving bonds in ways other than hydroysis\
**EC 5** = isomerases; involved in the structural rearrangement of molecules\
**EC 6** = ligases; involved in the ligation (joining) of two molecules to form a larger molecule\
**EC 7*** = translocases; involved in transporting substrates across membranes\

* note that translocases are a new EC classification and few organisms/enzymes have been annotated as such

Functions include:
- processing raw organismal .json files into associated EC lists, EC dictionaries, reaction lists, and compound lists
- creating and merging processed data into core dataframes and reading them out as .csv files
- creating visualizations of the data
- subsetting data based on annotation completeness and recreating core plots from these subsets
- assessing the EC distribution of various KEGG metabolic pathways
- assessing the taxonomic distribution of the dataset

For questions or concerns, please email me at dgagler@asu.edu.
