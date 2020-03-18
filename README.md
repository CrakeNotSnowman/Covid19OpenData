# Covid-19 Data Sources

[Work In Progress]

Here is a curated list of data on the Covid-19 outbreak. This includes genetic sequences, geospatial data of where the outbreak is, protein models, and more. 

Associated with these will be python notebooks demonstrating how to bring the data into python to make it easier to perform data science while reducing the time spent searching for data to work with. 

The goal of this project is to reduce the barrier to entry to different facets of bioinformatics, and to compile a quick reference sheet for various data used in ongoing research. If using this data, please be mindful of the possible strain on computer systems, and avoid downloading information from a primary source in an automated fashion if a secondary source or mirror is available. 

## Literature
 - [Kaggle Text Mining](https://www.kaggle.com/allen-institute-for-ai/CORD-19-research-challenge)

 - [CORD-19](https://pages.semanticscholar.org/coronavirus-research) (CORD-19 is the text database the kaggle competition is built off of)


## Population Modeling
- [From Hum Data](https://data.humdata.org/dataset/novel-coronavirus-2019-ncov-cases)
- [Johns Hopikins University CSSE](https://github.com/CSSEGISandData/COVID-19)
- [Modeling the Spatial Spread of Infection Diseases in the US-Wolfram Notebook](https://community.wolfram.com/groups/-/m/t/1889072) (And associated [video](https://www.twitch.tv/videos/569303364))


## Nucleotide Sequences
This data is explored in notebooks located in the `full_genomic_seqs` directory.

### NCBI Data Hub
- [NCBI Severe acute respiratory syndrome coronavirus 2 data hub](https://www.ncbi.nlm.nih.gov/labs/virus/vssi/#/virus?SeqType_s=Nucleotide&VirusLineage_ss=Wuhan%20seafood%20market%20pneumonia%20virus,%20taxid:2697049)

This is a collection of data in GenBank and the Sequence Read Archive (SRA) tied to SARS-CoV-2. 

From here you can download the table data as a yaml, or 

### SRA

- [Sequence Read Archive](https://trace.ncbi.nlm.nih.gov/Traces/study/?acc=SRR10903401%2CSRR10903402%2CSRR10902284%2CSRR10948474%2CSRR10948550%2CSRR10971381%2CSRR11092058%2CSRR11092057%2CSRR11092056%2CSRR11092064%2CSRR11085797%2CSRR11085737%2CSRR11085740%2CSRR11085733%2CSRR11085736%2CSRR11085738%2CSRR11085741%2CSRR11140744%2CSRR11140745%2CSRR11140749%2CSRR11140748%2CSRR11140747%2CSRR11140746%2CSRR11140751%2CSRR11140750%2CSRR11177792%2CSRR11241254%2CSRR11241255%2CSRR11247075%2CSRR11247076%2CSRR11247077%2CSRR11247078%2CSRR11267811%2CSRR11278090%2CSRR11278091%2CSRR11278092%2CSRR11278164%2CSRR11278165%2CSRR11278166%2CSRR11278167%2CSRR11278168&o=acc_s%3Aa)

(To update this download link: Follow [this link](https://www.ncbi.nlm.nih.gov/genbank/sars-cov-2-seqs/) and scroll down to "SRA Sequences" header, and follow the link on 'SRA' at the end of, "View and download next-generation sequencing runs from SRA." )

### Downloads

## Protein 

### Protein Models

- http://www.rcsb.org/news?year=2020&article=5e3c4bcba5007a04a313edcc

- https://www.ebi.ac.uk/pdbe/entry/emdb/EMD-21374

## CT/Xray Imaging
- [XRay Dataset](https://github.com/ieee8023/covid-chestxray-dataset)



# Comparative
Provided below here are links to similar data
## SARS And MERS

## Influenza 

## Betacorona virus


# Useful Programs
 - [PyMOL (Open Source Version)](https://github.com/schrodinger/pymol-open-source/)
 

# Other

## 3D Printed Supplies
 - [Open Source COVID19 Medical Supplies](https://www.facebook.com/groups/670932227050506) **THESE ARE NOT VERIFIED**: There's less oversight and ample room for misinformation about the success of some of these builds. But I felt that (with disgression) this belonged here. Please take all designs here with a grain of salt, and don't trust them blindly. 