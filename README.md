# POWER-BI-
MINI PROJECT

Dataset: https://docs.google.com/spreadsheets/d/1Ez8RhO1rE2QikfdddOZ19eEZhN4r6eW7WHb9qB05T7E/edit?usp=sharing


EXPLANATION : 

https://drive.google.com/file/d/17t0P7-CMtVKYL7mTRlPA6QJjNpmQtWPt/view?usp=drive_link


Analyze the data by visualizing the percentage of shipping based on ship mode : 

Shipping Percentage (1) = 
DIVIDE(
    COUNT('Global Superstore - Orders (1)'[Order ID]),
    CALCULATE(COUNT('Global Superstore - Orders (1)'[Order ID]), ALL('Global Superstore - Orders (1)'[Order ID]))
) * 100


