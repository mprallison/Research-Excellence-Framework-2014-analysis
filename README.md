# Research-Excellence-Framework-2014-analysis
A few modules to extract and analyse case study data from REF2014 and form a few musings on what we find

REF2014 (https://impact.ref.ac.uk/casestudies/search1.aspx) includes a collection of research case studies, were authors describe the impact their research as had. Quantifying impact magnitude is not easy, given the place of subjectivity and lack of potentially useful metrics (bredth, uptake, novelty, etc.), but some ideas about what researchers are talking about when they talk about research can be explored.

Modules REF_case_study_data allow case study fields to be extracted according to research discipline and by keyword. The includes categories and text data from JSON API results. I include two analyses and visualisations, with the example of seeing how case studies included under keyword "HIV" are broken down by unit of assessment (discipline) and impact type. You find interesting results for words which might be represeent the research impact, like "policy","influence", "health" and "media".

REF_topic_model currently reads all case studies under keyword "HIV" and generates a topic model of the impact details raw text data. This gives a view of the clustering patterns of salient words in the text. 
