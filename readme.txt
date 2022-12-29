cd C:\Users\mrzes\Downloads
start /affinity 1 Anaconda3-2022.05-Windows-x86_64.exe
conda create -n learn-datascience  python=3.9.12 anaconda 
conda create --prefix=c:\tools\Anaconda3\envs -n learn-datascience  python=3.9.12 anaconda 
conda activate learn-datascience

conda env create -p c:\tools\Anaconda3\envs\learn-datascience  python=3.9.12 anaconda 

conda create --prefix c:\tools\Anaconda3\envs\learn-datascience python=3.9.12

conda config --show

jupyter notebook
pip install jupyter_contrib_nbextensions
jupyter contrib nbextension install --user
jupyter nbextension enable varInspector/main
jupyter notebook
