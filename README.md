# Hotel-Bookings-Analysis-Power-BI-Project
Hotel Bookings Analysis: Revenue Optimization and Cancellation Risk Modeling  A business intelligence project using Power BI to visualize key performance indicators and actionable insights derived from hotel booking data, prepared and cleaned using Python. Focuses on revenue leakage, lead time risk, and seasonality.

# Hotel Bookings Analysis: Revenue Optimization Dashboard

This project presents a comprehensive Business Intelligence (BI) analysis of hotel booking data, designed to identify major drivers of lost revenue, quantify cancellation risk, and propose actionable strategies for performance improvement.

The entire workflow, from data preparation to final visualization, showcases a practical application of core data analysis tools.

## Key Project Goals :

1.  **Quantify Revenue Leakage:** Determine the total lost revenue and identify the distribution channels most responsible for cancellations.
2.  **Model Cancellation Risk:** Establish the correlation between booking lead time, market segments, and cancellation rates.
3.  **Optimize Strategy:** Provide clear, data-backed recommendations for contract negotiation, deposit structuring, and targeted marketing campaigns.

## Insights & Recommendations :

The analysis resulted in three core strategic findings visualized in the Power BI dashboard:

### **Insights**
| Insight | Key Finding |

| **Lost Revenue Concentration** | Total Lost Revenue is **$16.7M** (39.2% of Total), highly concentrated in the **TA/TO (Travel Agent/Tour Operator)** channel. |
| **Long Lead Time Risk** | Bookings placed **>300 days in advance** show a cancellation rate frequently exceeding **50%**, predominantly driven by the **Group** segment. |
| **Booking Volume Gaps** | Low-occupancy periods (lowest volume months) are consistently **February, May, and October**. |

### **Recommendations**
| Recommendation | Strategic Action |

| **Contractual Review** | Implement stricter non-refundable deposit terms with TA/TOs to secure revenue. |
| **Risk-Based Deposit** | Introduce a dynamic, higher non-refundable deposit for **Group** bookings placed **180+ days** in advance. |
| **Targeted Demand** | Launch specific promotional campaigns during **February, May, and October** to stabilize booking volume. |

 Technologies Used

* **Data Cleaning & Preprocessing:** **Python** (Pandas, NumPy)
* **Business Intelligence & Visualization:** **Microsoft Power BI**
* **Data Source:** (Specify your data source if possible, e.g., Sample Hotel Bookings Dataset, Kaggle, etc.)

## Repository Structure

* `data/`: Contains the original and cleaned datasets (csv files).
* `notebooks/`: Contains the Python script/Jupyter Notebook used for data preparation (e.g., `data_cleaning.ipynb`).
* `reports/`: Contains the Power BI file (`.pbix`) and screenshots of the final dashboard.
* `README.md`: This file.

## How to View the Dashboard

1.  Clone this repository.
2.  Download and install **Microsoft Power BI Desktop**.
3.  Open the file located in the `reports/` folder (e.g., `Hotel_Bookings_Analysis.pbix`).
4.  Navigate through the different tabs (Bookings, Revenue, Cancellations) to explore the full analysis.


*This project was completed as a demonstration of skills in data analysis, BI visualization, and generating commercial recommendations.*
