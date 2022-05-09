# QR_comptaBDD
This is a protocol to sort a data financial excel and to rend plots. It is done with Python, in Anaconda, using the Pandas library. 

## Set up the environment
1. You have to install Anaconda environment.
2. Then, you have to install Jupyter Lab.
3. When it's done, just go to my instruction file and run one by one each block of code. 

### Anaconda installation
Link : https://www.anaconda.com/products/distribution <br />
Anaconda is an open-source distribution of the Python and R programming languages for data science that aims to simplify package management and deployment.
<br />
<br />
<img src="/install_anaconda.png" alt="Install Anaconda" height="300"/>

### JupyterLab installation
<img src="/install_jupyterlab.png" alt="Install JupyterLab" height="300"/>

### Run the project

You have 5 projects to run.

#### How to run a project
It is always the same steps. 
First, you import libraries.
Second, you select your excel. Be careful of the path.
Then, just run the code.
If you are done, you can save the changes in a new file.
For every excel file you save, please open the excel, delete the first column with numbers of the rows. It could be disturbing for later.

#### QR_filter

QR_filter helps you to delete useless rows, to select the interesting columns (date, plan_compta, debit, credit, solde progressif)

#### QR_split

QR_split can split the plan_compta to have only the number (ex: 1013) instead of the number and title (ex: 1013 CAPITAL)

#### QR_merge

QR_merge can merge two different tabs thanks to a common column. 

#### QR_firstNumber

It creates a column with the first number of the financial number (ex: for "1013" it gives "1").

#### QR_union

Once you have created several dataframes with the same datas, you can concatenate them into one dataframe.

Download QR_comptaBDD from Github
<br />
<img src="/download_file.png" alt="Download file" height="300"/>
<br />
<br />
Open file in localhost with JupyterLab.
<br />
<img src="/open_file.png" alt="Open file" height="300"/>
<br />
<br />
Run the code 
<br />
<img src="/run_code.png" alt="Run code" height="300"/>

### Create your new excel file
Once "Sales record successfully exported into Excel File" open the excel you've just created and make it clearer 
<br />
<br />
<img src="/delete_column.png" alt="Delete the first column" height="300"/>
<br />
<br />
<img src="/change_title.png" alt="Rename columns" height="300"/>
<br /> The titles you give for each column must be the same used in the code. 

### Plots
Now you can draw graphs, depending on the data you want to visualize. You have an example of how to select data and plot.

### Links that might help you
Pandas Installation instructions : https://pandas.pydata.org/getting_started.html <br />
Getting started with pandas : https://pandas.pydata.org/docs/getting_started/intro_tutorials/index.html
