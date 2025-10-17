END TO END ML PROJECT

conda create -p venv python=3.8 -y

 conda activate C:\mlproject1\venv

 conda create -n ml38 python=3.8 -y
conda activate ml38
pip install ipykernel
python -m ipykernel install --user --name ml38 --display-name "Python 3.8 (ml38)"
