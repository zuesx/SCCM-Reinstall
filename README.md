# SCCM-Reinstall
SCCM Client center reinstall script

Overview:

This script is used when troubleshooting the install of the SCCCM (MECM) client. This script will perform the following tasks. 
  Request computer name/ IP
  Request privileged credentials for the computer
  Check if the given computer is reachable
  Verify if the remote computer has PowerShell version 3 or higher. (This is necessary for the commands used in this script)
  Verify/Create a temp folder to store the SCCM client download. 
  Download the SCCM client from a supplied URL to the specified folder.
  Extract the client zip
  
