# Forecasting_IBEX_Stock_Index

The objective of this project is to create a regression model capable of estimating the future value of the IBEX stock-market index, based on explanatory variables whose future value can be predicted with reasonable accuracy.

The first thing they thought of was to include **interest rates**, a classic variable, given that fixed- income interest rates influence the progress of variable income, although it is not known if the long- term rates or short-term rates are a better explanatory variable. As a representative short-term rate they used the **90-day Madrid interbank rate (MIBOR**), and as a long-term rate they took the **10-year bond rate**.
Also, it seems that international capital flows can have an important influence on changes in the stock-market indexes, and so a variable related to these flows of foreign capital was included, namely the **€/$ exchange rate**.
