# Stress in Office

Stress in Office is a model that classifies physiological measurements of stress response. Trained on a [study](#acknowledgments) of email-use patterns and interaction with office stressors, including how these interactions are mediated by individual characteristics, like age, gender, nationality, first language, education.

# Table of Contents
1. [Project Motivation](#project-motivation)
2. [Installation](#installation)
3. [Repository Breakdown](#repository-breakdown)
4. [Results](#results)
5. [Acknowledgements](#acknowledgments)

# Project Motivation
[...]

# Installation
[...]

# Repository Breakdown
- [data](data/) — data used and produced
    - [CSV](https://en.wikipedia.org/wiki/Comma-separated_values) files:
        - [Data to Model](data/data_to_model.csv): CSV file without 
        - [Stress vs. Productivity DataFrame](data/stress_productivity_df.csv): CSV file containing data related to personality tests, physiological measurements and heart rate date from participants
    - [Pickles](https://docs.python.org/3/library/pickle.html):
        - [Study Keys](data/study_keys.pkl): information on variables (meaning, min and max values, etc) extracted from the paper to support model development
        - [Extracted model features](data/model_features.pkl): selected features after dimensionality reduction
- [notebooks](notebooks/) — data treatment process divided into four Jupyter Notebooks with explanations
    - [Data Wrangling](notebooks/1_Data_Wrangling.ipynb)
    - [Data Cleaning](notebooks/2_Data_Cleaning.ipynb)
    - [Pre Data Modeling](notebooks/3_a_Pre_Data_Modeling.ipynb)
    - [Data Modeling](notebooks/3_b_Data_Modeling.ipynb)
- [presentation](presentation/) — data visualizations and presentation
    - [Tableau Workbook](presentation/Stress_in_the_office.twb)
    - [First Iteration for Stakeholders](presentation/Stress_in_the_office.pdf)

# Results
[...]

# Acknowledgements

- [Office Tasks 2019 – A Multimodal Dataset](https://osf.io/zd2tn/)
    - **Contributors:** Ioannis Pavlidis, Shaila Zaman, Amanveer Wesley, Christopher Blank
    - **Date created:** 2019-05-17 06:53 PM | Last Updated: 2019-09-30 08:23 PM
    - **Identifier:** DOI 10.17605/OSF.IO/ZD2TN
    - **Category:**  Project
    - **License:** [CC0 1.0 Universal](https://creativecommons.org/publicdomain/zero/1.0/legalcode)

- [Stress and productivity patterns of interrupted, synergistic, and antagonistic office activities | Nature - Scientific Data](https://www.nature.com/articles/s41597-019-0249-5.epdf)
    - **Authors:** Shaila Zaman, Amanveer Wesley, Dennis Rodrigo Da Cunha Silva, Pradeep Buddharaju, Fatema Akbar, Ge Gao4, Gloria Mark, Ricardo Gutierrez-Osuna & Ioannis Pavlidis
    - **License:**
        > **Open Access**  
        This article is licensed under a Creative Commons Attribution 4.0 International License, which permits use, sharing, adaptation, distribution and reproduction in any medium or format, as long as you give appropriate credit to the original author(s) and the source, provide a link to the Creative Commons license, and indicate if changes were made. The images or other third party material in this article are included in the article’s Creative Commons license, unless indicated otherwise in a credit line to the material. If material is not included in the article’s Creative Commons license and your intended use is not permitted by statutory regulation or exceeds the permitted use, you will need to obtain permission directly from the copyright holder. To view a copy of this license, visit http://creativecommons.org/licenses/by/4.0/.  
        The Creative Commons Public Domain Dedication waiver http://creativecommons.org/publicdomain/zero/1.0/ applies to the metadata files associated with this article.