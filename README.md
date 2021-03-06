# bloodSampleImageAnalysis

The project is about developing a simple, reliable and cost-effective testing platform for detection of certain types of biomarkers in blood samples by taking images from a smart phone camera.

Such a project will be of great importance to the community. Detecting cancer biomarkers from a drop of blood reliably and quickly will improve health-care systems. Such a system will make testing easier and deliver results very quickly.

Also, if the application can display messages in accordance with the measurements, the user need not be a practitioner of medicine or a trained professional. By following simple instructions anyone can obtain analysis on a drop of blood in a cost-effective manner.

This was done as a part of Helikar Lab preliminary proposal for Google Summer of Code 2015.
(Did not get accepted)

#File descriptions

-Run the main.cpp to call functions.

-measureVolume.cpp detects blobs and calculates volume (in terms of pixel intensity)

-calcMuSigma.cpp returns mean and std. deviation of given data

-Normalize.cpp scales the volume to [0,1] interval

-header.h links all the function files together

#images
[Link to testImage: https://cloud.githubusercontent.com/assets/8938083/6871016/c0309fb2-d4c5-11e4-9045-dfad639e270c.jpg]

[Link to sample output (running console): https://cloud.githubusercontent.com/assets/8938083/6873090/c90c7c92-d4d3-11e4-9c57-b8126717c12a.jpg]

[Link to processed image (grayscale|marked blobs): https://cloud.githubusercontent.com/assets/8938083/6873123/0563aa94-d4d4-11e4-8ba8-fd0387b2a57b.jpg]
