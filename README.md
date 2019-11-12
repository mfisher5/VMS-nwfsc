## Process Vessel Monitoring System (VMS) Data

This repository contains all files used to process vessel monitoring system (VMS) data. Data and RMarkdown output are not included for confidentiality.


### Project Overview
There are three subprojects in processing VMS data: 

1. pre-processing PacFIN fish tickets and VMS data, 

2. matching VMS to fish tickets, and 

3. interpolating missing VMS data.
<br>
<br>


### Directory Structure

`input_data`: raw and prcoessed OLE VMS data, PacFIN fish ticket data. File formats either .csv or .dbf

`methods`: images and ppt to keep track of methods. most content pasted into readme docs.

`R_Output`: intermediate and final .csv, .dbf files output from R for both fish ticket and VMS data. Also includes visualizations saved as .png files.

`resources`: 

`results`: summaries of results

`scripts`: all R scripts used to process VMS data.

`verify_code`: R scripts, data, workspaces used to verify code

<br>
<br>
<br>
<br>

*Additional documentation and most input / output from R is saved on Google Drive and NOAA server.*