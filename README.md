
**OTUS Machine Learning Professional**
### **Homework 5**

### Parsing and NLP
![hw5p_header](https://user-images.githubusercontent.com/73858914/170866768-f64bea0c-1af1-43e1-b8b9-623d2a1bb943.png)

**Goals:**  
1. Parse archive of Medium "Towards data science" publications:
- Parsed article's data are:
    - url
    - author, 
    - title
    - subtitle
    - claps (likes)
    - responses (comments)
    - reading time
    - publication date
2. NLP 
- Split data into train and test sets;
- Apply TF-IDF to text data (title+subtitle);
- Build regression model with claps as target and visualize results.

**Additional goals:**  

- Perform EDA to check dependencies between parsed features. Use [binsreg](https://github.com/nppackages/binsreg) estimations.
- Have a look at [Texthero](https://github.com/jbesomi/texthero) NLP library

**Binder notebooks:**

main.ipynb: Text preprocessing, TF-IDF, regression   
parsing.ipynb: Parsing   
eda.ipynb: EDA   

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/oort77/OTUS_PRO_HW5/main)  

