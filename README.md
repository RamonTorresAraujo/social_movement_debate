####################################
# Brazilian Social Movement Debate #
####################################

This repository contains the codes relate to a project, already accepted to be published, where we analyzed 447 articles about social movement published in the prestigious Brazilian journals.

Szwako, J.; Dowbor, M.; Araujo, R. (forthcoming), The production of academical articles about social movements published in Brazilian journals (2000-2017): trends and innovations, BIB.   

# Main research question:

Is there a consolidated debate with shared problems and theories about social movements in Brazil?   

# Work steps:

1. We scraped from Scielo platform the urls, titles, abstracts, and references of the articles with words (and their plurals) 'movimento', 'ação coletiva', 'conflito', 'confronto', 'protesto', 'mobilização', 'manifestação', and 'reivindicação',  that were published, between 2000 and 2017, in journals ranked by Capes as A1 and A2 at the Antropology, Political Science, and Sociology fields.    

2. We read all titles/abstracts and selected the articles about social movements. We decided select the articles manually, instead of automatically, because we noticed that the key words were not intuitive.    

3. After select our corpus, we cleaned and prepared the data, removing the punctuation, the stop words, treating the synonyms, and so on. 

4. We performed the EDA, checking the vocabulary and counting the frequency of words. 

5. We performed network analyses of co-words and co-references, analyzing measures as density and betweenness, and identifying clusters of words and references.    
