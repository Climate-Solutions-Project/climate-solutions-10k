# climate-solutions-10k  
This repository provides data for climate solutions, defined as products and services that develop or deploy technologies in a transition to a low-carbon economy. We fine-tune a GPT3.5 model to identify climate solutions sentences in 10-K Item 1 Business Description.  

**CSmeasure10k_firmyear data contains the following variables:**  
conm: company name  
gvkey: company identifier   
fyear: fiscal year  
**CS Measures:**  
gpt_total_sentence: total number of 10-K Item 1 sentences  
gpt_positive: number of 10-K Item 1 sentences classified as a climate solutions sentence  
gpt_climate_ratio: main Climate Solutions Measure, defined as gpt_positive divided by gpt_total_sentence, times 100  
gpt_top_\*: the percent of climate solutions sentences in the top 50 and 100 sentences in 10-K Item 1  
gpt_weighted_\*: a weighted measure placing a larger weight on earlier sentences in 50 and 100 sentence-increments  
gpt_rolling_\*: the percent of climate solutions sentences in the 50- and 100-sentence-segment with the highest ratio of climate solutions sentences  
**CS Topics:**   
stc_\*: number of 10-K Item 1 sentences belonging to one of nine topic categories, divided by gpt_total_sentence, times 100  
ts_\*: number of 10-K Item 1 sentences belonging to one of 88 topics, divided by gpt_total_sentence, times 100  
  
Data available for firms in 13 industry groups from fiscal year 2005-2022.  
For topic details, see CSmeasure_topics file.  


**Reference:** Lu, S., Serafeim, G., Xu, S., & Awada, M. (2025). Tracking Business Opportunities for Climate Solutions using AI in Regulated Accounting Reports.
