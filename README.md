# eds_basics
Jupyter notebooks for basic EDS processing using hyperspy and numpy

This notebook is aimed at users who have only a small amount of experience with jupyter notebooks and hyperspy but are familiar with energy dispersive X-ray spectroscopy (EDS). In particular it's geared towards Titan and Talos users at the University of Manchester but could, with some adjustment, be used for other instruments.

The notebook covers various aspects of EDS processing: file types and importing data (at the moment this is only covered in-depth for Bruker .bcf files and Velox .emd files, with only brief text descriptions for DigitalMicrograph .dm3 and Aztec .rpl files), batch processing, plotting elemental maps, quantification and stastical measurements. There are also some extra features at the end for users to try out.

Several example datasets are included that the user can use to test the script. They should be downloaded to the same directory as the iPython notebook (or their location specified in the load function).

At the moment (24 March 2020) this is notebook is limited in scope, but further develepments will be made in the future. Additional notebooks dealing with more complex EDS analysis will also be uploaded in due course. If you find any issues or if you want to contribute please let me know.

Dan
daniel.kelly@manchester.ac.uk
