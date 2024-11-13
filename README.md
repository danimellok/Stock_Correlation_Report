# Stock_Correlation_Report

Getting Started

Follow these steps to set up and run the project on your computer.
1. Clone the Repository
First, download the project files to your computer by running the following commands in your terminal or command prompt. Replace <repository-url> with the actual URL of the project:
git clone <repository-url>
cd <repository-directory>
Alternatively, you can download the entire repository as a ZIP file from GitHub:
Go to the repository page on GitHub and click on the "Code" button, then select "Download ZIP." Extract the ZIP file and navigate to the project folder.
2. Install Required Packages
To make sure everything works properly, you’ll need to install some packages. You can do this in one simple step.
Instructions:
Install the Required Libraries:
In your terminal, make sure you’re in the project directory (where the requirements.txt file is located), and then run:
pip install -r requirements.txt
This command will automatically install all necessary packages listed in requirements.txt, including:
yfinance
pandas
matplotlib
fpdf
3. If You Don’t Have pip Installed
If you see an error about pip not being installed, follow these steps to set it up:
Download the get-pip.py script by running this command:
curl https://bootstrap.pypa.io/get-pip.py -o get-pip.py
Run the script to install pip:
python3 get-pip.py
Verify that pip installed correctly by checking its version:
pip --version
Now you can install the required packages using pip:
pip install pandas yfinance matplotlib fpdf
4. Running the Code
Once the libraries are installed, you’re ready to run the project. Use the following command to start the program:
python your_script_name.py
Replace your_script_name.py with the actual name of the Python file you want to run.
Imports in the Code (For Reference)
These are the libraries used in the code:
import yfinance as yf
import pandas as pd
from datetime import datetime, timedelta
import seaborn as sns
import matplotlib.pyplot as plt
from fpdf import FPDF, XPos, YPos
