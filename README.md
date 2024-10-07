# Python-Analysis-on-Sudan-Conflict


This project contains code for analyzing and visualizing data related to humanitarian aid for Sudan and other countries.

#  Project Background/Context:

The Sudan conflict has not been widely reported on given the number of casualties and the scale of the humanitarian crisis. This project seeks to use humanitarian aid data to compare the Sudan conflict to other crisis areas and their relative media coverage compared to Sudan. I also analyse trade data to understand a hidden element of how the UAE have continued to capitalise from this conflict through trade.

# Data sources:
1. Annual financial report of United Nations High Commissioner for Refugees (UNHCR) - was used for humanitarian aid data
2. MediaCloud.org was used for media analysis including number of mentions for major conflict areas across TheGuardian, CNN, BBC and Al-Jazeera

#  Executive Summary:

The code utilizes numpy, pandas and matplotlib libraries to process and visualize data from various sources. Key functionalities include:

Creating scatter plots to explore the relationship between displaced people and budget allocation. Incorporating country flags as data point markers for enhanced visualization.
![Screenshot 2024-10-07 124349](https://github.com/user-attachments/assets/6f14e407-4b86-4574-8c98-7049e64aa65d)

Analyzing media mentions of Sudan, Ukraine, and Gaza over time.
![Screenshot 2024-10-07 125157](https://github.com/user-attachments/assets/f811797c-58eb-4688-a06b-fc36e52544e4)

Merging and visualizing data on media mentions by country for different news outlets.
![Screenshot 2024-10-07 125635](https://github.com/user-attachments/assets/e0d7fcc8-04b8-4087-a4c3-bdba0afe99bc)


Examining trade data between African countries and the UAE. (Note: Data paths reference user's local machine and need adjustment)
![Screenshot 2024-10-07 125801](https://github.com/user-attachments/assets/be17cbf8-93f1-4d2b-9c28-50010ccfb8cd)


## 3. Insights Deep Dive:

- The scatter plots provide a  correlation between displaced people and humantarian budget allocation with Sudan requiring more budget than neighboring conflicts

- Visualizing media mentions reveals Sudan to be the least covered conflict from its start to present (time at which study took place)

- Trade data shows the UAE to continue profiting from the Sudan conflict via Gold trade

## Additional Notes:

The code currently uses file paths specific to the user's machine and needs adjustments for broader use.
Error messages are present due to undefined variables resulting from missing data merges. These can be addressed by ensuring successful data merging before plotting the visualizations.
I hope this summary clarifies the project's goals and the functionalities of the code.
