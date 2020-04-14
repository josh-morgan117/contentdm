# contentdm
Making CONTENTdm uploading easier

Split Data file:

This method is for creating separate tab delimited files for each compound object, something needed for uploading using the directory structure in CONTENTdm Project Client. For how to use directory structure uploading, see this video https://www.youtube.com/watch?v=g7QjfRK0Y0o&t=14s

Sheet 1 is titled Data and should include all of your metadata. Column A should have identifiers, and Column B should have the related compound object identifier or title (depends on how you want to upload your files). Columns C through n can hold the rest of your metadata.
Sheet 2 has the macro button and requires the file path to output your tab delimited files.

I am currently working on adding a loop to check for the separate directory folder and saving the file there or creating the directory needed and then saving the file.
