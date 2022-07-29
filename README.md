# ISPF Master Class: Edit Macros
The edit macros and execs in this package are related to the
session ISPF Master Class: Edit Macros given by me on multiple
occasions at SHARE and GSE-UK conferences.

Please provide me with any suggestions and/or corrections.

Dan Dirkse
ztools.channel@gmail.com                                                      


The following files make up the package and should be maintained with
the GNU GENERAL PUBLIC LICENSE contained in the @LICENSE.TXT file.

@LICENSE.TXT - GNU GENERAL PUBLIC LICENSE
@README.TXT  - This file
BATEDIT.TXT  - Exec to call the editor in batch
BATJCL.TXT   - JCL to call BATEDIT
CHANGEIT.TXT - Example initial edit macro used by BATEDIT
COMPDSN.TXT  - Edit macro to compare data sets (called by COMPJCL)
COMPJCL.TXT  - Edit macro to compare JCL member to the 'system' library
INLINE.TXT   - Edit macro to copy text from DSN on cursor line as a SYSIN DD *
ISPFBAT.TXT  - JCL Procedure example to run ISPF in batch (used by BATJCL)
LMCENTER.TXT - Line command edit macro to center data line(s)
LMDO.TXT     - Line command edit macro to wrap Do-End around data line(s)
LMSPY.TXT    - Line command edit macro to add an ISREMSPY line after data line
MARKDIFF.TXT - Edit macro to show differences between to lines in the data
NXCOPY.TXT   - Edit macro to copy source data after/before each NX data line
RESC.TXT     - Edit macro to reset after a COMPARE command
STEPS.TXT    - Edit macro to show only JCL EXEC statements

Note: Due to character set changes while downloading/uploading the LMDO macro
      you may need to manually update the SEEK statement's picture string.
      The character between the single quotes needs to be a not sign (hex 5F).
