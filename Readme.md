# Programming for Data Analysis Project
**Programming for Data Analysis Project**


**Assignment:** Programming for Data Analysis, GMIT 2021  

**Lecturer:** Dr Brian McGinley  

**Author:** Enda Lynch   
**Github Username:** Lynch08  
**GMIT Email:** G003987951@gmit.ie  
**Personal Email:** elyn@live.ie  

##### Background   
This is my simulation project for the Programming for Data Analysis module, Galway-Mayo Institute of Technology, 2021.  

This GitHub repository documents my initial research, project progress (git version control) and findings.

##### Github Repository

**URL:** https://github.com/Lynch08/ProgDA_Project/tree/master 

The repository contains:
 - 1 jupyter notebook (Sim_SmartPhone_Data.ipynb) that holds the explanation, code, visuals and citeations for the assignment.
 - The Assignment details in PDF form from Dr Brian McGinley 
 - An Images folder where I have stored some PNG files to display in the notebook
 - A readme file explaining the objectives, outcomes and instructions on how to view the notebook in both editable and static format.
 - A folder called Monthly_Data (This is not required but a line of code needs to be uncommented in section "4.2 Code" if this folder does not exist)
 
### Assignment Objectives  

See the Assignment Instructions [here](./ProgDAProject.pdf)

**The Primary Objectives are as follows:**

 - Choose a real-world phenomenon that can be measured and for which you could collect at least one-hundred data points across at least four different variables.
 - Investigate the types of variables involved, their likely distributions, and their relationships with each other.
 - Synthesise/simulate a data set as closely matching their properties as possible.
 - Detail your research and implement the simulation in a Jupyter notebook – the data set itself can simply be displayed in an output cell within the notebook.

This project is intended to further familiarisation with data analytics. It is also intended to get familiar with the analytical tools, specifically the NumPy library and its random sampling module. The project will allow to get practical understanding of handling data in Python environment.

As it is a learning exercise for me, I have made attempt to try and comment various functionalities not only for readability but also for my future reference.

**Planned Project Outcomes**
 - To gain experience in project time management by break the project down into small manageable tasks.  
 - To gain an understanding of the functionality of the NumPy library and how to use its functions and distribuion types when simulating data.
 - To integrate the skills I had acquired in my first semester with the first 10 weeks of the Programming in Data Analysis module to analyse the library and present a cohesieve and interesting project.  
 - To expand my knowledge of the python libraries and tools to make the code as simple and readable as possible for the reader.  
 - To learn how to best optimise my time between research, programming, problem-solving and analysis.


