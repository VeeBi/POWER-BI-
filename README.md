# POWER-BI-
MINI PROJECT


EXPLANATION : 


https://drive.google.com/file/d/17R9vA0yyet_46gLp8_dUcgKyIKIWkfDK/view?usp=drive_link

https://drive.google.com/file/d/17Ndb3-cRmmsxr2JlyZ0H6tI1rwixhlXm/view?usp=drive_link

https://drive.google.com/file/d/17VuhyEC5qwYd_lWuuFUw4O8NKUo8Td55/view?usp=drive_link


Analyze the data by visualizing the percentage of shipping based on ship mode : 

Shipping Percentage (1) = 
DIVIDE(
    COUNT('Global Superstore - Orders (1)'[Order ID]),
    CALCULATE(COUNT('Global Superstore - Orders (1)'[Order ID]), ALL('Global Superstore - Orders (1)'[Order ID]))
) * 100


