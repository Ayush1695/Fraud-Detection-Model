Please find below the instruction to run the code - This is the entire process I followed. Or you can just open my notebook from the path and can start running it.

1) I downloaded the data using terminal. The code to download the data is as belows:
    a Open terminal or git bash
    b Type "cd" to directory
    >     cd <Your directory>
    c) Initiate a git repository
    >     git init .
    d. Add existing files
    >     git add .
    e. Commit all files (-a) and add a message (-m)
    >  git commit -a -m "Download transaction data"
    f. clone the repo with the clone url
    >  git clone --Cant share the data path because of privacy--

2) Once you have clones the repo the data will be saved in a DS folder. 
   I could have programmity copy pasted it into more intuitive folder but in the interest of time 
   i extracted the transaction.zip to transaction.txt and copy pasted it to a folder named input

3) Now you just need to copy my "code.ipynb" file that I sent to the repo in which you cloned the data.

4) Make sure you have all the required packages installed. 
  I have placed a requirements.txt file in the folder itself.
  You just need to run the code below in the directory from terminal.
  If packages like xgboost, lightgbm, hyperopt already installed in you machine, this can be skipped
   > pip install -r requirements.txt

5) Next open the code.ipynb file and start running the code block by block. Make sure the working directory is correctly set.

6) You can keep running the code and check the output

Note: There is nothing to save so output folder will remain empty.