### Assignment delivery
The project is stored in this GitHub [repository] (https://github.com/Lynch08/ProgDA_Project/tree/master ).

This README.md file contains background information and introduction to the assignment.

The assignment has been done within the Jupyter Notebook Sim_SmartPhone_Data.ipynb, stored in this repository.

In the notebook I have conducted the research and described the assignment progress. It is illustrated the applied concepts and methods together with relevant code snippets. The notebook includes also the calculated outputs and plots with accompanied description. Finally, inside the notebook I have included also references to sources being consulted for this assignment.


### How to download this repository (editable version)

- Go to GitHub.
- Go to my repository: https://github.com/Lynch08/ProgDA_Project/tree/master 
- Click the clone/download button.
- Save the repository to a local folder location on your machine.
- You will need to navigate to this folder location on the command line in order to run the program.
- Details on how to run each individual script in this repository is included later in this Readme file.

### Running the Jupyter Notebook

 - On the command line navigate to the folder location where the repository has been downloaded and saved to using the cd command to change directory.
 - Type jupyter lab on the command line and press enter
 - After a short wait jupyter notebook will open in your web browser (I would suggest Chrome).
 - Open the Sim_SmartPhone_Data.ipynb notebook in the browser and the notebook containing the code and comments that I wrote for this assignment will be displayed.
 - Before beginning I would suggest going to the Kernel option on the menu bar and if you want to run the notebook yourself choose "Restart Kernel and Clear Outputs". If you want the notebook to run automatically choose "Restart Kernel and Run All Cells"
 - If you want to run the code in any particular cell, click into the cell, hold down the shift key, press enter and the command will run and the output wil be displayed in the next cell.
 - To change between edit and read mode at any time press the ESC key.
 - When you have finished viewing the jupyter notebook close the web browser and return to the command line. Press Ctrl + C on the command line to kill the program.

### Dependancies 

I have a requirements.txt file that you can use to install all of the dependencies required to run the notebook in the exact same environment - however below are the main dependencies if you would like to do that manually. After cloning the repository navigate to the folder using the command prompt and use the ```pip install``` command if you want to use the requirments.txt file.
See this video for full instructions on how to install: https://www.youtube.com/watch?v=mBcmdcmZXJg 


**Required**
- Download Python environment - I recommend ([Anaconda](https://www.anaconda.com/products/individual)) 
    - Libraries to import within the python environment (all are linked to official documentation)
        - [Numpy](https://numpy.org/doc/)
        - [Pandas](https://pandas.pydata.org/docs/)
        - [matplotlib.pyplot](https://matplotlib.org/stable/api/_as_gen/matplotlib.pyplot.html)
        - [Seaborn](https://seaborn.pydata.org/)
        - [Random](https://docs.python.org/3/library/random.html)
        - [Time](https://docs.python.org/3/library/time.html)
        - [Calendar](https://docs.python.org/3/library/calendar.html)
        - [OS](https://docs.python.org/3/library/os.path.html)
        - [Glob](https://docs.python.org/3/library/glob.html)
        - [Datetime](https://docs.python.org/3/library/datetime.html)

**Not required but helpful**  
cmder - this is a command line emulator that in my opinion is easier to use and cleaner than the windows cmd window. [Download Cmder Here](https://cmder.net/)


 
 
### Notebook Structure
 
The notebook is broken down into 9 sections.  
In the first two sections I go through a brief explanation of what I understand the numpy library to be and its history.  
Then I explain how to install Numpy (once the dependencies above have been met) and link to the documentation if required.  
I then dive into the functionality and tools in the library. First looking at what random data is and how to generate different types.  
Then I look at how that data can be manipulated using permutations and then how it can be interpreted and analysed using different distributions.  
I look at the seed and discuss if random data is really random, and how to make your work with a random number generator reproducible.  
Finally I cite the sources I used to put the notebook together.

##### See the Table Of Contents below
Table of contents is also at the top of the notebook.

1. Introduction
    - 1.1 Project objective
    - 1.2 Choice of real world phenomenon
    - 1.3 Investigate the types of variables involved, their likely distributions, and their relationships with each other.
    - 1.4 Synthesise/simulate a data set as closely matching their properties as possible
    - 1.5 Detail your research and implement the simulation in a Jupyter notebook – the data set itself can simply be displayed in an output cell within the notebook
    
2. About Data Simulation
    - 2.1 Data Simulation a Brief History
    - 2.2 Benifits of Simulated Data2.2 Benifits of Simulated Data
    - 2.3 Real World Applications for Simulated Data2.3 Real World Applications for Simulated Data

3. Investigate the types of variables involved, their likely distributions, and their relationships with each other
    
4. Synthesise/simulate a data set as closely matching their properties as possible 
    - 4.1 Python Libraries
    - 4.2 Setting the seed
    - 4.3 Code
    - 4.4 Add more columns for Analysis from simulated data
    
5. Analysis 
    - 5.1 Monthly Analysis
    - 5.2 Analysis of sales data by city 
    - 5.3 Analysis of Orders per hour
    - 5.4 Analysis of Orders for Phone type
    - 5.5 Analysis of orders by Region (And Finding a Mistake)  
    
6. Permutations 
    - 6.1 Function random.shuffle  
        - 6.1.1 Using shuffle with a multi dimensional array  
    - 6.2 Function random.permutation   
    
7. Citations and Bibliography
    - 7.1 Citations from Notebook
    - 7.2 Biblography
    
