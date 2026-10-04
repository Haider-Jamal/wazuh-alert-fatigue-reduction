# Wazuh Alert Fatigue Reduction Project

SOC Analyst L1 portfolio project: tuned a Wazuh SIEM to reduce alert noise 
while proving true-positive detection survived the tuning.

Full write-up: `Alert-Fatigue-Reduction-Project.docx`

Key finding: a custom noise-reduction rule silently broke native brute-force 
correlation. Caught during re-validation, root-caused, and fixed with a 
second rule — restoring detection without losing the noise reduction.
