# Global Terrorism Analysis

<details>
<summary>Table of Contents</summary>

1. [About the Project](#about-the-project)
2. [Dataset Description and Cleaning](#dataset-description-and-cleaning)
3. [Data Analysis Strcture](#data-analysis-structure)
4. [Insights from Data Analysis](#insights-from-data-analysis)
5. [Libraries Used](#libraries-used)
6. [Contact](#contact)
</details>

## About the Project

The Global Terrorism Analysis project aims to provide critical insights into the patterns and drivers of terrorism related incidents worldwide. Terrorism poses a significant threat to global security and stability, affecting countries, general public and communities across the world. By analyzing historical data and trends, this project seeks to understand the temporal trends, geographical hotspots, most prominent organizations and their attack types, and many more factors contributing to terrorism incidents.

<div align = "right">    
  <a href="#global-terrorism-analysis">(back to top)</a>
</div>

## Dataset Description and Cleaning

The dataset is quite vase with 181691 rows (each row representing a unique terrorist attack) and 135 columns. Several columns had over half missing values. They were all filtered out, and the necessary columns carefully selected out of the remaining. Their characteristics are described below:
**NOTE**: The variables colour-coded with green background below are the "**primary variables**", i.e., variables which are primarily being used for the EDA.

![image](https://github.com/vahadruya/Capstone_EDA_Global_Terrorism_Analysis/assets/115869753/df788231-dd78-46d2-8d91-ec8b3000de7e)

A column named **casualties** was created from the columns of **killed** and **wounded** for each terrorist attack, representing the total impact of the terrorist attack. The total number of terrorist events, casualties, number of suicide attacks, and successful attacks are called the **"Impact" metrics**, which highlights the effect of terrorism.

<div align = "right">    
  <a href="#global-terrorism-analysis">(back to top)</a>
</div>

## Data Analysis Structure

The dataset is analysed in three separate sections, each of which contain multiple sub-sections. Various kinds of plots such as line-plots, bar-plots, combined line-bar plots, pie-charts, and geographical heatmaps have been used in this project, mostly using libraries such as **plotly** and **folium**. The sections are, namely:

1. **Global Analysis**: In this section, the entire dataset is considered for a holistic analysis, for all countries of attack and all terrorist organisations, to understand the general characteristics of terrorist attacks and their effect on the populace. Both univariate and bivariate analyses is performed, for various features such as the attack type, yearly variation of attacks, target type etc, for all the impact metrics.
2. **Local Analysis** This section involves analysis on a subset of the dataset, of specific countries of interest. These countries are chosen based on the heatmap and/or the plots which display hot-spots of terrorist activities. The countries chosen are **Iraq**, **Afghanistan**, **Pakistan** and **India**.
3. **Analysis of specific terrorist organisations**: This section contains analysis of specific terrorist organisations, selected based on their notoreity, popularity and impact of terrorism. They are **Taliban** and **The Islamic State of Iraq and the Levant (ISIL)**. Few other terrorist organisations such as **Shining Path**, **Boko Haram** etc. are also analysed briefly

<div align = "right">    
  <a href="#global-terrorism-analysis">(back to top)</a>
</div>


## Insights from Data Analysis

*   Number of terrorist attacks and the casualties increased exponentially in the 21st century, especially in the regions of **Middle East**, **South Asia** and **Sub-Saharan Africa**, peaking in 2014. The percentage of suicide attacks among the attacks in these regions also started increasing in the same period of time.
*    **Bombings** and **Armed Assaults** are an overwhelming favourite of terrorists as a method of their attack, with most of suicide attacks involving the former. **Private Citizens and Properties**, **Military** and **Police** were the most targeted institutions/places by the terrorists.
*    The terrorist hotspots in 20th century were primarily in the **United Kingdom**, **El Salvador** and **Peru**. The terrorist organisations of **IRA**, **FMNL** and **Shining Path** respectively were prominent within these countries.
*    The countries of **Iraq**, **Afghanistan**, **Pakistan** and **India** are the terrorist hotposts of 21st century, with highest number of attacks, casualties and suicide attacks. The one single terrorist event in USA by Al-Qaida was one of the most devastating terrorist attacks, claiming over 19,000 casualties in just 4 attacks.
*    **The Islamic State (ISIL)** is the most active terrorist organisation in **Iraq** with over 4000 terrorist attacks conducted by them, despite starting as late as 2013. They were also active in several areas of **Turkey** and **Syria**. **Baghdad** was the most targeted city in **Iraq**, and over a quarter of attacks were through suicide bombings.
*  The **Taliban** is the most active terrorist organisation in **Afghanistan**. They almost completely operate within the country, with a few attacks in border of Pakistan as well. Their primary target is the Afghan **Police** and **Military** 
*   India has been witnessing several **Maoist** and **Communist** attacks in the 21st century, in the Naxalist infested states of **Jharkhand**, **Chattisgarh** etc. Most of the attacks are using **Bombings** and **Armed Assaults**, with very few suicide attacks unlike in **Iraq**.

<div align = "right">    
  <a href="#global-terrorism-analysis">(back to top)</a>
</div>

## Libraries Used

For handling and manipulating data

<a href="https://pandas.pydata.org/" target="_blank"><img src="https://img.shields.io/badge/Pandas-black?style=flat-square&logo=Pandas&logoColor=white&link=https://pandas.pydata.org" alt="Pandas" width="84" height="25"></a>
<a href="https://matplotlib.org/" target="_blank"><img src="https://img.shields.io/badge/Matplotlib-afc6d3?style=flat-square&logo=matplotlib&logoColor=white&link=https://matplotlib.org/" alt="Matplotlib" width="78" height="25"></a>
<a href="https://seaborn.pydata.org/" target="_blank"><img src="https://img.shields.io/badge/Seaborn-7db0bc?style=flat-square&logo=seaborn&logoColor=white&link=https://seaborn.pydata.org/" alt="Seaborn" width="65" height="25"></a>
<a href="https://pypi.org/project/folium/" target="_blank"><img src="https://img.shields.io/badge/folium-00aa54?style=flat-square&logo=folium&logoColor=white&link=https://pypi.org/project/folium/" alt="folium" width="75" height="25"></a>
<a href="https://plotly.com/python/" target="_blank"><img src="https://img.shields.io/badge/plotly-black?style=flat-square&logo=plotly&logoColor=white&link=https://plotly.com/python/" alt="plotly" width="70" height="25"></a>
<div align = "right">    
  <a href="#global-terrorism-analysis">(back to top)</a>
</div>


## Contact

<a href="https://www.linkedin.com/in/aditya-a-p-507b1b239/" target="_blank"><img src="https://img.shields.io/badge/Linkedin-0078b7?style=flat-square&logo=linkedin&logoColor=white&link=https://www.linkedin.com/" alt="Linkedin" width="85" height="25"></a>
<a href="mailto:apaditya96@gmail.com" target="_blank"><img src="https://img.shields.io/badge/Gmail-red?style=flat-square&logo=Gmail&logoColor=white" alt="Gmail" width="70" height="25"></a>
  
<div align = "right">    
  <a href="#global-terrorism-analysis">(back to top)</a>
</div>


