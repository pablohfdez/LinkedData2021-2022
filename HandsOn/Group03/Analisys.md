# Analysis.html

**Hands-on assignment 2 - Summary of our ontology**

The Publisher of our datasets is the Ayuntamiento de Madrid and it’s rightsholders the Dirección General de Servicios de Limpieza y Residuos. We analyzed it’s license and it has the following restrinctions:

1.	It is forbidden to distort the meaning of the information.
2.	The source of the documents to be reused must be cited. This appointment may be made as follows: "Origin of the data: Madrid City Council (or, where appropriate, administrative body, body or entity in question)"
3.	The date of the last update of the documents to be reused must be mentioned, as long as it was included in the original document.
4.	It may not be indicated, implied or suggested that the Madrid City Council participates, sponsors or supports the reuse that is carried out with the information.
5.	The metadata on the update date and the applicable reuse conditions included, where appropriate, in the document made available for reuse must be kept, not altered or deleted.
6.	In the case of anonymized information for the protection of personal data or other reasons, it is expressly forbidden to carry out tasks of re-identification of people from this data and other possible, past, current or future sources of data and information.

Our potential license is CC BY-NC-SA 4.0 International, because we think it adapts better our ideas, in which everyone should be able to use our work without a commercial intention.

We have two datasets: contenedoresVarios.csv and contenedoresRopa.csv, which have 49685 and 758 rows respectively. That means we have in total 50443 containers and each of them have features like identificatory, address, etc. After analyzing both of it, we choose those features that both of them have and  are useful for our project.
These are the following features:
- Type: type of the containers, like organic, glass, cloths…
- Type of tracks: for example, street, avenue…
- Name: name of the streets, avenues…
- Number: number of the street, avenue…
- District: designation of the district
- Latitude: latitude where the container is (The value is between 40.34 -- 40.52, in decimal notation). 
- Longitude: longitude where the container is (The value is between -3.78 -- -3.57, in decimal notation).

The domain that we choosed is http://findmycontainer.es/ + Path : lcc/ + ontology/ or resource/
To understand our ontology, we uploaded a schema of it to give a visual representation of it.
