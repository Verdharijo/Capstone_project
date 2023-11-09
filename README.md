# **Genealogy.aid: Facing the Next Phase**

## Problem Statement
Genealogy as a study relies tracing heritage in different mediums, however the most common approach requires photos and artefacts. In addition, the gold-standard for kinship verification is DNA, however that is not possible with long-lost loved ones, be it via death or distance.

In addition, one might not even be familiar with the their own lineage. Singapore has a unique situation of having the world's highest transnational marriage rates, with 1 in 6 marriages being interracial as well. This heralds a generation of individuals that grow up without a strong, pure cultural identity. 

Recently, genealogy has garnered significant interest among the population, with many memoirs and collections being published. However, such knowledge is usually a struggle for the average joe. 

I thus arrive the following problem statement:

*Can a model be used to analyse facial structures to derive a working genetic breakdown of ethnic groups*? 
*Can a model be used to verify if 2 individuals are indeed kin?* 
*Can there be a convenient platform to gain culturally relevant and factual information about the cultural migrations into Singapore?*


## Datasets Used
- train_relationship_local.csv
- train_relationships_fitw.csv
- genetic_ancestry.xlsx

## Data Dictionary
|Feature|Type|Dataset|Description|
|---|---|---|---|
|p1|filepath|train_relationship|Represents the filepath of the 1st image of a pair of images that shares a kin relationship|
|p2|filepath|train_relationship|Represents the filepath of the 2nd image of a pair of images that shares a kin relationship|
|Cambodian|int|genetic_ancestry|1 if genetic breakdown is positive|
|Malay|int|genetic_ancestry|1 if genetic breakdown is positive|
|Indonesian|int|genetic_ancestry|1 if genetic breakdown is positive|
|Punjabi|int|genetic_ancestry|1 if genetic breakdown is positive|
|Bengali|int|genetic_ancestry|1 if genetic breakdown is positive|
|Gujarati|int|genetic_ancestry|1 if genetic breakdown is positive|
|Tamil|int|genetic_ancestry|1 if genetic breakdown is positive|
|Telugu|int|genetic_ancestry|1 if genetic breakdown is positive|
|Northern Han|int|genetic_ancestry|1 if genetic breakdown is positive|
|Southern Han|int|genetic_ancestry|1 if genetic breakdown is positive|
|Japanese|int|genetic_ancestry|1 if genetic breakdown is positive|
|Others|int|genetic_ancestry|1 if genetic breakdown is positive|


## Conclusions and Recommendations
**Solution**

A one-stop platform that Singaporeans interested in genealogical research can individually visit and access the tools present.
- Analyse Facial Images to see probability of certain ancestral lineages
- Predict probability of kinship in unknown images to check if someone could be related to you
- Providing more understanding on the greater cultural ecosystem in Singapore

**Social Impact**
- Cost Reduction
  - Ancestral tests are expensive, going for ~$250 per test. 
  - Reduces manhours in identifying potential kin
- Social Benefit
  - Allows individuals access to tools to kickstart their genealogical journey


 ## Future Work
- Increase classes for Ancestral Lineage Model: Increasing from 6 to 12 initally then expanding beyond. 
- Improve model accuracy for facial kinship verification mode by utilizing more localised facial images in order to build a more robust database that is applicable to local use-cases
- Train LLM Model to serve as an advisor from genealogical beginners, recommending a project plan and directions to pursue as well.


## References
- https://theindependent.sg/more-singaporeans-marrying-foreigners/ 
- https://genealogysocietysingapore.com/ 
- https://www.straitstimes.com/singapore/12-family-histories-documented-in-new-book-on-singapore-s-multicultural-legacy
- https://www.straitstimes.com/singapore/china-based-firm-ties-up-with-genealogy-society-to-help-chinese-singaporeans-trace-roots
- https://www.straitstimes.com/singapore/genealogy-book-that-traces-600-years-of-s-pore-family-history-to-include-women-for-first-time
- https://phys.org/news/2021-08-genomic-analysis-peranakan-chinese-reveals.html
- https://finance.yahoo.com/news/global-genealogy-products-services-market-151800865.html
