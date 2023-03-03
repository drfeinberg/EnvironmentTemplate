# EnvioronmentTemplate

This is a bash script that will create a new anaconda environment with:  
- Python 3.10  
- Jupyter  
- Jupyter Lab  
- Pandas  
- OpenPyxl  
- Seaborn  

Then it activates the environment and installs:  
- praat-parselmouth with pip  

You are dumped back into bash, but not in the environment.  You still need to activate it.  If you know how to dump me back into an activated environment, please help me with a PR.


To run this from any folder, make sure you add the path of the script to your PATH.  For example, mine lives in a folder called ~/bash_scripts.  To add that to my path I ran:  

`export PATH=$PATH:~/bash_scripts`
