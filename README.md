# Task 7: Support Vector Machines (SVM)

## 🎯 Objective
Explore how Support Vector Machines (SVM) can be used to classify data, both linearly and non-linearly, using a simple 2D dataset.

## 🧰 Tools & Libraries
- **Scikit-learn** – for building and evaluating SVM models  
- **NumPy** – for data handling  
- **Matplotlib** – for visualizing the data and decision boundaries

## 📝 What You'll Do
1. **Create a toy dataset** using `make_moons` – a fun 2D binary dataset with a bit of noise.
2. **Train two SVM models**: one with a linear kernel, and one with an RBF (non-linear) kernel.
3. **Visualize the decision boundaries** to see how each model separates the classes.
4. **Tune hyperparameters** like `C` and `gamma` using `GridSearchCV` to find the best model.
5. **Evaluate your models** using cross-validation to get a better sense of performance.
