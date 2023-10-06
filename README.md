# NLP to Identify High Risk ICU Readmission Patients

Deep learning models have improved significantly over the years. The evolution of natural language
processing(NLP) has shown a lot of options to tackle medical analysis bottle necks that have existed
for decades. The invention of BERT (Bidirectional Encoder Representations from Transformers)
has opened the doors for more wide spread adoption of NLP in higher risk areas that could effect
patient care. Now that the architecture of training in both left and right contexts has proven it's
worth, there are opportunities to think of how it might improve the workflow within the hospital,
specifically the task of care coordinators to identify patients at risk for readmission. This study
explores that possibility with the use of the MIMIC III dataset and BERT models. The study is
attempting to evaluate if it is plausible for clinic notes to predict readmission of a patient into
an ICU. In the end, the best model had an AUC of 0.64. This did not meet the benchmark of
a manual evaluation from a care coordinator, but does show promise for further iteration on the
model.
