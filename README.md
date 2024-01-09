## Max's Awesome Capstone
=========================

### Project Overview  
This project aimed to explore the relationship between historical traffic data and highway construction projects. I hypothesized that high traffic volumes in specific areas would precede the construction of new highways, leading to a subsequent decrease in traffic after completion. However, my analysis revealed that this was not the case. I was unable to find a clear correlation between traffic patterns and highway construction projects, and the only significant factor influencing annual average daily traffic (AADT) appeared to be major global events, such as the COVID-19 pandemic. There were other factors that made this project infeasible given the time remaining in the bootcamp such as data disparity, hidden complexity of highway planning and the limited predicting power that a model trained on this data could produce.   Traffic data is typically tracked by district, while highway project data is associated with individual streets. This inconsistency hampered my ability to directly compare and analyze the datasets. There is also no dataset that I could find that listed past highway projects outside of the budget but the budget datasets did not contain constuction start dates or end dates, just dates for payment received. Highway construction projects are multifaceted and involve various factors beyond just traffic volume. Capturing these complexities within the data and model proved challenging. Highway planning is a long legislative process that takes years to plan one highway. One symptom of this is that many future highway projects are planned years in advance. analysis revealed that AADT is primarily influenced by external factors like major world events, making it difficult to predict future highway construction based solely on historical traffic data. With highway projects planned for the next few years the limited prediction power of a model using AADT would not be able to make accurate predictions for the required 10-30 years that may be required before the next highway project is approved. Although my hypothesis was not validated, the project provided valuable insights into the lack of a direct correlation between traffic patterns and highway construction projects. The project emphasized the importance of data consistency and accessibility when analyzing complex relationships between different datasets. The findings encourage further research into alternative methods for predicting highway construction needs, potentially incorporating additional factors beyond traffic data. I will be pursuing other subects for my capstone but given more time these would be my next steps: 
1. Data Integration: Explore data merging and transformation techniques to bridge the gap between traffic district and street-level highway project data.
2. Model Expansion: Investigate the incorporation of additional factors, such as population growth, economic trends, and government policies, into predictive models for highway construction.
3. Alternative Data Sources: Investigate the potential of non-traditional data sources, such as satellite imagery or social media, to provide insights into traffic patterns and future construction needs.

While the initial hypothesis was not confirmed, this project yielded valuable learnings about the challenges of analyzing traffic-construction relationships and the need for more holistic approaches to predicting future infrastructure needs. By addressing data limitations and exploring alternative methods, future research can build upon these findings to develop more robust and insightful models for guiding infrastructure development.
... 
...
...

### Walkthrough Demo

...
...
...

### Project Flowchart

...
...
...

### Project Organization

...
...
...

* `data` 
    - contains link to copy of the dataset (stored in a publicly accessible Google Drive folder)
    - saved copy of aggregated / processed data as long as those are not too large (> 10 MB)

* `model`
    - joblib dump of final model / model object

* `notebooks`
    - contains all final notebooks involved in the project

* `reports`
    - contains final report which summarises the project

* `references`
    - contains papers / tutorials used in the project

* `src`
    - Contains the project source code (refactored from the notebooks)

* `.gitignore`
    - Part of Git, includes files and folders to be ignored by Git version control

* `capstine_env.yml`
    - Conda environment specification

* `Makefile`
    - Automation script for the project

* `README.md`
    - Project landing page (this page)

* `LICENSE`
    - Project license

### Dataset

...
...
...

### Credits & References

...
...
...

--------
