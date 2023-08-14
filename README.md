# web_sites_heatmap

## Prerequisites

- Ensure you have Python 3.x installed on your machine. 
- The required dependencies for this project are listed in the requirements.txt file.

## Installation

- Clone the repository: git clone <https://github.com/Mmmnnn887722/web_sites_heatmap.git>
- Install the required packages: pip install -r requirements.txt

## Files Overview
 - Python script
 - requirments.txt file 
 - sample of data in zip file, to run the code, that contains 2 csv file:
     - web_dat : scroll data 
     - iMotion data : 001_zaid
- web_page files, that contains multiple of web sites screen shoots saved before, 
please unzip this filr and modify it's path in the code to be the directory in your machine

## Objective and Functionality
  The primary objectives of the script are: 
  - To offer an interface through which users can load specific data files
  - To process web-related data, specifically extracting and saving screenshots from URLs.
  - To manipulate the 'iMotion' dataset, which seems to capture gaze and other related metrics.
  - To allow users to view past results and interact with processed datasets.

## Execution Flow
The application's flow is outlined as follows:
- Upon launch, the GUI interface is initialized, allowing users to interact with the program.
- Users have the option to load files for processing or view results from previously processed datasets.
- The data processing functionalities, when invoked, read the input data, perform the necessary operations (like capturing screenshots or cleaning data), and save the processed data.
- The main event loop, root.mainloop(), ensures the application remains responsive and operational until the user decides to close it.

# Contributing
For more information or to report any issues, please contact me at me22329@essex.ac.uk.

# License
