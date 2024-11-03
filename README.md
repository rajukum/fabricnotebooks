First we need to use Sempy link labs and install them. Here is more information on sempy links library. https://github.com/microsoft/semantic-link-labs
The notebook takes two capacity Ids source and target. Target capacity ID needs to be in small vs source in Caps. This is due to dataframe output returned in small. The idea here is to check if the target capacity
exists, it is possible that target exists and the user running notebook doesn't have access to the capacity. 
Then the code has list of workspaces which you want to assign to the subdomain, there are mix of Admin API and user API here in the notebook. 
The code assign the workspace first to the target capacity then assign the workspace to the subdomain. 
