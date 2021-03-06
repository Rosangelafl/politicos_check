# politicos_check
Analysis in Python / Pandas of the Brazilian Congress under the focus of the judicial processes that deputies and senators answer in federal, state and electoral courts.
Analysis of the Brazilian congress has cross-referenced data from various sources to indicate which and how many legal proceedings respond to Brazilian congressmen. The primary source of the data was the site http://www.politicos.org.br/processos, the data was scraped to a spreadsheet and then cleaned and structured by name of the congressmen, party, state and lawsuits with the links to the courts. This is a journalistic work and, therefore, 98% of the links were checked to verify the veracity of the information. After cleaning the csv files were analyzed with Pandas to withdraw insights on how many processes respond to the congressmen in total, which were the most committed crimes; processes per party; processes by party and state of representation.

First part of a series of data-driven reporting for coverage of the 2018 elections. The idea of background check of the congressmen was conceived in the MOOC "How to cover elections without making a mistake: Data and research to understand voters "promoted by the Knight Center for Journalism in the Americas and the National Newspaper Association (ANJ), in partnership with the Google News Initiative.

Crossing open data from various sources, from the main analysis cuts were made with specific themes such as the environment crossing other open data sources such as Abraji and Ruralometer. Information as campaign donors was obtained through Datascope, Cross Data and Dissemination of Elections and Electoral Accounts of TSE.

Sources.: http://www.politicos.org.br/processos
http://portal.stf.jus.br/
https://www.trf4.jus.br/trf4/
http://publique-se.org.br/
https://ruralometro.reporterbrasil.org.br/
http://www.datascopio.inf.br/
http://cruza.dados.org/
http://divulgacandcontas.tse.jus.br/divulga/#/
