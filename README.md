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
	b.)	Once in the repository directory, use the object menu (Right Clicking the mouse in the directory) and select "Open in Terminal". This will open a CMD window 		in the current directory.


<img width="898" height="862" alt="Image" src="https://github.com/user-attachments/assets/0d026f2a-7a49-4f99-8e11-233ff0b93c01" />
	
	
	c.) Alternatively, open a command window and change directory within the command window to the ClearVision directory. 
		i.e. cd c:\<repository path>
  
2. Start Jupyter Lab by typing 'jupyter lab' in the command window just opened.


<img width="964" height="505" alt="Image" src="https://github.com/user-attachments/assets/e7aee961-1280-46ef-ab73-dc61045f9a4f" />
  

3. Once Jupyter Notebook is open, all the files in that directory will appear in the files tab.


<img width="1265" height="879" alt="Image" src="https://github.com/user-attachments/assets/79d70b6c-4756-4518-9e01-081b54ec5aa1" />


5. If this is the first time running ClearVision from the current directory, the first step will be to run "0 - Setup & Run Website.jpynb".
This will configure/setup and start the ClearVision website. To do this follow these steps:

   a.) Double click "0 - Setup & Run Website.jpynb" from the folder view and the file will open in a new tab next to Launcher
   
   
<img width="1615" height="963" alt="image" src="https://github.com/user-attachments/assets/d0047ac0-9944-47d4-902d-94a0b1fbd5b1" />


	b.) Just above the "0 = Setup & Run Website.jpynd" file is a small menu bar, select the double arrows (Restart the kernel and run all cells)



<img width="696" height="63" alt="image" src="https://github.com/user-attachments/assets/122e39ca-246a-405e-9f97-6540f1e8d2f9" />
	


7. If ClearVision has already been setup and run once, then simply running "Website_Launch.jpynb" is all that is necessary to startup ClearVision. To do this follow these steps:

   a.) Double click on "Website_Launch.jpynb", which will open the file next to the Launcher


<img width="1308" height="1078" alt="image" src="https://github.com/user-attachments/assets/5760f4ae-c1dc-41c6-bb8b-da7b70c03ab8" />


	b.) Then select the double arrows to restart the kernel and run all the cells

   


