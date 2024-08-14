# Automate_rename_file_py

This code is about remane a set of files using python funcions and  libraries:
- firstly we need to create a function that we will  extract the title from the content by using <code> pdfminer.high_level </code> of the file and then print it correctly  through calling <code> bidi.algorithm </code> model 
- Then we will specify the folder that contains our files. To do that import  <code> os </code> lib, and passing the path as parameter to <code> os </code> method called <code> listdir </code>.
- After all files would represent as a list, we will loop to processing each file seprantly.
- We get the path of each file and then pass it into the function that we have prepared befor.
  
