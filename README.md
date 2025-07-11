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

For W1A3:
`pip install tensorflow==2.3.0`
`pip install matplotlib`
`pip install music21`
`pip install mido`
`pip install pydub`

For W2A1: 
Unzip file W2A1/data/glove.6B.50d.txt.zip

For W2A2:
`pip install emoji`
`pip install scikit-learn`

Unzip file W2A1/data/glove.6B.50d.txt.zip
Copy file W2A1/data/glove.6B.50d.txt to W2A2/data

For W3A1:
`pip install Faker`
`pip install tqdm`
`pip install Babel`

For W4A1:
`pip uninstall tensorflow`
`pip uninstall Faker`
`pip uninstall emoji`
`pip uninstall numpy`
`pip install numpy==1.19.2`
`pip install tensorflow==2.4.0`
