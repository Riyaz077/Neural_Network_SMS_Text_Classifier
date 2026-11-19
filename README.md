# Neural Network SMS Text Classifier

A TensorFlow/Keras neural network that predicts whether an SMS message is ham or spam.

## Files
- `fcc_sms_text_classification.ipynb` — complete Jupyter notebook.
- `README.md` — setup and execution instructions.

## Run in Google Colab
1. Upload the notebook to Google Colab.
2. Choose **Runtime → Run all**.
3. The notebook downloads the SMS dataset automatically.
4. Check the evaluation report and test `predict_message(...)`.
5. Run the official freeCodeCamp test cell from the original challenge notebook before submitting.

## Run locally in VS Code (Windows)
Open a terminal in this folder:

```powershell
py -3.11 -m venv .venv
.\.venv\Scripts\Activate.ps1
python -m pip install --upgrade pip
pip install tensorflow pandas numpy scikit-learn matplotlib ipykernel
```

Open the `.ipynb` file in VS Code, select the `.venv` Python kernel, and choose **Run All**.

If PowerShell blocks activation, use Command Prompt:

```cmd
.venv\Scripts\activate.bat
```

## Required function
`predict_message(message)` returns a two-item list:
- item 1: estimated spam probability, from 0 to 1
- item 2: predicted class, either `ham` or `spam`

## Important
This notebook is a complete implementation, but it has not been executed against the official freeCodeCamp test in this environment. Dataset downloads require internet access. The original challenge's final test cell may expect the exact train/test data variables and data preparation used in its starter notebook. Run that official test before submitting, and adapt the notebook to its supplied first two cells if necessary.
