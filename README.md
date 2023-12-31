# ChemoKB and ChemoKB-open
ChemoKB is a a knowledge graph of chemotherapy protocols. A subset of ChemoKB, named ChemoKB-open, includes only non-confidential protocols (513 out of 1,358).
These protocols have been extracted from the Pharmacy database of the Georges Pompidou Eureopean Hospital (HEGP) of the AP-HP. 

ChemoKB-open will soon be available at https://chemokb.inria.fr/, with a SPARQL endpoint.
ChemoKB-open is available for download at XX.
ChemoKB is described in more details in [1]

ChemoKB instanciates the ChemoOnto ontology [2, 3, 4].


# Reference classifications
1 - Principal indications (in terms of cancer location) of chemotherapy protocols are in **PRC_TUMOR_LOCATION.csv**. <br />
2 - ATC codes (level3) associated with drugs of chemotherapy protocols are in **PRC_ATC_LVEL3.csv**. <br />

The list of cancer locations and level3 ATC codes are in **list_of_location_and_atc3.csv**. <br />


# References
[1] Jong Ho Jhee, Alice Rogier, Dune Giraud, Emma Pinet, Brigitte Sabatier, Bastien Rance and Adrien Coulet. Representation and comparison of chemotherapy protocols with ChemoKG and graph embeddings, submitted to SWAT4HCLS 2024. <br />
[2] Rogier, A., Rance, B., Coulet, A. (2023). ChemoOnto, an ontology to qualify the course of chemotherapies. Bio-ontologies COSI 2023, Poster.  <br />
[3] ChemoOnto on the BioPortal: https://bioportal.bioontology.org/ontologies/CHO <br />
[4] ChemoOnto on GitHub: https://github.com/TeamHeka/ChemoOnto




