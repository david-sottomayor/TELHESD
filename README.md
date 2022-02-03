# TELHESD
## Technology Enhanced Learning for Higher Education Students with Disabilities
This repository holds the dataset collected for the paper with the above title

It lists the Portuguese Higher Education Institutions, their websites and the WCAG 2.1 compliance rating for 3 pages on those websites (homepage, programs, applications), wether the site is compliant with 83/2018 Portuguese Law Decree that ruled that from September, 23rd of 2020 all institutions websites must have an accessibility statement on the domain/acessibilidade page. It finally rates each site weighting the average of the 3 WCAG 2.1 ratings at 75% and Accessibility Statement Compliance at 25%

Dimensions:
Instituição: Portuguese Higher Education Institution Name
Subsistem: Cathegory (Universitary, Polytechnic, Polytechnic Organic Unit Not Attached to an University)
Sector: Cathegory (Public, Private, Military/Police)	
URL: Institution Site (homepage)
Homepage: accessMonitor 2.1 Rating (0 to 10) of the homepage 	
Programs: accessMonitor 2.1 Rating (0 to 10) of the programs page	
Applications: accessMonitor 2.1 Rating (0 to 10) of the applications page
Accessibility Statement: Normalized binary score (0: Non Compliant, 10: Compliant)	
Rating: AVG(Homepage, Programs, Applications) * 0.75 + (Accessibility Statement) * 0.25	


References:
WCAG 2.1 Rating Tool:	AMA accessMonitor 2.1	
https://accessmonitor.acessibilidade.gov.pt/
Higher Education Institutions List:	DGES
https://www.dges.gov.pt/pt/pesquisa_cursos_instituicoes?instituicao=&cursos=&distrito=&tipo_ensino=&tipo_estabelecimento=&area=&tipo_curso=
