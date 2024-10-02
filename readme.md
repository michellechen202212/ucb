# **Coupon Acceptance Analysis**

## **Overview**

This repository contains a detailed analysis of customer behavior when receiving digital coupons while driving. The study focuses on the key factors that influence whether a customer accepts or rejects a coupon. These factors include the type of coupon, customer demographics, and driving conditions. The dataset used for this analysis comes from the UCI Machine Learning Repository and was collected via a survey conducted through Amazon Mechanical Turk.

## **Files Included**

* `prompt.ipynb`: A Jupyter Notebook containing the complete analysis, including code and visualizations.  
* `coupons.csv`: The dataset utilized in this project, which includes details on coupon types, driving conditions, and customer demographics.  
* `README.md`: This file, providing a summary of the project and its key components.  
* `report.docx`: A nontechnical report summarizing the key insights and actionable recommendations drawn from the analysis.

## **Project Context**

The objective of this analysis is to explore the factors that impact a customer’s decision to accept or decline coupons while driving. Customers were presented with various driving scenarios and asked if they would accept a coupon for a bar, restaurant, or coffee house nearby. Important variables considered in the analysis include time of day, weather, passenger type, and destination.

## **Key Findings**

* **Coupon Type**: The acceptance rates vary depending on the coupon type. For instance, bar coupons tend to have higher acceptance rates, particularly among younger customers, while coffee house and restaurant coupons exhibit different trends across demographic groups.  
* **Demographics**: Younger individuals (under 30\) and those with higher incomes are more inclined to accept bar coupons. On the other hand, lower-income customers prefer more practical offers, such as restaurant discounts.  
* **Passenger Influence**: Drivers accompanied by adults, such as partners or friends, are more likely to accept bar or coffee house coupons. Conversely, drivers with children are less likely to accept bar coupons.  
* **Coupon Frequency**: Customers who frequently visit bars or coffee houses are more likely to accept related coupons. For example, individuals who go to bars more than three times a month have an acceptance rate exceeding 70%, compared to less frequent visitors.

## **Actionable Insights**

1. **Target Frequent Visitors**: Coupons for bars and coffee houses should be directed toward regular visitors, as they demonstrate a higher likelihood of redemption.  
2. **Demographic-Specific Offers**: Coupons for entertainment-related venues like bars should target younger customers (under 30). Meanwhile, practical offers like restaurant discounts may resonate more with lower-income groups.  
3. **Passenger-Aware Marketing**: Coupon offers should be tailored to the driver’s passengers. For example, bar coupons should focus on drivers with adult passengers, while family-oriented restaurant coupons may appeal more to drivers with children.  
4. **Timing**: Deliver bar and entertainment-related coupons during evenings and weekends when customers are more likely to engage in spontaneous activities.

## **How to Use the Repository**

1. Clone the repository to your local environment.  
2. Open the `prompt.ipynb` file using Jupyter Notebook.  
3. Ensure you have the required Python libraries installed (`pandas`, `matplotlib`, `seaborn`, etc.) to execute the analysis.  
4. Run the notebook to explore the data, visualize trends, and replicate the analysis results.

## **Conclusion**

This analysis offers valuable insights into the factors driving coupon acceptance among customers while driving. By utilizing these findings, businesses can refine their marketing strategies to deliver more targeted and effective offers, ultimately increasing coupon redemption rates.

