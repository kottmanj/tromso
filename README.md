# Tequila Tutorial

## Dependencies

Necessary  
```bash
pip install tequila-basic
```   

Optional: Fast simulator (recommended)
```bash
pip install qulacs
```  

Optional: Quantum Chemistry (classical methods, standard basis sets)
```bash
pip install pyscf
```  

Optional: Quantum Chemistry (MRA-PNOs via madness backend)
```bash
conda install madtequila -c kottmann
```

## Launch jupyter notebooks locally

```bash
git clone https://github.com/kottmanj/tromso
cd tromso
conda env create --name tromso --file environment.yml
conda activate tromso
conda install -c anaconda ipykernel
python -m ipykernel install --user --name=tromso
jupyter notebook
```

Then select the notebook of your choice and change the kernel:  
`kernel` -> `change kernel` -> "tromso"  




