# Lab 4 – Explainable and Privacy-Aware AI Threat Alert

**Course:** ENSP355 – AI in Cyber Security  
**Platform:** Jupyter Notebook / Google Colab

## Project contents
- `Lab_4_Explainable_Privacy_Aware_Threat_Alert.ipynb` – complete notebook for Q1–Q5.
- `requirements.txt` – Python dependencies.
- `.gitignore` – ignores temporary notebook and Python files.

## How to run locally
1. Install Python 3.10 or later.
2. Open a terminal in this folder.
3. Create and activate a virtual environment (recommended).
4. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
5. Start Jupyter:
   ```bash
   jupyter notebook
   ```
6. Open `Lab_4_Explainable_Privacy_Aware_Threat_Alert.ipynb`.
7. Choose **Kernel → Restart & Run All** and save the notebook.

## Run in Google Colab
1. Upload the `.ipynb` file to Google Drive.
2. Right-click it and choose **Open with → Google Colaboratory** (or upload it directly at Colab).
3. Choose **Runtime → Run all**.

## Important dataset note
The Lab 4 manual instructs students to reuse the small login-activity model and dataset from Lab 2. Those Lab 2 files were not included with the supplied Lab 4 PDF. Therefore, this notebook includes a small **illustrative synthetic training dataset** so every cell runs independently. Replace `training_data` in the notebook with your actual Lab 2 training dataset and retrain the Decision Tree if you have it. The five assessment records are taken from the Lab 4 manual.

## Questions covered
- Q1: Baseline predictions and confidence.
- Q2: Feature importance, chart, and interpretation.
- Q3: Controlled sensitivity test (`failed_logins`: 2 → 8).
- Q4: IP/account masking and four privacy rules.
- Q5: Responsible alert severity, reason, recommended action, and human review.

## GitHub upload
Create a new GitHub repository, then upload all files in this folder. Or use:
```bash
git init
git add .
git commit -m "Complete AI in Cyber Security Lab 4"
git branch -M main
git remote add origin https://github.com/YOUR-USERNAME/YOUR-REPOSITORY.git
git push -u origin main
```
Replace the remote URL with your own repository URL. Do not upload real user identifiers or confidential login data.
