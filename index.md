# Data description

1.) The research questions that I am trying to answer involves using radiation spectroscopy data. 
My field of research is nuclear engineering and within this field, spectroscopy data is quite common.
It is essentially histogram data where counts are measured and binned versus energy. I process the 
spectroscopy data into a couple different forms. This data then aids my ability to make claims
about the material being analyzed. The type of material is the research question i am trying to 
answer. 

2.) The primary source of data will be collected using the radiation detector. The detector outputs
binary data (".bin") that needs to be processed using my custom algorithm so that it can be analyzed 
further. After the data is processed it is saved in a much smaller file called a pickle file. This type 
of file is quite common in Python programming. The data contains the spectroscopic data, again this is
essentially counts vs energy. The pickle file also contains valuable data information about HOW the data 
was processed in the algorithm, frame rate information, how long the data was acquired, the distance 
between the source and the detector as well as certified material quantities. Modeling and simulation are 
also performed in MCNP to support the claims made by the data, this data is stored as a default MCNP 
output in the form ".o" which contains a plethora of information regarding the simulation and outcome.

3.) To reiterate, the data will be captured as binary data, pickle processed data, images of the 
experimental setup, output and input files from the modeling performed, software files from the
multiple forms of processing that is performed on the data. The data covers observational, experimentally
measured, simulated, modeled AND data from software output! There will also be a large number of plots and 
images that are created using the analysis tools from my processing code. 

4.) Data is predominantly collected using a detector connected to a laptop. The laptop has software 
which extracts binary data. Accompanied to this are measured length data from source to detector. 
Again, binary data is processed using my algorithm that creates new data, pickle  data which is 
merely histogram data. Information about sources used for the detector, distances, and time 
of acquisitions are all collected by pen and paper and saved within the filenames. The pickle file
additionally contains this information. 

5.) Approximately 99% of the data collected is the binary data in terms of file storage. The data 
collected in the binary form is approximately 1 TB. The remaining data in the mentioned forms about 
combines for less than 10 GB. 

# Roles and responsibilities

1. There are many forms of data that are created in my project. These can roughly be separated into groups 
such as raw binary data, metadata in the form of processing codes, literature, presentation documentation, 
processed data in Python pickle format, computer simulation code and the results. Researcher number 2 is 
responsible for all computer simulation code and the results that he formulates. The raw binary data is
always stored on one of several 1TB external SSDs for the project, the data is then zipped and backed up
on an internal share drive. Metadata in the form of processing codes is maintained by myself and researcher
1 and is managed using Git and backed up on both work computers. The literature is all stored on the share
drive and each researcher is responsible for contributing to the pool of knowledge. The same is true for 
presentation documentation, they are managed on a share drive for everyone on the project to contribute. 
The majority of the data analysis data using the pickle formatted data are created and maintained by myself
and stored on a work computer and backed up on a share drive. The PI is predominantly the person responsible
for ensuring sensitive data is controlled. 

2. Sensitive data is described as data that is not yet confidential in nature, but still must not be openly
disclosed due to the privacy. This can manifest as student data, employee data etc. This essentially means 
that if the data were to be released, it could negatively affect someone's personal lives, but will likely 
not have a huge impact. My research data is sensitive due to intellectual property and by the nature of the
work being conducted. However, my data does not involve human subjects.

3. There are no legal documents binding how the research data is managed except for the stipulation that we 
are unable to share any form of the data or results unless it is reviewed by HQ. The National Nuclear Security
Administration (NNSA) under the Department of Energy (DOE) funds our research. For this project there are
no data management requirements. There are no contracts or disclosure agreements that affect me other than
the aforementioned requirement to not share data or results that applies to the entire project. 

# Data standards and metadata

1.) For radiation spectroscopy there are certain metadata standards surrounding
data acquisition conditions. The metadata allows readers to be able to replicate
what the researchers show in their results. For example, the source-detector 
distance is typically given, the source activity, acquisition time, the detector 
performance in terms of resolution, efficiency and energy range. These standards
are typical in radiation spectroscopy within the field of nuclear science and engineering.
Some software will have these types of metadata input and will record them in
a 'Readme.txt' file with specifics on the data acquisition.
 
2.) The data documentation plan I constructed consisted of recording the source-
detector distance, the claimed source enrichment, and pictures of the setup. I
did not have direct access to knowing the source activity as it is not extremely
applicable to my measurements. However, the detector performance is very-well documented 
in previous research that is recorded in the forms of plots/figures, tables, and online
transcripts on a shared project page. Other forms of data that are generated in my 
research include simulation results and processed data. The simulations have an
input file that is commented so the reader can understand what each line represents 
and the output files are large and automatically generated through MCNP, the simulation
program. Metadata standards are therefore good for some of my data management, but 
does not fit for others. 

3.) Attached is the data summary created for the data about my thesis. The data has 5 
columns consisting of the sample ID, the date/time of acquisition start, the enrichment, 
the source-detector distance in inches, and lastly the acquisition time. This includes
all the necessary information about how the raw binary data was acquired. 

# Storage and security

# Access and data sharing

# Archiving and preservation

Repository with source code [here](https://github.com/clarallebot/GRAD521_DMPtemplate)
