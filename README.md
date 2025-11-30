Bias in clinical artificial intelligence (AI) remains a critical concern, as models
often inherit inequities from training data and risk producing uneven outcomes
for vulnerable groups. While most research evaluates fairness after deployment, less attention has been paid to identifying which dataset features act as
primary indicators of bias (e.g., race, sex, age) and which act as secondary
indicators (e.g., insurance type, education, location).
This thesis addresses that gap through three objectives. First, it develops a
systematic method to classify primary and secondary bias indicators using widely
used ICU datasets such as MIMIC-III, MIMIC-IV, and eICU. Second, it
explores the use of interpretable AI/ML models to automatically flag attributes
by bias risk, combining statistical tests with literature guidance. Third, it
applies a fairness audit to OptAB, a recent AI framework for antibiotic selection
in sepsis patients.
The audit evaluates subgroup performance across sex, age, renal, and liver function using fairness metrics including demographic parity, disparate impact ratio,
equal opportunity, equalized odds, AUC disparity, and Brier scores. Statistical testing and visualization methods will be used to highlight disparities [2,3].
The expected contribution is a combined taxonomy of bias indicators, a prototype
flagging tool, and a fairness evaluation framework for clinical AI. Together, these
outputs aim to support more equitable applications of AI in critical care and
provide practical insights for responsible deployment.
