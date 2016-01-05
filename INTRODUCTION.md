# Introduction #

This project is the result of a collaboration between researchers of MIT,MGH and BWH. Our goal was to create a simple but useful tool to reconstruct images from list-mode data files of Monte Carlo simulations of PET acquisitions from GATE. GATE produces large ROOT files that need some post-processing (sinogram, rebinning, normalization..) to convert them into data files with the appropriate format required by some available reconstruction codes (like STIR).

Our approach was different. We wanted to use the Origin Ensemble (OE) algorithm proposed by A. Sitek, to reconstruct directly from the ROOT files. The algorithm has some properties, like its simplicity, that are really useful for a project like this.
The code has a few basic options, but it can be easily adapted and incorporate new options.


# Details #

Add your content here.  Format your content with:
  * Text in **bold** or _italic_
  * Headings, paragraphs, and lists
  * Automatic links to other wiki pages