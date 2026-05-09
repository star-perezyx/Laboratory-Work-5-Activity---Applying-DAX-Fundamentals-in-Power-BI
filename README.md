# Laboratory-Work-5-Activity---Applying-DAX-Fundamentals-in-Power-BI

# Google Colab Link: <a href="https://colab.research.google.com/drive/1X3JkjxgKyCNaW1e9C7XhacG6qXPhwFTm?usp=sharing">CLICK HERE</a>!

<table style="width: 686.703px;">
<tbody>
<tr style="height: 43px;">
<td style="width: 97px; height: 43px;">Model-Sample</td>
<td style="width: 87px; height: 43px;">Train Accuracy</td>
<td style="width: 82px; height: 43px;">Train Loss</td>
<td style="width: 13px; height: 43px;">Test Accuracy</td>
<td style="width: 15px; height: 43px;">Test Loss</td>
<td style="width: 15px; height: 43px;">Precision</td>
<td style="width: 15px; height: 43px;">Recall</td>
<td style="width: 15px; height: 43px;">F1-score</td>
<td style="width: 15px; height: 43px;">ROC</td>
<td style="width: 15.7031px; height: 43px;">AUC</td>
</tr>
<tr style="height: 63px;">
<td style="width: 97px; height: 63px;">Pre-Trained Model 1 (DenseNet121)</td>
<td style="width: 87px; height: 63px;">0.828883</td>
<td style="width: 82px; height: 63px;">0.661469</td>
<td style="width: 13px; height: 63px;">0.055340</td>
<td style="width: 15px; height: 63px;">10.746322</td>
<td style="width: 15px; height: 63px;">0.054335</td>
<td style="width: 15px; height: 63px;">0.054346</td>
<td style="width: 15px; height: 63px;">0.054220</td>
<td style="width: 15px; height: 63px;">&nbsp;</td>
<td style="width: 15.7031px; height: 63px;">0.506360</td>
</tr>
<tr style="height: 63px;">
<td style="width: 97px; height: 63px;">Pre-Trained Model 2&nbsp;(EfficientNetB3)</td>
<td style="width: 87px; height: 63px;">0.083010</td>
<td style="width: 82px; height: 63px;">2.974527</td>
<td style="width: 13px; height: 63px;">0.045631</td>
<td style="width: 15px; height: 63px;">10.128438</td>
<td style="width: 15px; height: 63px;">0.007414</td>
<td style="width: 15px; height: 63px;">0.047122</td>
<td style="width: 15px; height: 63px;">0.012369</td>
<td style="width: 15px; height: 63px;">&nbsp;</td>
<td style="width: 15.7031px; height: 63px;">0.484317</td>
</tr>
<tr style="height: 57px;">
<td style="width: 97px; height: 57px;">Pre-Trained Model 3&nbsp;(ResNet101)</td>
<td style="width: 87px; height: 57px;">0.105825</td>
<td style="width: 82px; height: 57px;">2.858907</td>
<td style="width: 13px; height: 57px;">0.049515</td>
<td style="width: 15px; height: 57px;">9.003025</td>
<td style="width: 15px; height: 57px;">0.020428</td>
<td style="width: 15px; height: 57px;">0.053761</td>
<td style="width: 15px; height: 57px;">0.025142</td>
<td style="width: 15px; height: 57px;">&nbsp;</td>
<td style="width: 15.7031px; height: 57px;">0.500458</td>
</tr>
<tr style="height: 63px;">
<td style="width: 97px; height: 63px;">Model from Teahable Machine</td>
<td style="width: 87px; height: 63px;">N/A</td>
<td style="width: 82px; height: 63px;">N/A</td>
<td style="width: 13px; height: 63px;">0.043689</td>
<td style="width: 15px; height: 63px;">2.995732</td>
<td style="width: 15px; height: 63px;">0.002184</td>
<td style="width: 15px; height: 63px;">0.05</td>
<td style="width: 15px; height: 63px;">0.004186</td>
<td style="width: 15px; height: 63px;">&nbsp;</td>
<td style="width: 15.7031px; height: 63px;">0.500061</td>
</tr>
<tr style="height: 23px;">
<td style="width: 97px; height: 23px;">1st Model</td>
<td style="width: 87px; height: 23px;">0.8425</td>
<td style="width: 82px; height: 23px;">0.4453</td>
<td style="width: 13px; height: 23px;">0.0621</td>
<td style="width: 15px; height: 23px;">10.8997</td>
<td style="width: 15px; height: 23px;">0.0607</td>
<td style="width: 15px; height: 23px;">0.0595</td>
<td style="width: 15px; height: 23px;">0.0591</td>
<td style="width: 15px; height: 23px;">&nbsp;</td>
<td style="width: 15.7031px; height: 23px;">0.5043</td>
</tr>
<tr style="height: 43px;">
<td style="width: 97px; height: 43px;">2nd Model - Enhancement</td>
<td style="width: 87px; height: 43px;">0.828883</td>
<td style="width: 82px; height: 43px;">0.661469</td>
<td style="width: 13px; height: 43px;">0.055340</td>
<td style="width: 15px; height: 43px;">10.746322</td>
<td style="width: 15px; height: 43px;">0.054335</td>
<td style="width: 15px; height: 43px;">0.054346</td>
<td style="width: 15px; height: 43px;">0.054220</td>
<td style="width: 15px; height: 43px;">&nbsp;</td>
<td style="width: 15.7031px; height: 43px;">0.506360</td>
</tr>
<tr style="height: 24.5px;">
<td style="width: 97px; height: 24.5px;">3rd Model - The Good Model</td>
<td style="width: 87px; height: 24.5px;">0.8966</td>
<td style="width: 82px; height: 24.5px;">0.2982</td>
<td style="width: 13px; height: 24.5px;">0.0485</td>
<td style="width: 15px; height: 24.5px;">12.5211</td>
<td style="width: 15px; height: 24.5px;">0.0449</td>
<td style="width: 15px; height: 24.5px;">0.0465</td>
<td style="width: 15px; height: 24.5px;">0.0454</td>
<td style="width: 15px; height: 24.5px;">&nbsp;</td>
<td style="width: 15.7031px; height: 24.5px;">0.4966</td>
</tr>
</tbody>
</table>

GUIDE QUESTIONS (FINAL REFLECTION)

A. Model Performance
1. Which pre-trained model achieved the highest accuracy? Why?
2. Which model had the lowest performance? What could be the reason?
3. How did loss values compare across models?

B. Evaluation Metrics
4. Why is accuracy not enough to evaluate a model?
5. Which model had the best F1-score? What does it indicate?
6. How did Precision and Recall differ across models?

C. Confusion Matrix Analysis

7. Which classes were frequently misclassified?
8. What patterns did you observe in the confusion matrix?

D. ROC and AUC
9. Which model had the highest AUC score?
10. What does AUC tell us about model performance?

E. Explainability (Grad-CAM)
11. What did Grad-CAM reveal about model decision-making?
12. Did the model focus on relevant image regions?
13. Which model produced the most meaningful heatmaps?
F. Model Comparison & Improvement
14. Which model would you recommend for deployment? Why?
15. How can you further improve your best-performing model?

G. Real-World Application
16. How can your model be applied in real-world scenarios?
17. What are the risks of deploying an inaccurate model?
18. How can this system be integrated into a mobile/web app?
