# di-dv_analysis_program
A program to analyze di/dv peaks of data obtained from a Scanning Tunneling Microscope


*Put this di-dv_peaks.ipynb and show_eps.ipynb into the folder with the desired .csv and .eps files*

----di-dv_peaks.ipynb----
You may select a variety of filters to the data;
  - Choose from eight graphing styles
  - Use the 'Apply Filter' button after selecting your specifications
  - The 'Reset' button removes the filters and resets the data set for your current graph style
  - Hover over the points to see their name (depending on your system, it could be very slow to reach the desired point)
  


The seventh cell hosts the graphing features for user interaction.
The eighth cell contains a form for user data submission.  It does not currently write to the csv file.



----show_eps.ipynb----
type in the title shown when hovering over a datapoint in di-dv_peaks.ipynb.  This title is the last six characters of the eps file title.  Two eps graph images will appear with a list of the last 10 searches.

  
