IT Ticket Resolution Prediction - Assignment
Project Overview

This project focuses on analysing and predicting IT service ticket resolution times. The dataset represents service desk operations with features like assignment groups, reassignments, and SLA-related details.

The goal is not just prediction, but also to identify inefficiencies (like reassignment penalties and workload delays) and propose prescriptive actions for improvement.

🛠Files in Repo

PartB_Assignment.ipynb → Full Jupyter notebook with all preprocessing, feature engineering, modelling, and evaluation.

Report_Assignment1_PartD.docx → Final report (Part D submission).

Reports Part A–C (optional) → Earlier submissions for context.

How to Run

Clone the repo:

git clone https://github.com/your-username/it-ticket-resolution.git
cd it-ticket-resolution


Install requirements:

pip install -r requirements.txt


Open Jupyter Notebook:

jupyter notebook PartB_Assignment.ipynb

Key Results

Best performing model: Voting Classifier (ensemble of RF, LR, GBM, XGBoost)

Accuracy ≈ 0.54

Balanced F1 across classes:

Fast: 0.60

Moderate: 0.48

Slow: 0.55

Replication Notes

Dataset is provided by the course (not public).

All preprocessing (e.g., reassignment penalty subtraction, SLA feature removal) is included in the notebook.

Visualisations and confusion matrices are generated directly in the notebook.

Prescriptions (from analysis)

Auto-escalation when >2 reassignments.

Review workload balancing across support engineers.

Enforce SLA adherence with smarter routing.

Author

Mrunmayee Dixit
