# Workshop Computational access to digital collections - University of Strathclyde

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/hibernator11/workshop-notebooks-scotland/HEAD)

This is a colletion of Jupyter Notebooks used for a workshop in collaboration with the [University of Strathclyde, MSc Information and Library Studies, Library Technology and Systems](https://www.strath.ac.uk/courses/postgraduatetaught/informationlibrarystudies).

<img width="30%" src="https://www.strath.ac.uk/media/1newwebsite/webteam/logos/crest-jubilee-390x60.svg">

### Hutton Drawings metadata dataset - Data Foundry - National Library of Scotland

- Dataset: [Hutton Drawings](https://data.nls.uk/data/metadata-collections/hutton-drawings/)
- Format: MARCXML
- Extraction process (to CSV): [MARC-DataExtraction-Hutton.ipynb](https://nbviewer.org/github/hibernator11/workshop-notebooks-scotland/blob/main/notebooks/MARC-DataExtraction-Hutton.ipynb)
- Analysis: [ExploringCSV-Hutton.ipynb](https://nbviewer.org/github/hibernator11/workshop-notebooks-scotland/blob/main/notebooks/ExploringCSV-Hutton.ipynb)
- Method: [map visualisation based on Wikidata](https://w.wiki/9Fde)

### A Medical History of British India digitised dataset - Data Foundry - National Library of Scotland

- Dataset: [A Medical History of British India](https://data.nls.uk/data/digitised-collections/a-medical-history-of-british-india/)
- Format: Plain text (TXT)
- Analysis: [Exploring-Medical-History-of-British-India.ipynb](https://nbviewer.org/github/hibernator11/workshop-notebooks-scotland/blob/main/notebooks/Exploring-Medical-History-of-British-India.ipynb)
- Method: Natural Language Processing and Named-Entity Recognition

### Biblioteca Virtual Miguel de Cervantes dataset - Linked Open Data - Wikidata

- Dataset: [Biblioteca Virtual Miguel de Cervantes](https://data.cervantesvirtual.com/datos-enlazados)
- Format: RDF (LOD)
- SPARQL query (BVMC and Wikidata): [MARC-DataExtraction.ipynb](https://nbviewer.org/github/hibernator11/workshop-notebooks-scotland/blob/main/notebooks/LinkedOpenData-BVMC.ipynb)
- Method: [map visualisation based on Wikidata](https://w.wiki/9FwJ)

### Datasets

The folder input contains a list of datasets provided by:
- [Data Foundry](https://data.nls.uk/) - National Library of Scotland
- [Chronicling America](https://chroniclingamerica.loc.gov/) - Library of Congress
- [Biblioteca Virtual Miguel de Cervantes](https://data.cervantesvirtual.com)
- [Wikidata](https://www.wikidata.org)

### Acknowledgments
This work has been possible thanks to many researchers and initiatives. First of all, I would like to thank Milena Dobreva for inviting me to give this workshop. This work would not have been possible without the help and inspiration of the [International GLAM Labs Community](glamlabs.io), the [Collections as data](https://collectionsasdata.github.io/) initiative, the [National Library of Scotland](https://data.nls.uk/), the [GLAM Workbench](https://glam-workbench.net/), the [Biblioteca Virtual Miguel de Cervantes](https://data.cervantesvirtual.com/) at the University of Alicante, [DARIAH-EU](https://www.dariah.eu/) and [Europeana Research](https://pro.europeana.eu/page/research).

### Licence
<a rel="license" href="http://creativecommons.org/licenses/by/4.0/"><img alt="Licence Creative Commons" style="border-width:0" src="https://i.creativecommons.org/l/by/4.0/80x15.png" /></a><br />Content is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by/4.0/">Creative Commons Attribution 4.0 International license</a>.

Please, note that the datasets used in this project have separate licences.

### References
- https://data.nls.uk/projects/the-national-librarians-research-fellowship-in-digital-scholarship-2022-23/
- https://glam-workbench.net/
- https://github.com/hibernator11/notebook-EADH-2021-workshop
- Candela, G., Chambers, S., & Sherratt, T. (2023). An approach to assess the quality of Jupyter projects published by GLAM institutions. Journal of the Association for Information Science and Technology, 74(13), 1550–1564. https://doi.org/10.1002/asi.24835
- Candela, G. (2023). Towards a semantic approach in GLAM Labs: The case of the Data Foundry at the National Library of Scotland. Journal of Information Science. https://doi.org/10.1177/01655515231174386
- Candela, G. et al. (2018). Migration of a library catalogue into RDA linked open data. Semantic Web 9(4): 481-491. https://doi.org/10.3233/SW-170274
- Candela, G. et al. (2022). Reusing digital collections from GLAM institutions. Journal of Information Science. 48(2): 251-267. https://doi.org/10.1177/0165551520950246
- Candela, G., Gabriëls, N., Chambers, S., Dobreva, M., Ames, S., Ferriter, M., Fitzgerald, N., Harbo, V., Hofmann, K., Holownia, O., Irollo, A., Mahey, M., Manchester, E., Pham, T.-A., Potter, A., & Van Keer, E. (2023). A checklist to publish collections as data in GLAM institutions. Global Knowledge, Memory and Communication. Advance online publication. https://doi.org/10.1108/GKMC-06-2023-0195
- https://github.com/hibernator11/hdh-compartir-pantalla-2023

