# Description of data:

The primary source of data will be collected using a radiation detector. The detector outputs
binary data (".bin") that needs to be processed using my custom algorithm so that it can be analyzed 
further. After the data is processed it is saved in a much smaller file called a pickle file. This type 
of file is quite common in Python programming. The pickle file also contains valuable metadata information 
about how the data was processed in the algorithm, frame rate information, how long the data was acquired, 
the distance between the source and the detector as well as certified material quantities. Modeling and
simulation are also generated in monte-carlo n-particle (MCNP) to support the claims made by the data, 
this data is stored as a default MCNP output in the form ".o" which contains a plethora of information 
regarding the simulation and outcome. 

To reiterate, the data will be captured as binary data, pickle processed data, images of the 
experimental setup, output and input files from the modeling performed, software files from the
multiple forms of processing that is performed on the data. Additionally, data will be created
in the form of documentation and presentations from Word and Powerpoint. The data covers observational, 
experimentally measured, simulated, modeled AND data from software output! There will also be a
large number of plots and images that are created using the analysis tools from my processing code.
In summation, the data types for this project will consist of .bin, .txt, .o, .pkl, .png, .pdf, 
.docx, .pptx and .p files. 

Data is predominantly collected using a detector connected to a laptop. The laptop has software 
which extracts binary data. Accompanied to this are measured length data from source to detector. 
Again, binary data is processed using my algorithm that creates new data, pickle  data which is 
merely histogram data. Information about sources used for the detector, distances, and time 
of acquisitions are all collected by pen and paper and saved within the filenames. The pickle file
additionally contains this information. 

Approximately 99% of the data collected is the binary data in terms of file storage. The data 
collected in the binary form is approximately 1 TB. The remaining data in the mentioned forms about 
combines for less than 10 GB. 

# Roles and responsibilities

The data formed from this project can roughly be separated into groups such as raw binary data, 
metadata in the form of processing codes, literature, presentation documentation, 
processed data in Python pickle format, computer simulation code and the results. Researcher number 2 is 
responsible for all priomary computer simulation code generated in MCNP and the results that he formulates. 
Researcher 2 will make decisions on how the code will be altered and be responsible for maintaining backups
as well as commenting the code so that other researchers can understand. The raw binary data is always stored 
on one of several 1TB external SSDs for the project, the data is then zipped and backed up on an internal share 
drive. Researcher number 3 is the person that will ensure that large .bin files are zipped and condensed onto 
the lab-wide project share drive.

Metadata in the form of processing codes is maintained by myself and researcher
3 and is managed using Git and backed up on both work computers and the project share. The literature is all stored
on the share drive and each researcher is responsible for contributing to the pool of knowledge. The same is true for 
presentation documentation, they are managed on a share drive for everyone on the project to contribute. 
The majority of the data analysis data using the pickle formatted data are created and maintained by myself
and stored on a work computer and backed up on a share drive. The PI is predominantly the person responsible
for ensuring sensitive data is controlled. 

There are no legal documents binding how the research data is managed except for the stipulation that we 
are unable to share any form of the data or results unless it is reviewed by the funding sponsor (NNSA). 
The National Nuclear Security Administration (NNSA) under the Department of Energy (DOE) funds our research. 
For this project there are no data management requirements. There are no contracts or disclosure agreements 
that affect me other than the aforementioned requirement to not share data or results that applies to the entire project. 
If someone on the project were to leave this would not affect data management. The PI is the primary researcher
to ensure data is managed and backed up properly. If the PI were to leave, the co-PI would then gain responsibility.

# Data standards and metadata

For the broad field of nuclear science and engineering there are certain metadata 
standards surrounding data acquisition conditions. The metadata allows readers to 
be able to replicate what the researchers show in their results. For example, the source-detector 
distance is typically given, the source activity, acquisition time, the detector 
performance in terms of resolution, efficiency and energy range. These standards
are typical in radiation spectroscopy within the field of nuclear science and engineering.
Some software will have these types of metadata input and will record them in
a 'Readme.txt' file with specifics on the data acquisition. For example, in MCNP, 
the simulation code used heavily in this field, the input file is very rigid and 
this allows readers to trust the end-results shown. MCNP is the closest thing
to a metadata standard in this field. 
 
The data documentation plan I constructed consisted of recording the source-
detector distance, the claimed source enrichment, and pictures of the setup. I
did not have direct access to knowing the source activity as it is not extremely
applicable to my measurements. However, the detector performance is very-well documented 
in my previous published research that is recorded in the forms of plots/figures, tables, and online
transcripts on a shared project page. Other forms of data that are generated in my 
research include simulation results and processed data. The simulations have an
input file that is commented so the reader can understand what each line represents 
and the output files are large and automatically generated through MCNP, the simulation
program. Metadata standards are therefore good for some of my data management, but 
does not fit for others. 

# Storage and security

The data is currently stored in many locations. Specifically, my project which is the subset of a larger project has the data stored on a work laptop, on an external SSD, and stored as a zipped file on a project share online that is remotely accessed. The data is stored as raw binary data that is either zipped up in a compact form or unzipped (~900GB). The data on the laptop and external drive will remain for an unknown period of time. The reason for this is because the data is stored on a government laptop that is contigent upon the researcher continuing work post-graduation with the laboratory. However, the data stored on the shared drive online will remain for 5 years after the project finalization. The project is set to finish in August of 2020 therefore the data will survive till August of 2025 approximately. Access to all forms of data is only allowed for authorized researchers. 

3. The analyzed data are all results of processing the binary data. This processing is easily redone therefore it's not important to backup the analyzed data. As stated above, the primary data (binary) is zipped and stored in three different locations so there are three copies. The binary data remains unchanged so it does not need to be continually backed up. The results of analysis are stored on the laptop and important results are backed up on the project share for interpretation. The network shared drive is housed and managed entirely by the pacific northwest national laboratory (PNNL). It is backed up on internal servers housed on campus. The longevity of this approach is mentioned in 2. above. 

# Sharing and preservation

1.) Yes, there are certainly factors restricting who can access my data. The research conducted is funded by the National Nuclear Security Administration (NNSA) under the Department of Energy (DOE). As such, the protocol requires that any data release in the form of raw data, publications, modeling results, effectively any product of this research must be reviewed prior to release by a derivative classifier. Therefore, no data is available to be released publicly except in the form of presentations and journal articles, both of which are heavily reviewed before approval. In other words the data (presentations and publications) are only available to those that are at the event or those who have access to the article. 

2.) This is somewhat answered in #1 above. Only presentations and publications are data that will be made available. There is no set time when these will occur as it depends on the project decisions. For example, I presented the research in the graduate research symposium at OSU and that was made available. Further, I have a published journal article on this research as of October of 2018 that is publicly available through Elsevier. Normal citation policies apply, if results from a journal article are used they should be properly cited. Within the publications/posters there are figures and tables that may be drawn from for use in other work. 

3.) The data mentioned above in "data description" are all stored on a lab-wide cloud server. These servers contain thousands of project share drives with TBs of available storage. My project currently has two shared drives on the server. After the project is finished, the project shares will remain for five years before being removed. Further, there are five, 1 TB external drives containing various raw and processed data pertaining to the project. These will be kept in the office of the PI until five years after the close of the project. The external drives contain only raw and processed data. However, the project shared drives contain a plethora of information discussed above in the form of raw data, processed data, figures, tables, meeting documents, presentation files, journal articles, referenced papers, etc.. This is mostly outlined in the data description section and encompasses the archived data files by the lab IT support. 


