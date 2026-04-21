## **Title**
**A Hybrid Time-Series Framework for Early Detection and Slow Drift Detection of Household Energy Inefficiency Using Smart Meter, Weather, and Carbon Intensity Data**

## **Aim**
To develop a **multi-household time-series framework** that integrates **global forecasting models** with **residual-based monitoring** to detect **early inefficiency events** and **slow drift** in **electricity consumption** while assessing **environmental impact**.

## **Objectives**
- To **preprocess and integrate** **smart meter**, **weather**, and **carbon intensity data**
- To analyse **temporal consumption patterns** across **households**
- To develop **global forecasting models** using **XGBoost**, **Random Forest**, and **TCN**
- To apply a **local LSTM model** for selected **household-level analysis**
- To detect **inefficiency-related drift** using **STL**, **CUSUM**, and **EWMA**
- To enable **early anomaly detection** and **slow drift detection**
- To evaluate model performance using **MAE**, **RMSE**, and **R²**
- To analyse the **carbon impact** of **excess energy consumption**
- To apply **Explainable AI** using **global SHAP**, **feature importance**, and **permutation importance**
- To simulate **pseudo real-time monitoring** and **alert generation**

## **Observation**
**Electricity consumption** evolves over time with both **sudden changes** and **gradual behavioural shifts**, influenced by **internal usage patterns** and **external factors** such as **weather**.

## **Interpretation**
A **hybrid approach** combining **global forecasting models** (**XGBoost**, **Random Forest**, **TCN**), **statistical drift monitoring**, and **Explainable AI** provides a **scalable**, **interpretable**, and **real-world applicable solution** for detecting and managing **household energy inefficiency**.
