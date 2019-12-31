# Research-Excellence-Framework-2014-analysis
A few modules to extract and analyse case study data from REF2014 and form a few musings on what we find

REF2014 (https://impact.ref.ac.uk/casestudies/search1.aspx) includes a collection of research case studies, where authors describe the impact of their research. Quantifying impact magnitude is not easy, given the place of subjectivity and lack of potentially useful metrics (bredth, uptake, novelty, etc.), but some ideas about what researchers are talking about when they talk about research can be explored.

Modules in REF_case_study_data allow case study fields to be extracted according to research discipline or by keyword. This includes categories and text data from JSON API results. I include two analyses and visualisations, with the example of seeing how case studies included under keyword "HIV" are broken down by unit of assessment (discipline) and impact type. You find interesting results for words which might reflect the authors' understanding of their impact, like "policy", "influence", "health", "media".

REF_topic_model currently reads all case studies under keyword "HIV" and generates a topic model of the impact details text. This gives a view of the clustering patterns of salient words in the text. 
