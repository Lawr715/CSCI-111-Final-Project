# Marino CSCI 111 Valorant ML Submission

## Files
- `Marino_Code.ipynb` - final runnable notebook.
- `Marino_Presentation.pdf` - final presentation deck.
- `Marino_Speaker_Script.md` - optional recording script.
- `valorant_shared_meta_shape_top5.csv` - cleaned final dataset used by the notebook.
- `requirements.txt` - Python package list.

## How to Run
1. Open a terminal in this folder.
2. Install packages:
   ```powershell
   python -m pip install -r requirements.txt
   ```
3. Start Jupyter:
   ```powershell
   jupyter notebook
   ```
4. Open `Marino_Code.ipynb` and run all cells.

The notebook loads `valorant_shared_meta_shape_top5.csv` directly, so the raw `vct_2021` through `vct_2026` folders and `build_ultimate_v8.py` are not required for the submitted version.
