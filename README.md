# Python-Data-Analysis
Python Data Analysis program with GUI- uses Pandas and Matplotlib, for Advanced Programming module in University.

## Program Functionality
The application provides the following functionality:
1. A means to load the initial data set (which consists of three CSV files) and translate it into a suitable format, either XML, or JSON       or an entity relationship structure (not CSV). 
2. A means to back up the data in this format using either files or a database. This should preserve the current state of the data when the program is closed.
3. A process for cleaning and preparing the initial data set, managing inconsistences, errors, missing values and any specific changes required by the client (see below)
4. A graphical user interface(s) for interacting with the data enable the user to:
      - Load and clean the initial data set
      - Load and save the prepared data set
      - Use the prepared data set to generate output and visualisations
      - Manipulate the range of values used to generate output and visualisations

A programe flow diagram and wire frame designs were constructed:

<a href="https://ibb.co/QfgTXpH"><img src="https://i.ibb.co/c1BZxk8/Screenshot-2021-02-03-at-11-49-40.png" alt="Screenshot-2021-02-03-at-11-49-40" border="0"></a>

Main Window and Graph Plot Windows Wire Frames:

<a href="https://ibb.co/7YKDNKS"><img src="https://i.ibb.co/GxRD3Rd/main-frame.png" alt="main-frame" border="0"></a>

<a href="https://ibb.co/z49LdLB"><img src="https://i.ibb.co/Js6bZbG/plot-1.png" alt="plot-1" border="0"></a>

<a href="https://ibb.co/q1wB1X4"><img src="https://i.ibb.co/WK1nKqd/plot-2.png" alt="plot-2" border="0"></a>

<a href="https://ibb.co/tJ8C1Sd"><img src="https://i.ibb.co/W2gKRQT/plot-3.png" alt="plot-3" border="0"></a>

<a href="https://ibb.co/X8LhLW1"><img src="https://i.ibb.co/Sryhy6b/show-data.png" alt="show-data" border="0"></a>

## Data Manipulation and Outputs 
The client initially wanted the application to perform the following actions on the data:
1.	Outputs should not include any data from vendors that have a ‘PROGRAM STATUS’ of INACTIVE.
2.	The ‘PE DESCRIPTION’ column contains information on the number and type of seating available at the vendor. Extract this out into a new column, retain all other information within that column. E.g.: 
      - ‘FOOD MKT RETAIL (1-1,999 SF) LOW RISK’, 
      - ‘RESTAURANT (61-150) SEATS LOW RISK’.  
3. The client initially needed information to generate the following and output the results using appropriate representation:
      - Produce the mean, mode and median for the inspection score per year:
      - For each type of vendor’s seating
      - For each ‘zip code’
      - To produce a suitable graph that displays the number of establishments that have committed each type of violation.
      - Determine if there is any significant correlation between the number of violations committed per vendor and their zip code, ‘Is there a tendency for facilities in specific locations to have more violations?’.
      
Outputs:
- Main Window:

<a href="https://imgbb.com/"><img src="https://i.ibb.co/KrG40mw/Screenshot-2021-02-03-at-11-48-14.png" alt="Screenshot-2021-02-03-at-11-48-14" border="0"></a>

- Show Cleaned Data Window:

<a href="https://ibb.co/RDTKSB2"><img src="https://i.ibb.co/pLjTPR2/Screenshot-2021-02-03-at-11-48-24.png" alt="Screenshot-2021-02-03-at-11-48-24" border="0"></a>

Graphical Outputs via Matplotlib:

<a href="https://ibb.co/hsqz6MF"><img src="https://i.ibb.co/6YdCMZ0/Screenshot-2021-02-03-at-11-48-44.png" alt="Screenshot-2021-02-03-at-11-48-44" border="0"></a>

<a href="https://ibb.co/2cyHSZv"><img src="https://i.ibb.co/xzDdYF1/Screenshot-2021-02-03-at-11-48-34.png" alt="Screenshot-2021-02-03-at-11-48-34" border="0"></a>

- Window to adjust subplot data and graphical layout:

<a href="https://ibb.co/12nBDJk"><img src="https://i.ibb.co/zf5CyHz/Screenshot-2021-02-03-at-14-49-26.png" alt="Screenshot-2021-02-03-at-14-49-26" border="0"></a>

## Running the Program:
- Execute via Jupyter Notebooks.
- Data set is available here.



