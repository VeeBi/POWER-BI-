# POWER-BI-
MINI PROJECT


Shipping Percentage (1) = 
DIVIDE(
    COUNT('Global Superstore - Orders (1)'[Order ID]),
    CALCULATE(COUNT('Global Superstore - Orders (1)'[Order ID]), ALL('Global Superstore - Orders (1)'[Order ID]))
) * 100
