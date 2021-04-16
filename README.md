# contentdm
Making CONTENTdm uploading easier

NOTE 1: Be sure to TRIM and CLEAN your data. Trailing spaces can cause errors.


Split Data file:

This method is for creating separate tab delimited files for each compound object, something needed for uploading using the directory structure in CONTENTdm Project Client. For how to use directory structure uploading, see this video https://www.youtube.com/watch?v=g7QjfRK0Y0o&t=14s

Sheet 1 is titled Data and should include all of your metadata. Column A should have identifiers, and Column B should have the related compound object identifier or title (depends on how you want to upload your files). Columns C through n can hold the rest of your metadata.

Sheet 2 has the macro button and requires the file path to output your tab delimited files.

Split Data into separate folders file:

Similar to the split data file but this one requires a master folder path to be supplied (where you want all of your files and subfolders to be saved to) in Sheet 2. Since CONTENTdm directory structure requires each file to be in its own subfolder, this will check to see if that subfolder exists and save the file there, if the subfolder does not exist, it will create one based on the compound object identifier/title you provided in Column B of Sheet 1 and save the file there.
