# Salary-Predictor

1. Create a github repository.
- Title, Public, README.md, python
- Opening the repository in vscode

2. Create virtual environment
- Python -m venv_name
- Activate the env. name/Scripts/activate
- Incase it doesnot get activated:
   - Execute this command in VS Code PowerShell instance: Set-Execution Policy RemoteSigned -ScopeProcess
- Install the required libraries: pip install numpy, pandas, matplotlib, jupyter, ipykernel seaborn, scikit-learn

3. Data Gathering and Model Training (model.ipynb)
- Select the kernel
- Load data and import libraries
- Preprocessing and train test split
- Model Training
- Model evaluation
- Model Serialization

4. app.py (Streamlit UI)

- pip install Streamlit UI
- Import libraries
- Page, Title, Document Title
- Load model
- Define input fields: st.number_input()
- Make prediction: st.success
- https://cheat-sheet.streamlit.app/

5. requirements.txt
- model.version
- Donot do pip freeze

6. Streamlit Community Cloud
- Connect/continue with GitHub
- Utilize default CI/CD
