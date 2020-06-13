# AutoApply
Script meant to automatically apply to jobs, currently on indeed <br>
Need to update "path" variable with path to relevant chromedriver which can be found here: <br>
https://sites.google.com/a/chromium.org/chromedriver/downloads <br>
Environment can be created with: <br>
conda create --name <env_name> --file requirements.txt <br>
To add environment as Jupyter kernel: <br>
source activate <env_name> <br>
python -m ipykernel install --user --name=<env_name> <br>
