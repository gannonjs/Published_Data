# This folder is designed to store a public database of UDG spectroscopic data. 

It represents an extension of the spectroscopic velocity dispersins listed in Table A1 from:

Gannon J.~S., Forbes D.~A., Brodie J.~P., Romanowsky A.~J., Couch W.~J., Ferr{\'e}-Mateu A., 2023, MNRAS, 518, 3653. doi:10.1093/mnras/stac3264

And an extension of the spectroscopic stellar population information listed between Tables 1 and 2 in:

Ferr{\'e}-Mateu A., Gannon J.~S., Forbes D.~A., Buzzo M. L., Romanowsky A.~J., Brodie J.~P., MNRAS, Submittied.

It is requested users of this database please cite the above work.

### Please note that the galaxies DF44 and DFX1 are currently repeated with the two disagreeing globular cluster counts. If not using this table to compare to globular cluster counts one entry should be deleted.

It contains:
1) This Readme
2) bibiography.txt - A bibliography of bibtex entries for the source material
3) column_labels.txt - A list of the columns and their units
4) individual_galaxy_notes.md - A list of each galaxy included in the compilation including notes on where the data comes from and considerations made when selecting the inclusions.
5) udg_data.csv - a csv file containing the UDG database. The first row re-lists the columns.

To be included in the database galaxies are required to have:
1) A half-light radius > 1.5 kpc (note this is semi-major while the table lists circularised).
2) An average V-band surface brightness < \mu_V >)_e within the half-light radius greater than 24.7 mag/ arcsec^2.
3) A spectroscopic velocity dispersion and/or spectroscopic stellar population information (mass weighted age/mass weighted metallicity [Z/H])

Cuts 1) and 2) are designed based on the van Dokkum et al. (2015) UDG definition but here we choose an average surface brightness cut to not bias ourselves against nucleated UDGs.

To the best of my knowledge I have included all galaxies published in the literature that meet these criteria. I do not pretend to be omniscient however so if I've missed your work (sorry) please contact me via the email below to fix this.

For those interested in seeing a version history of changes please consult the git comments.

If you have any questions with the data, wish to have me include your galaxy in the database, or would like to disagree with me about my choices made please contact me via email:

jonah.gannon@gmail.com

June 2023
