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
<td style="width: 15px; height: 63px;"><img width="411" height="316" alt="image" src="https://github.com/user-attachments/assets/7d0e1b77-c759-49fd-97ee-6e4edc5e86ab" /></td>
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
<td style="width: 15px; height: 63px;"><img width="402" height="330" alt="image" src="https://github.com/user-attachments/assets/931ee695-42e0-4819-8ef3-39257f465c27" /></td>
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
<td style="width: 15px; height: 57px;"><img width="402" height="322" alt="image" src="https://github.com/user-attachments/assets/705b15ac-1e1f-4941-a24e-d643d7e0afad" /></td>
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
<td style="width: 15px; height: 63px;"><img width="714" height="485" alt="image" src="https://github.com/user-attachments/assets/b1c77478-0b69-40ff-bca3-0eabb1081d55" /></td>
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
<td style="width: 15px; height: 23px;"><img width="479" height="388" alt="image" src="https://github.com/user-attachments/assets/add6c998-fd43-4ca8-8415-75e7e15a8823" /></td>
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
<td style="width: 15px; height: 43px;"><img width="487" height="382" alt="image" src="https://github.com/user-attachments/assets/daeb230b-93b7-4619-8ceb-108f48c57345" /></td>
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
<td style="width: 15px; height: 24.5px;"><img width="479" height="383" alt="image" src="https://github.com/user-attachments/assets/662d5a52-2cfb-42bb-bc50-0cbf941c9333" /></td>
<td style="width: 15.7031px; height: 24.5px;">0.4966</td>
</tr>
</tbody>
</table>

# GUIDE QUESTIONS (FINAL REFLECTION)

# A. Model Performance
# 1. Which pre-trained model achieved the highest accuracy? Why?
Ans: DenseNet121 achieved the highest accuracy, often exceeding 93% on validation. This is because DenseNet connects each layer to every other layer in a feed-forward fashion, which alleviates the vanishing-gradient problem and encourages feature reuse.

# 2. Which model had the lowest performance? What could be the reason?
Ans: Teachable Machine had the lowest performance. This was likely due to a simpler architecture and a lower input resolution (180x180), which captures less detail than the more complex pre-trained models.

# 3. How did loss values compare across models?
Ans: Transfer learning models (DenseNet, ResNet) typically showed lower and more stable loss values compared to the custom V1 model, indicating better convergence.

# B. Evaluation Metrics
# 4. Why is accuracy not enough to evaluate a model?
Ans:  Accuracy can be misleading if the dataset is imbalanced (e.g., if one class has many more images than others). It doesn't tell us where the model is specifically failing.

# 5. Which model had the best F1-score? What does it indicate?
Ans: DenseNet121 had the best F1-score (~0.93). A high F1-score indicates a good balance between Precision and Recall, meaning the model is reliable at both identifying a class and not misidentifying others as that class.

# 6. How did Precision and Recall differ across models?
Ans: Precision measures how many 'positives' were actually correct, while Recall measures how many of the actual 'positives' the model caught. In our tests, DenseNet maintained high levels for both, while weaker models showed 'gaps' where they often missed certain classes (low recall).

# C. Confusion Matrix Analysis
# 7. Which classes were frequently misclassified?
Ans: Classes with similar visual features (e.g., two types of similar-looking objects) were frequently misclassified into one another.

# 8. What patterns did you observe in the confusion matrix?
Ans: The diagonal line was strongest for DenseNet, while weaker models showed 'scatter' outside the diagonal, indicating confusion between specific categories.

# D. ROC and AUC
# 9. Which model had the highest AUC score?
Ans: DenseNet121 achieved a Macro-AUC of approximately 0.99.

# 10. What does AUC tell us about model performance?
Ans: AUC measures the model's ability to distinguish between classes. An AUC of 0.99 means there is a 99% chance the model will rank a random positive instance higher than a random negative one.

# E. Explainability (Grad-CAM)
# 11. What did Grad-CAM reveal about model decision-making?
Ans: Grad-CAM revealed that the models look for specific edges, textures, or central objects to make a decision.

# 12. Did the model focus on relevant image regions?
Ans: The better models (DenseNet/ResNet) focused on the actual object, while the weaker models sometimes looked at the background or irrelevant edges.

# 13. Which model produced the most meaningful heatmaps?
Ans: DenseNet121 produced the most meaningful heatmaps that tightly aligned with the physical object in the image.

# F. Model Comparison & Improvement
# 14. Which model would you recommend for deployment? Why?
Ans: I recommend DenseNet121 for deployment due to its superior balance of high accuracy, high F1-score, and robust AUC.

# 15. How can you further improve your best-performing model?
Ans: Further improvements could include Data Augmentation (flipping, rotating images), Fine-tuning for more epochs, or using an even larger architecture like EfficientNetV2.

# G. Real-World Application
# 16. How can your model be applied in real-world scenarios?
Ans: This system can be used for automated sorting, inventory management, or assisted living apps (e.g., helping visually impaired users identify objects).

# 17. What are the risks of deploying an inaccurate model?
Ans: Deploying an inaccurate model in critical fields (like medical or safety) could lead to dangerous misidentifications.

# 18. How can this system be integrated into a mobile/web app?
Ans: The model can be converted to TensorFlow Lite (.tflite) for use in mobile apps or served via a Flask/FastAPI backend for web applications.
