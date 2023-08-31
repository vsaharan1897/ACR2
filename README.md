# ACR2

# General Overview:
#This reports consists of two files: . 
#ACR2GetReports.ipynb: Automatates report pulling from Diio, renames download, and covnerts to csv
#ACR2Part2.ipynb: Analyzes downloaded csv files and produces SummaryDash.png and ACR Carrier Summary Tabs.xlsx

# Setup:
#1. Download Jupyter Notebooks/Anaconda. 
#2. In the folder "Python Scripts", add the contents of ACR2Documents.zip. This zip will also contain 2019PullData.zip, add contents of this file into 'Python Scripts" as well (Note: you can also place content in whichever folder Jupyter Notebook is installed, avoid
placing anything into the 'Downloads' folder)
#3. Recieve both .ipynb files and download both into "Python Scripts" folder or wherever Python is located. Open both .ipynb files and download all necessary libraries using pip install *library*
#4. You will also need to download Chrome Web Driver To get Chrome WebDriver, use the following guide:
                #1. Check your version of Chrome ( ":" --> "Help" --> "About Google Chrome")
                #2. Then lookup "WebDriver for Chrome" and select the link that says that (https://chromedriver.chromium.org/downloads)
                #3. From there, find the correct link to download (most likely will be stable version for windows 32) and put into a new tab and will download 
                #4. Move the downloaded content into the same folder where Jupyter Noetbook is in ('Python Scripts', etc)
#5. Once everything is downloaded, proceed to start execution of ACR2GetReports.ipynb
