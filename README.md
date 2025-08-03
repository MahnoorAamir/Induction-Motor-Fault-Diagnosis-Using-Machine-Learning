# 🌀 Induction Motor Fault Diagnosis Using Machine Learning

This project focuses on diagnosing **induction motor faults** using **three-phase current signature analysis**. The classification is done using both **Naïve Bayes** and **Support Vector Machine (SVM)** for:

- ✅ Binary Classification: Healthy vs Unhealthy
- 🔢 Multiclass Classification: 14 Fault Classes

The dataset includes current data of motors under varying load and fault conditions, making it ideal for time-domain analysis and condition monitoring.

---

## 📁 Dataset Overview

The dataset contains **instantaneous current values** for three-phase induction motors recorded under different load and fault conditions:

### ✅ Fault Types

- **Bearing Faults**:
  - Inner-race and Outer-race
  - Severity Levels: 0.7mm, 0.9mm, 1.1mm, 1.3mm, 1.5mm, 1.7mm
- **Broken Rotor Bar (BRB) Faults**
- **Load Conditions**: 100W, 200W, 300W
- **Total Files**: 39
- **Folders**: 7 (organized by load level)
- **Sampling Rate**: 10,000 Hz
- **Block Size**: 1000 samples per channel




