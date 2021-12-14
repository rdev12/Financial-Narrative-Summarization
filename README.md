# Financial-Narrative-Summarization

**Aim:** Identify and summarise the narrative sections of the annual reports

Narrative sections contain textual information and reviews by the firm’s management and board of directors. They usually contain textual information and reviews by the firm’s management and board of directors instead of statistics and tables. 

## Dataset
The task dataset has been extracted in TXT format from UK annual reports published in PDF file format.

-   Annual Report: Around 80 pages on average
-   Target Summary: 1000 words maximum
-   Extracted sections that are considered as the summary of the whole report - Not written!

### Metric
ROUGE 2 F1 score on test set will be the main metric 
