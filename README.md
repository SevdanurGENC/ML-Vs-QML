# ML-Vs-QML
It will be shown how to train a quantum machine learning model to overcome a classification problem.


As an example of a quantum model, we’ll train a variational quantum classifier (VQC). The VQC is the simplest classifier available in Qiskit Machine Learning and is a good starting point for newcomers to quantum machine learning who have a background in classical machine learning.


![image](https://github.com/SevdanurGENC/ML-Vs-QML/assets/5441882/1e803eab-fb71-4a23-8ddf-8a04eb038b28)

![image](https://github.com/SevdanurGENC/ML-Vs-QML/assets/5441882/11bb5620-c9b6-4601-bcb5-519a53f2baa8) 

![image](https://github.com/SevdanurGENC/ML-Vs-QML/assets/5441882/4c4368d3-7708-4072-86d1-75b6fe459fb4)


## Conclusion 

```ts 
print(f"Model                           | Test Score | Train Score")
print(f"SVC, 4 features                 | {train_score_c4:10.2f} | {test_score_c4:10.2f}")
print(f"VQC, 4 features, RealAmplitudes | {train_score_q4:10.2f} | {test_score_q4:10.2f}")
print(f"----------------------------------------------------------")
print(f"SVC, 2 features                 | {train_score_c2:10.2f} | {test_score_c2:10.2f}")
print(f"VQC, 2 features, RealAmplitudes | {train_score_q2_ra:10.2f} | {test_score_q2_ra:10.2f}")
print(f"VQC, 2 features, EfficientSU2   | {train_score_q2_eff:10.2f} | {test_score_q2_eff:10.2f}") 
```

![image](https://github.com/SevdanurGENC/ML-Vs-QML/assets/5441882/e5297f0e-3d39-42d3-940a-3f59434c093d)
