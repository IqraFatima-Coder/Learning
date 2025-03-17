# Virtual Environement
## Important Commands

- Open Anaconda Prompt
- Create a virtual environment
  *conda create -n environment_name python=version_number*
  (*Enter y if asks for permission to proceed*)
- Activate virtual environment
  *conda activate environment_name*
- Deactivate virtual environment
  *conda deactivate*
- Install Packages
   Two ways:

   1) Using pip Command (Recommended):
  *pip install package_name==version*

  e.g.   pip install numpy

  2)  Using conda:
  *conda install package_name*

  e.g. 
    conda install pandas


- Display Package List:
  *conda list*
-  Delete an Environment: 
  *conda remove --name env_name --all*
- Show all created environments:
  *conda info --envs*   or *conda info -e*
  
