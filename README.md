# cse251b kaggle


## setup
To set up with a virtual environment:
```bash
python -m venv .venv
./venv/Scripts/activate
```

To install libraries with `requirements.txt`:
```bash
pip install -r ./requirements.txt
```

The notebook assumes an **unzipped** `cse-251-b-2025` folder with the data as `.npz` files at the **same level** as the notebook.

```
cse251b-kaggle
├── README.md
├── cse-251-b-2025
│   ├── test_input.npz
│   └── train.npz
├── cse-251-b-2025.zip
├── kaggleNotebook.ipynb
└── requirements.txt
```

The `submission/` folder and CSVs, GIFs have been silenced in `.gitignore`.
