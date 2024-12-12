# Exploratory_Data_Analysis_Pizza_Sales_Dataset
ABOUT THIS DATASET

This dataset contain detailed information about pizza orders, including specifics about the pizza variants, quantities, pricing, dates, times, and categorization details.

pizza_id: A unique identifier assigned to each distinct pizza variant available for ordering.
order_id: A unique identifier for each order made, which links to multiple pizzas.
pizza_name_id: An identifier linking to a specific name of the pizza.
quantity: The number of units of a specific pizza variant ordered within an order.
order_date: The date when the order was placed.
order_time: The time when the order was placed.
unit_price: The cost of a single unit of the specific pizza variant.
total_price: The aggregated cost of all units of a specific pizza variant in an order.
pizza_size: Represents the size of the pizza (e.g., small, medium, large).
pizza_category: Indicates the category of the pizza, such as vegetarian, non-vegetarian, etc.
pizza_ingredients: Provides a list or description of the ingredients used in the pizza.
pizza_name: Specifies the name of the specific pizza variant ordered.

LIBRARIES THAT IMPORTED IN THIS DATASET
import pandas as pd 
import numpy as np
import seaborn as sns
import matplotlib.pyplot as plot
