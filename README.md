This repository provides trained Scikit-Learn machine learning models used in the associated paper (Composition Optimization of Oxide Glasses for Advanced IC Packaging via Machine Learning).

Each pickle file contains an artificial neural network (ANN) model trained using chemical composition descriptors to predict a key glass property for IC packaging.

model_Coefficient_of_Thermal_Expansion.pkl
ANN model for predicting the coefficient of thermal expansion (CTE).

model_Glass_Transition_Temperature.pkl
ANN model for predicting the glass transition temperature (Tg).

model_Youngs_Modulus.pkl
ANN model for predicting Young’s modulus.

model_Shear_Modulus.pkl
ANN model for predicting shear modulus.

model_Vickers_Hardness.pkl
ANN model for predicting Vickers hardness.

model_Fracture_Toughness.pkl
ANN model for predicting fracture toughness.

model_Thermal_Conductivity.pkl
ANN model for predicting thermal conductivity.

Input order (mol%):
SiO₂, B₂O₃, Al₂O₃, MgO, CaO, BaO, Li₂O, Na₂O, K₂O, ZnO, SrO, TiO₂, GeO₂, P₂O₅

model_Dielectric_Constant.pkl
ANN model for predicting dielectric constant.

model_Dielectric_Loss.pkl
ANN model for predicting dielectric loss.

Input order (mol% for each chemical component):
SiO₂, B₂O₃, Al₂O₃, MgO, CaO, BaO, Li₂O, Na₂O, K₂O, ZnO, SrO, TiO₂, GeO₂, P₂O₅, Temperature (oC), log frequency (Hz)


If you have any questions, please contact Shuwei Chang at Davidliefco@gmail.com

