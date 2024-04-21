######### create environment
conda create -p venv python==3.10 -y

######### get list of python environment
conda info --envs   

######### activate environment
conda activate venv/

######### install library
pip install -r requirements.txt

######### get google api key
https://aistudio.google.com/app/apikey

######### poppler needed for pdf2image
brew install poppler