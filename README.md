step1: create venv
conda create -p venv python==3.11 -y

step2: activate conda venv
conda activate venv/

step3: install requirements.txt

step4: install dev dependencies like ipykernel

Remark: setuptools 81.0 works properly always install that(pkg_resources)