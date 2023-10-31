# HBS/COICOP Supply-Chain Footprint Analysis (pymrio)
Interquintile footprint comparison and analysis for Great Britain.

Eurostat provides annual data on Household Final Consumption expenditure broken down by COICOP categories and by certain cross-sectional variables.


__Results__
---
Total footprints:
![Alt text](images/image1.png)

Footprints by source:

$$\text{Fpt}_{\text{source}} = S \cdot \text{diag}(X) = S\cdot \text{diag}(L\cdot Y)$$
whereby X is the total industrial outputs. Here we need to iterate group-wise.

![Alt text](images/image2.png)

Footprints by final product:
$$\text{Fpt}_{\text{product}} = S\cdot L \cdot \text{diag}(Y)$$

![Alt text](images/image3.png)

Visualization (approximate) of RoW area:
![Alt text](images/image4.png)