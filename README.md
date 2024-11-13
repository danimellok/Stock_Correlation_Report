# Stock_Correlation_Report

Getting Started

# Project Title

## Getting Started

Follow these steps to set up and run the project on your computer.

### 1. Clone the Repository

Download the project files to your computer by running the following commands in your terminal or command prompt. Replace `<repository-url>` with the actual URL of the project:


**Alternatively, you can download the entire repository as a ZIP file from GitHub:**  
1. Go to the repository page on GitHub.
2. Click on the "Code" button, then select "Download ZIP."
3. Extract the ZIP file and navigate to the project folder.

### 2. Install Required Packages

To ensure the project runs smoothly, install the necessary libraries. You can do this with one command:

**Instructions:**

1. **Install the Required Libraries:**

   In your terminal, make sure you’re in the project directory (where the `requirements.txt` file is located), and run:



This command will automatically install all necessary packages listed in `requirements.txt`, including:  
- `yfinance`  
- `pandas`  
- `matplotlib`  
- `fpdf`

### 3. If You Don’t Have `pip` Installed

If you encounter an error about `pip` not being installed, follow these steps to set it up:

1. Download the `get-pip.py` script by running this command:



2. Run the script to install `pip`:



3. Verify that `pip` installed correctly by checking its version:



4. Now you can install the required packages using `pip`:



### 4. Running the Code

Once all the libraries are installed, you’re ready to run the project. Use the following command to start the program:



### Imports in the Code (For Reference)

These are the libraries used in the code:

```python
import yfinance as yf  
import pandas as pd  
from datetime import datetime, timedelta  
import seaborn as sns  
import matplotlib.pyplot as plt  
from fpdf import FPDF, XPos, YPos  
