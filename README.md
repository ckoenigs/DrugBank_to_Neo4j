# DrugBank_to_Neo4j
This integrates all open source data of DrugBank into Neo4j.

This integrated DrugBank (https://www.drugbank.ca/releases/latest) into Neo4j, but first the DrugBank data are formed into tsv file with use of https://github.com/dhimmel/drugbank/blob/gh-pages/parse.ipynb
with some changes, so that also more properties and relationships are extracted. The result are multiple tsv files and not only one.

After extract the information of the xml file the information must be combined with the information from the other drugbank files. Also, the targets are validated with the uniprot identigfier ().
