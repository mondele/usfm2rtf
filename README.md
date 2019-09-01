# usfm2rtf
Creates "pretty" rtf output from USFM files

# Initial version 0.1
   Just a clone of v. 0.5 of usfm2html. I'm starting this program to try to add footnotes to the output. Since HTML doesn't 
   really support footnotes, I thought I would try messing about with rtf.

# Changes in v. 0.5:
   Added code to ignore Strong's numbers, etc., from USFM 3

# Changes in v. 0.4:
   Removed `<!--NewPage-->` comments. These were causing issues printing from LibreOffice,
   but didn't seem to cause page breaks as intended.

# Changes in v. 0.3:
   Correctly deals with UTF-8 files that otherwise may not display correctly.

# Changes in v. 0.2:
   Adding/changing code to deal with Bahasa USFM files

  Usage python3 usfm2html.py <path to USFM file>

 The output of this command can be run through html2ps and then ps2pdf in order to produce pdf output.
 Please note that any errors in the USFM will likely produce formatting errors in the HTML, and thus in the PDF.
