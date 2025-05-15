# Literature Review

Approaches or solutions that have been tried before on similar projects.

**Summary of Each Work**:

- **Source 1**: [Does Machine Learning Offer Added Value Vis-à-Vis Traditional Statistics? An Exploratory Study on Retirement Decisions Using Data from the Survey of Health, Ageing, and Retirement in Europe (SHARE)]

  - **[Link](https://www.mdpi.com/2227-7390/10/1/152?)**
  - **Objective**:
    - Assess whether there is a benefit of using machine learning methods over traditional statistics when predicting retirement decisions based on the SHARE dataset
  - **Methods**:
    - Event History Analysis (traditional statistics) on longitudinal data
    - Random forests for survival analysis (machine learning approach) - R package randomForestSRC
    - Included covariates (based on Scharn et al. [2] and data availability):
        - Age, gender, country
        - Self-perceived health (sphus)
        - Number of grandchildren (binarized)
        - Rent or mortgage payments (binarized)
        - Years of education
    - For longitudinal, this is what they did:
      - Focused only on respondents working in wave 1, from countries participating in all selected waves.
      - After filtering for missing employment data, final sample: 2,882 respondents.
      - A person–period dataset was created, with retirement status measured at the end of each interval.

  - **Outcomes**:
    - Firstly, they summarize previous studies that assessed what factors contributed to retirement decisions. Here are some of them that may be interesting to us (though somewhat obvious maybe...):
        -  Health and physical work demands play a key role in early retirement, especially for manual workers. Sundstrup et al. [68], van der Mark-Reeuwijk [80], Hagan et al. [79], De Preter et al. [66]
        -  Low education levels and stable careers are associated with earlier retirement. Trentini [77]; also De Breij et al. [82]
        -  Spousal influence: A partner’s retirement increases likelihood of retiring; divorce or widowhood delays it. Radl & Himmelreicher [83]
        -  Gender norms: Female main earners tend to retire earlier than secondary earners.  Bertogg et al. [84]
        -  Family and caregiving responsibilities, including grandparenting, increase likelihood of retirement. De Preter et al. [66], Van Bavel & De Winter [81]
        - and many more... but to name a few.
    - They find that the predictive capabilites of random survival forests are better than the cox regression (traditional statistics) - this is good for us, and we can now assess how good DL methods are (let's hope better). We will also incorporate much more data I presume.
    - Cox regression of course offers much more insight into the actual features that affect retirement - this is less the case for the RSF and likely even less if we use DL.
      
  - **Relation to the Project**:
    This article adresses our main project idea directly - employing ML to predict retirement decisions.
    One thing that becomes very clear is that ML is not as widely adopted in this field as we may have thought (with DL not mentioned at all...), which legitimizes our project idea. ("Unsupervised learning, which attempts to find patterns in the data without any guidance from the researcher [93], is beyond the scope of this article.") What's more, according to this study ML outperforms traditional statistics for prediction. And noone has really used DL, which will likely be even better, making our study actually quite novel and relevant  - yay!
    
    One thing that we must decide is whether we want to perform a longitudinal analysis (likely rather complicated, but more sensible) or a more simple classification approach (i.e., predict why someone retired).


  
- **Source 2**: [Millennials and Early Retirement: An Exploratory Study]

  - **[Link](https://www.mdpi.com/2673-8104/3/2/15)**
  - **Objective**:
    - explore to which extend working conditions and health factors shape Millennials' preferences to retire early
  - **Methods**:
    - classification decision tree model
  - **Outcomes**:
    - Millennials who have a low job satisfaction and visit the doctor's office often (more than 5 times a year) have a 72% chance to wish to retire early
    - Life quality, BMI, self-health-assessment, Depression and job terms also were found to have influence but less 
    - looking at the whole sample though, Millennials do not wish to retire early in general
  - **Relation to the Project**:
    - helpful to identify key variables that can be usefull to feed into our model
    - decision tree model a a potential classification model 

- **Source 3**: [Title of Source 3]

  - **[Link]()**
  - **Objective**:
  - **Methods**:
  - **Outcomes**:
  - **Relation to the Project**:

- **Source 4**: [Survey of Health, Ageing and Retirement in Europe (SHARE) - Dataset]

  - **[Link](https://share-eric.eu/data/)**
  - Data used as the basis for our model
