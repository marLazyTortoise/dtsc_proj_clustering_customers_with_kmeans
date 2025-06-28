# Online Retail Data Clustering Project

## Setup

Using python 3.13.3

0. To enable "Windows Long Path Support" (on Windows) see  
     https://learn.microsoft.com/en-us/windows/win32/fileio/maximum-file-path-limitation?tabs=registry#enable-long-paths-in-windows-10-version-1607-and-later  
   Via Powershell e.g.  
     `New-ItemProperty -Path "HKLM:\SYSTEM\CurrentControlSet\Control\FileSystem" -Name "LongPathsEnabled" -Value 1 -PropertyType DWORD -Force`  
   Otherwise requirements-installation might fail.
1. Create a python virtual environment via `python -m venv .env`
2. Activate the environment via `source .env/Scripts/activate`
3. Install requirements via `pip install jupyter pandas matplotlib seaborn scikit-learn openpyxl`  
   Or  
   `pip install -r ./requirements.txt`
