# VoltMat AI — Frontend

Open `index.html` in a browser.

This is a frontend prototype for the metal-ion battery electrode-voltage prediction project. It mirrors the paper's input/feature-processing/ML workflow.

Important:
- The current browser result is a UI demonstration, not a trained scientific prediction.
- Replace `predictVoltage()` with a call to your Python/FastAPI/Flask backend once the DNN/SVR/KRR models are trained.
- The research paper describes 237 input features, normalization, PCA reduction to 80 components, and DNN/SVM/SVR/KRR-style model evaluation.
