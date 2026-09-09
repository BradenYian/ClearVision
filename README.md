# ClearVision Local
The ClearVision Local branch contains the code necessary to run ClearVision locally on a Windows workstation or server.
In order execute and run the local version of ClearVsion, Jupyter Lab from Project Jupyter will be required.
To start and run ClearVision Local from Jupyter Lab follow the steps listed below
1. Download and install Jupyter Lab https://jupyter.org/install#jupyterlab
2. Project Jupyter tools are available for installation via the Python Package Index (pip), the leading repository of software created for the Python programming language.
3. Installing Jupyter Lab with pip:
	a.) Open Run Windows key + R (Win+R) or a Command window (type cmd from Start menu)
	b.) Type 'pip install jupyter lab' into the Run dialog or CMD window
Note: If you install Jupyter Lab with conda or mamba, we recommend using the conda-forge channel.

Once installed, start Jupyter Lab as follows:
1. Open/Start Jupyter Notebook in the directory which contains the GitHub repository. 
	a.) Navigate to the directory containing the ClearVision files with File Explorer Windows key + E (Win+E)
  b.)	Once in the repository directory, use the object menu (Right Clicking the mouse in the directory) and select "Open in Terminal". This will open a CMD window in the current directory.
  <img width="898" height="862" alt="Image" src="https://github.com/user-attachments/assets/0d026f2a-7a49-4f99-8e11-233ff0b93c01" />
  c.) Alternatively, open a command window and change directory within the command window to the ClearVision directory. i.e. cd c:\<repository path>
2. Start Jupyter Lab by typing 'jupyter lab' in the command window just opened.
3. Once Jupyter Notebook is open, all the files in that directory will appear in the files tab.

5. If this is the first time running ClearVision from the current directory, the first step will be to run "0 - Setup & Run Website.jpynb". This will configure/setup and start ClearVision
6. If ClearVision has already been setup and run once, then simply running "Website_Launch.jpynb" is all that is necessary to startup ClearVision.
