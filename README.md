create env

'''bash
conda create -n wineq python=3.8 -y
'''

activate env
'''bash
conda activate wineq
'''

created a requirements file

installed the requirements
'''bash
pip install -r requirements.txt
'''

git init
dvc init
dvc add data_given/winequality.csv



