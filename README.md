# NYCDSA_PhysicianPayments
The following project was submitted as part of the NYC Data Science Academy (2020 cohort) with the intended purpose of creating an RShiny app to explore the relationship between healthcare industry payments to physicians and subsequent rates of prescriptions made by physicians. Data publically available through the 'Centers for Medicare & Medicaid Services' and 'ProPublica' organizations included over 14 million payments made to physicians, and 3 million prescription claims by physicians (top 50 drugs), respectively. Extensive exploratory data analysis was performed to gain key insights into the relationships between (1) healthcare industry type and physician subspecialty, and (2) pharmaceutical payments and number of prescription claims. This infromation may be vital as drug companies look to use their money to expand market influence, as well as regulatory bodies aimed to minimize the influence of money in how healthcare is provided to patients. 

## RShiny App and Blogpost:

RShiny: https://jah377.shinyapps.io/NYCDSA_doctorpayments_jonharris_rshinyapp/

Blogpost: https://nycdatascience.com/blog/student-works/what-is-in-your-doctors-wallet/

## Author Information:
**Jonathan A. Harris, MS**

Linkedin: https://www.linkedin.com/in/jonharriseit

GitHub: https://github.com/jah377

ResearchGate: https://www.researchgate.net/profile/Jonathan_Harris23

## Relevant Folders and Files:
**CMS_opepay_datacleaning_chunk.ipynb**

  Contains processes for:
    - Chunking import and cleaning up of CMS-recorded payments to health care professions in 2016
    - Information used to explore differences in payment amounts between specialities, and industry types
  
 **CMS_openpay_analysis.Rmd**

  Contains processes for:
    - Generates plots of the analysis describe above

  
**ProPublic_analysis.Rmd**
  
  Contains  processes for:
    - Executes all analysis related to ProPublica dataset
    - Generates plots

**NYCDSA_doctorpayments_jonharris_rshinyapp**
  
  Folder contains files for:
    - Creation of RShiny app
    - All analyses found within the app



