# Beamer Templates
Beamer templates for producing presentations in LaTeX that match ATI house style.
## Installation
Download the files from the template directory, using the "clone or download" button located to the upper left. Copy the \*.sty files to the corresponding subfolders in your Beamer themes directory:
 - *beamerthemeTuring.sty* should be copied to the *themes* subfolder
 - *beamerouterthemeTuring* should be copied to the *outerthemes* subfolder
 - *beamerinnerthemeTuring* should be copied to the *innerthemes* subfolder
 - *beamercolorthemeTuring* should be copied to the *colorthemes* subfolder
 
## Usage
- Copy the *Turing-skeleton-example.tex* file as the base for your presentation. You should copy the *images* folder with the ATI logos to the same location as *Turing-skeleton-example.tex*.
- Choose the light or dark theme by retaining either \\usetheme{TuringLight} or \usetheme{TuringDark} (make sure to uncomment your chosen theme if necessary by removing any leading "%" at the start of the line. Delete or comment out the other theme (you can comment a line out by placing a "%" at the start of the line).
- Set the presentation title, subtitle and date within the \\title, \\subtitle and \\date fields. Note that the \\author field is not used in the ATI template.
- Create your text-based slides following either the single-column or double-column page example skeletons.
