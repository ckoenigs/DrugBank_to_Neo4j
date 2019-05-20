# DrugBank_to_Neo4j
This integrates all open source data of DrugBank into Neo4j.

This integrated DrugBank (https://www.drugbank.ca/releases/latest) into Neo4j, but first the DrugBank data are formed into tsv file with use of https://github.com/dhimmel/drugbank/blob/gh-pages/parse.ipynb
with some changes, so that also more properties and relationships are extracted. The results are multiple tsv files and not only one.

After extract the information of the XML file the information must be combined with the information from the other DrugBank files. Also, the targets are validated with the UniProt identifier (https://github.com/ckoenigs/UniProt_to_Neo4j). The program need as information where the other DrugBank files are. Also, the generated csv files from the other program are in a dictionary drugbank.
