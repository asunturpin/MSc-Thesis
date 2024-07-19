# MSc-Thesis
In this repository, information related to my MSc-Thesis named "An Integrative Method for Orthologous Gene Retrieval: Combining InParanoid and OMA Databases" can be found:

## Abstract
This Master's thesis focuses on developing a computational method to facilitate the retrieval of orthologous genes across species. Orthologous genes, which are crucial for comparative genomics and biomedical research, are dispersed across heterogeneous databases, making interoperability a challenge. This project aligns with the efforts of the Quest for Orthologs consortium, which aims to standardize orthologous information using the ORTH ontology.
The method integrates data from two significant orthology databases, InParanoid and OMA, using SPARQL queries on RDF repositories. By automating the query process and introducing a reliability scoring system based on data curation status and occurrences count across the databases, this method enhances the accessibility and usability of orthologous data for researchers.
The results, exemplified by the retrieval of orthologous proteins to P53 gene of Homo sapiens from Mus musculus, among other IDs, illustrate the method's efficacy in integrating data from InParanoid and OMA. The method organizes this information into a dataframe that includes the UniProt IDs, protein curation status, occurrence counts, and reliability scores.

## Tools
* Use of standarized semantic web information such as ORTH ontology.
* Manage GraphDB as a repository to query InParanoid database in RDF format. 
* Use SPARQL language to make queries from OMA enpoint and InParanoid GraphDB repository.
* Employ platforms such as Jupyter Notebook to write Python code in order to develop the final method.

##  Available information
* The developed code for testing the method is contained in a notebook named 'Unified_method_P04637'. It can be tested with other UniProt IDs or species.
* The notebook created for the addition of other examples for the Results section is named Unified_method_UniprotID_examples.
* Libraries and developed functions are contained in another notebook under the name 'libraries_functions'. It is necessary to download this file to test the other two notebook.
* The memory itself is also collected in PDF format, under the name 'Turpin_Gomez_Asuncion_MScThesis'.

## Contact
Please, for any question, collaboration or suggestion contact to this author via email [asunturping@gmail.com].
