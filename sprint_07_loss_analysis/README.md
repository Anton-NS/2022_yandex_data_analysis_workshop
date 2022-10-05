<div align="center">

<div>  
  &nbsp; 
</div>

# Sprint 07 Loss analysis of the Procrastinate Pro+ application

[![Telegram support](https://img.shields.io/badge/Support-Telegram-blue)](https://t.me/anton_siluyanov)
[![Facebook](https://img.shields.io/badge/Facebook-1877F2?logo=facebook&logoColor=white)](https://www.facebook.com/AntonSiluDS/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?logo=linkedin&logoColor=white)](https://www.linkedin.com/in/siluyanov/)

<div>  
  &nbsp; 
</div>
	
  :star: **Star me on GitHub — it motivates me a lot!** :star:
	
<div>  
  &nbsp; 
</div>
</div>

<blockquote>
  &nbsp;
	
  *“✔️ Great features! 👍”*  

 Reviewer's comment when submitting the project.

  &nbsp;

</blockquote>

## :book: &nbsp; Table of Contents
* [Project Description](page_with_curl--project-description)
* [Project Results](bar_chart--project-description)
* [Project Composition](#clipboard--project-composition)
* [Configuration](#clipboard--configuration)
* [File Structure](#file_cabinet--file-structure)
* [Dependencies](#notebook_with_decorative_cover--dependencies)
* [Acknowledgments](#trophy--acknowledgments)

## :page_with_curl: &nbsp; Project Description
A task for a marketing analyst of the Procrastinate Pro+ entertainment application. Despite huge investments in advertising, the company has been suffering losses for the last few months. The task is to understand the reasons and help the company become profitable again.

**Project Characteristics**
| Fields of activity | Areas of activity | Tools | Skills |
|:--|:--|:--|:--|
| Internet services | Marketing Analyst | Python | Data preprocessing |
| Startups          |Product Analyst | Pandas| Unit economy |
| | | Matplotlib | Product metrics |
| | | Seaborn | |


## :bar_chart: &nbsp; Project Results
The data from ProcrastinatePRO+ was analyzed.

Various metrics were calculated, cohort analysis was used: LTV, CAC, Retention rate, DAU, WAU, MAU, etc. 

Previously written metric calculation functions were used. 

Conclusions have been drawn based on the data obtained.

</br>

**Project screenshots**

Attraction dynamic

<img src="sprint_07_loss_analysis/pics/s07_attraction_dynamic.png" alt="Attraction dynamic" width="523px"/>

LTV table

<img src="sprint_07_loss_analysis/pics/s08_ltv_table.png" alt="LTV table" width="870px"/>

## :clipboard: &nbsp; Project Composition
1. Project description
1. Research plan
1. General comments on the approach and logic of the project
1. **Step 0**. Getting ready for work
   1. Importing libraries
   1. Setting project parameters
   1. Project Functions
   1. Loading Data
1. **Step 1**. A general look at the data
   1. Study of general information
      1. Familiarity with visits_info_short data
      1. Familiarity with orders_info_short data
      1. Getting to know the costs_info_short data
1. **Step 2**. Data Preparation
   1. Duplicates
   1. Implicit duplicates
   1. Omissions
   1. We will bring the data to the necessary types
1. **Step 4**. Functions for calculating and analyzing LTV, ROI, retention and conversion
   1. `get_profiles_full`
   1. `get_retention`
   1. `plot_retention`
   1. `get_conversion`
   1. `plot_conversion`
   1. `get_ltv`
   1. `get_profiles CAC`
   1. `get_ltv_roi`
   1. `plot_ltv_roi`
1. **Step 5**. Research analysis
   1. Create profiles and fill in the data
   1. Source countries of visits
   1. User devices
   1. Channels for attracting users
1. **Step 6**. Marketing expenses
1. General expenses
1. User expenses
1. **Step 7**. Payback of advertising
   1. Total return on advertising
   1. Payback — advertising channels
   1. Payback — countries
   1. Payback — devices
   1. Conversions and Retention
      1. Conversions - Devices
      1. Conversions - countries
      1. Conversions - advertising channels
      1. Hold - devices
      1. Retention - countries
      1. Retention - Advertising channels
      1. Answers to questions
1. Appendix 1: The original assignment of the project work
1. Appendix 2: Data description

