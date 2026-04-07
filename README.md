# SIMULATION-OF-MEAN-AND-VARIANCE-USING-SCILAB-T1-C12-EVEN
AIM:

To write a program for mean, variance and cross correlation in SCILAB and verify the output.

#EQUIPMENTS NEEDED:

.Computer with i3 Processor

.SCI LAB

ALGORITHM:

Define the Function: Specify the function you want to simulate. For example, f(x)=sin⁡(x)f(x)=sin(x) or any other function.
Generate Sample Points: Decide on the range and the number of sample points. Generate these sample points within the desired range.
Evaluate the Function: Compute the function values at each of these sample points.
Compute Mean, Variance and Cross Correlation: Use Scilab's functions to calculate the mean and variance of the computed function values.
Display Results: Output the computed mean variance and Cross Correlation

PROCEDURE:

1.Refer Algorithms and write code for the experiment.

2.Open SCILAB in System

3.Type your code in New Editor

4.Save the file

5.Execute the code If any Error, correct it in code and execute again

6.Verify the generated results

PROGRAM:
```
clc;
clear;

// Given data
X = [3 5 6 7 9];

// Number of elements
N = length(X);

// Calculate Mean
mean_value = sum(X) / N;

// Calculate Variance
variance_value = sum((X - mean_value).^2) / N;

// Display Results
disp("Mean = ");
disp(mean_value);

disp("Variance = ");
disp(variance_value);
```

CALCULATION:

<img width="1424" height="1384" alt="image" src="https://github.com/user-attachments/assets/7cdd6acc-1e5b-4b4c-98dc-2e934ec6e583" />
<img width="1417" height="1600" alt="image" src="https://github.com/user-attachments/assets/13a83a44-f205-4cb1-9c2d-a2194f93b77e" />


OUTPUT:

<img width="180" height="169" alt="image" src="https://github.com/user-attachments/assets/88cc13ee-072f-4887-965c-871c18fc4eb1" />

RESULT:

<img width="1348" height="894" alt="image" src="https://github.com/user-attachments/assets/dfc77bab-74e8-4731-a457-4488a1c9f737" />
