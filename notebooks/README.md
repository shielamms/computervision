## Installing a jupyter kernel

```
python -m venv venv
source venv/bin/activate

pip install jupyter
pip install ipykernel, ipython, bash_kernel

python -m ipython kernel install --user --name=cv-nb-kernel
python -m bash_kernel.install

jupyter notebook
```