: Run the project using the pretrained model without training.

1. Clone/download the project and extract it.
2. Create a virtual environment: python -m venv venv
3. Activate it (PowerShell): .\venv\Scripts\Activate.ps1
4. Install dependencies: pip install -r requirements.txt
5. Move to the project folder: cd NST_Code
6. Run the application: python app.py
7. If Flask starts successfully, open http://127.0.0.1:5000 in your browser.
8. Do NOT run train.py unless you want to train a new model.
9. Ensure pretrained files such as vgg_normalised.pth and any required decoder checkpoint are present.
10. If a ModuleNotFoundError occurs, install the missing package with pip and rerun.



