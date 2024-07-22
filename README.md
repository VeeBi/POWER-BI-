# POWER-BI-
MINI PROJECT


EXPLANATION : 





Analyze the data by visualizing the percentage of shipping based on ship mode : 

Shipping Percentage (1) = 
DIVIDE(
    COUNT('Global Superstore - Orders (1)'[Order ID]),
    CALCULATE(COUNT('Global Superstore - Orders (1)'[Order ID]), ALL('Global Superstore - Orders (1)'[Order ID]))
) * 100


