# This is a DMP repository for the project Nightbot.

Context: (Response to assignment DMP Part 1)
DMP Part 1: By Dustin Kasparek

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




