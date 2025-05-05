# dls-course5
Deep Learning Specialization - Course 5 - Sequence models

To run locally (using VS Code), **install pyenv + virtualenv**

`brew install pyenv pyenv-virtualenv`

Install Python version, e.g.

`pyenv install 3.7.17`

cd into the working directory and **create a virtual env** with desired Python version:

`pyenv virtualenv 3.7.17 dls-c5`

Activate the virtual env:

`pyenv local dls-c5`

Install needed Python libraries

`pip install numpy==1.18.4`

`pip install nbconvert` #to avoid syncing cell's output - See https://gist.github.com/33eyes/431e3d432f73371509d176d0dfb95b6e