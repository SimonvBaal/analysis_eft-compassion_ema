# pandemic-urges-EMA

The three letter identifier for this project is ctf (Compassion, Future Thinking).

## Description
In this project we analyse the effects of compassion and episodic future thinking on the 
intensity of urges, and participants' ability to control them.
The data was collected using Ecological Momentary Assessment (aka experience 
sampling). There are 95 participants in the final sample and each participant is 
asked to report about various COVID-19 related urges in everyday life, via a 
smartphone app, called SEMA3.

We also collected some demographic data contained in the eligibility datafile,
in the raw-data folder.

## Installation
### Requirements
R 4.0.5
RStudio

### Instructions
Please download the entire folder to your computer.
Then, navigate to the folder and click on the file called "analysis_ctf.Rproj". 
The project should open in RStudio with the environment pre-loaded.

The package management for this project was made using 'renv'. This means that
when you run the following command, all the packages with the correct versions
will be loaded.
> renv::restore()

## Usage
There are three ways to start working with this project.

The first, and the easiest/fastest, is something RStudio may do for you
automatically, and that is loading the .RData file. To do this directly, one 
simply runs "load(.RData)" in the console panel. 

The second option is to run directly from the analysis.....Rmd file, which 
uses the pre-cleaned dataset.

The third option is to open the cleaning....Rmd file. Running this file 
will pull datasets from the raw-data folder and clean them for use in the 
analysis Rmarkdown file mentioned above (this file will be stored in the 
'data' subfolder).

Figures can be found in the figures subfolder, with the plots....Rmd file you
may use to recreate them.

## Support
Should you have any problems, please send an email to simon.vanbaal1@monash.edu

## Contributing
This project is not open for contributions. However, if you find a mistake,
please contact me via the email address listed above.

## Authors and acknowledgement
I wrote the code for this project myself, but I would like to thank my
collaborators for their input: Antonio Verdejo-Garcia and Jakob Hohwy.

## Project status
This project is still under development.